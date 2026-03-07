# Bilingual Site Restructuring Plan

## Current State Analysis

The site currently has a mix of Chinese and English content:

- **Chinese homepage**: [`chinese.md`](_pages/chinese.md) at `/chinese/`
- **English homepage**: [`about.md`](_pages/about.md) at `/` (also `/about/`)
- **Bilingual pages**: [`awards.md`](_pages/awards.md) uses Chinese with English translations in parentheses
- **English-only pages**: [`publications.md`](_pages/publications.md), [`talks.html`](_pages/talks.html), [`services.md`](_pages/services.md), [`grants.md`](_pages/grants.md), [`teaching.md`](_pages/teaching.md), [`contact.md`](_pages/contact.md), [`cv.md`](_pages/cv.md)
- **Chinese-only content**: [`_talks/`](_talks/) collection contains Chinese talk descriptions
- **Navigation**: Mixed Chinese/English menu in [`_data/navigation.yml`](_data/navigation.yml)

## Goal

Create separate Chinese and English versions for each page, with:
1. Chinese homepage at `/chinese/`
2. English homepage at `/` (or `/about/`)
3. Mutual links between language versions
4. Consistent navigation per language

## Proposed Architecture

### 1. Page Structure

Create parallel page sets using filename suffixes:

```
_pages/
├── about.md                    # English homepage (permalink: /)
├── chinese.md                  # Chinese homepage (permalink: /chinese/)
├── publications.md             # English publications
├── publications-zh.md          # Chinese publications (permalink: /publications/zh/)
├── talks.html                  # English talks listing
├── talks-zh.html               # Chinese talks listing (permalink: /talks/zh/)
├── awards.md                   # English awards (extract English translations)
├── awards-zh.md                # Chinese awards (Chinese-only content)
├── services.md                 # English services
├── services-zh.md              # Chinese services
├── grants.md                   # English grants
├── grants-zh.md               # Chinese grants
├── teaching.md                 # English teaching
├── teaching-zh.md             # Chinese teaching
├── contact.md                  # English contact
├── contact-zh.md              # Chinese contact
├── cv.md                       # English CV
└── cv-zh.md                   # Chinese CV
```

### 2. Content Strategy

- **English pages**: Use existing English content where available; translate Chinese content where missing.
- **Chinese pages**: Use existing Chinese content; translate English content where missing.
- **Bilingual pages like awards.md**: Split into separate language versions:
  - `awards-zh.md`: Chinese text only (remove English parentheses)
  - `awards.md`: English text only (extract English translations)
- **Talks collection**: Keep Chinese talk files in `_talks/` but create English translations as separate files? Or create a parallel collection `_talks_en/`. Simpler: keep Chinese talks and add English translations within same files (as previously attempted but reverted). However, user may prefer separate English talk pages.

### 3. Navigation

Update `_data/navigation.yml` to support two language menus:

Option A: Two separate navigation files:
- `_data/navigation-en.yml`
- `_data/navigation-zh.yml`

Option B: Single file with language keys:

```yaml
main_en:
  - title: "About Me"
    url: /
  - title: "Publications"
    url: /publications/
  # ...

main_zh:
  - title: "个人简介"
    url: /chinese/
  - title: "发表论文"
    url: /publications/zh/
  # ...
```

Update layout templates to use appropriate navigation based on page language.

### 4. Language Switcher

Add a language switcher component in the site header/footer that:
- Detects current page language
- Offers link to counterpart page in other language
- Uses consistent placement (e.g., top-right corner)

Implementation: Add a `lang` front matter to each page (e.g., `lang: en` or `lang: zh`). Use Liquid logic to generate switcher links.

### 5. Mutual Linking

Each page should include a prominent link to its counterpart, e.g.:

> **English version** | **中文版**

Place near page title or in sidebar.

### 6. URL Patterns

- English pages: `/page/` (existing)
- Chinese pages: `/page/zh/` (or `/zh/page/`)

Choose consistent pattern. Recommend `/page/zh/` to keep existing English URLs unchanged.

### 7. Collections Handling

- **Talks**: Create English translations of each talk file (new files `_talks/icml-en.md` etc.) or add English fields to existing front matter.
- **Publications**: Already English; need Chinese translations? Possibly not necessary as publications are international.

## Implementation Steps

1. **Create Chinese versions of English pages**
   - Translate content
   - Set appropriate permalinks
   - Add `lang: zh` front matter

2. **Create English versions of Chinese pages**
   - Translate `chinese.md` to English (already exists as `about.md`)
   - Translate Chinese-only content in `awards.md` etc.

3. **Split bilingual pages**
   - Separate `awards.md` into Chinese and English versions

4. **Update navigation configuration**
   - Create language-specific navigation
   - Update template to switch based on page language

5. **Add language switcher component**
   - Modify `_includes/masthead.html` or `_includes/sidebar.html`

6. **Update talk pages**
   - Decide on approach for talks collection
   - Implement chosen solution

7. **Testing**
   - Verify all links work
   - Check language consistency
   - Validate mobile responsiveness

## Considerations

- **SEO**: Use `hreflang` tags for search engines
- **Fallbacks**: If a page lacks translation, default to available language
- **Maintenance**: Future updates need to be made in both language versions

## Timeline

This is a medium-sized project requiring careful content translation and template modifications. Estimated effort: 2-3 days of focused work.

## Next Steps

1. Approve this architecture plan
2. Begin implementation with Chinese page creation
3. Iteratively test and refine

---

*Plan created by Roo on 2026-03-07*