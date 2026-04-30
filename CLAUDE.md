# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a bilingual (English/Chinese) academic website for Professor Xuanjing Huang at Fudan University, built with Jekyll and deployed to GitHub Pages. The site showcases NLP/LLM research publications, talks, awards, grants, and teaching activities.

## Development Commands

```bash
# Install dependencies
bundle install

# Run development server (http://localhost:4000)
bundle exec jekyll serve

# Build for production (outputs to _site/)
bundle exec jekyll build

# Run with custom config (e.g., for testing different settings)
bundle exec jekyll serve --config _config.dev.yml
```

## Architecture

- **Jekyll with GitHub Pages**: Uses `github-pages` gem. All plugins in `_config.yml` whitelist are GitHub Pages compatible.
- **Collections**: Four content collections - `_publications/`, `_talks/`, `_teaching/`, `_portfolio/`. Each outputs to its own permalink path.
- **Bilingual**: Pages specify `lang: en` or `lang: zh` in front matter. English and Chinese versions exist as separate files (e.g., `publications.md` and `publications-zh.md`).
- **Templates**: `_layouts/` for page layouts, `_includes/` for reusable components (head, scripts, navigation, etc.), `_sass/` for styles.
- **Markdown**: Kramdown with GFM enabled. Publication/talk entries use Markdown with YAML front matter.

## Content Structure

- `_publications/` - Individual publication entries with `pub_type` (Conference/Journal) and `author` fields
- `_talks/` - Talk entries with `venue` and `date`
- `_pages/` - Static pages (About, CV, Awards, Services, Grants, etc.)
- `_data/navigation.yml` - Navigation menu structure
- `markdown_generator/` - Tool for batch generating publication markdown

## Key Files

- `_config.yml` - Main Jekyll configuration (locale, collections, plugins, defaults)
- `_config.dev.yml` - Development-specific overrides
- `assets/css/main.scss` - Main stylesheet importing Sass partials
