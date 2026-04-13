# Xuanjing Huang's Academic Website

A bilingual (English/Chinese) academic website for Professor Xuanjing Huang (黄萱菁), built with Jekyll.

## Overview

This is the personal academic website of Professor Xuanjing Huang at [Fudan University](https://www.fudan.edu.cn/en/). The site showcases her research in Natural Language Processing (NLP) and Large Language Models (LLMs), including publications, talks, awards, grants, and teaching activities.

**Live Site:** https://xuanjing-huang.github.io

## Features

- **Bilingual Support**: Full English and Chinese language versions
- **Jekyll-powered**: Static site generation with Markdown content
- **Academic-focused**: Designed for researchers with sections for publications, talks, CV, and more
- **Responsive Design**: Mobile-friendly using Sass/SCSS
- **Collections**: Organized content for publications, talks, teaching, and portfolio
- **Analytics**: Google Universal Analytics integration

## Project Structure

```
├── _config.yml          # Jekyll configuration
├── _data/               # Data files (navigation, authors, comments)
├── _pages/              # Page content (about, publications, talks, etc.)
├── _posts/              # Blog posts
├── _publications/       # Publication entries (Markdown files)
├── _talks/              # Talk entries
├── _teaching/           # Teaching materials
├── _portfolio/          # Portfolio items
├── _includes/           # Reusable HTML components
├── _layouts/            # Page layouts
├── _sass/               # Sass stylesheets
├── assets/              # CSS, JavaScript, fonts, images
├── files/               # PDF files (publications, CV)
├── images/              # Image assets
└── markdown_generator/  # Tools for generating publication markdown
```

## Navigation Structure

### English
- About, Publications, Talks, Awards, Services, Grants, Teaching, Contact

### Chinese (中文)
- 个人简介, 学术论文, 学术报告, 获奖荣誉, 学术服务, 科研项目, 教学, 联系

## Getting Started

### Prerequisites

- Ruby (>= 2.4)
- Bundler
- Jekyll and its dependencies

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/xuanjing-huang/xuanjing-huang.github.io.git
   cd xuanjing-huang.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser at `http://localhost:4000`

### Building for Production

```bash
bundle exec jekyll build
```

The static site will be generated in the `_site` directory.

## Content Management

### Adding Publications

Create a new Markdown file in `_publications/` with the following front matter:

```yaml
---
title: "Your Publication Title"
collection: publications
permalink: /publications/your-publication/
author: Xuanjing Huang
pub_type: Conference/Journal
year: 2024
---
```

### Adding Talks

Create a new Markdown file in `_talks/` with the following front matter:

```yaml
---
title: "Talk Title"
collection: talks
permalink: /talks/talk-title/
author: Xuanjing Huang
date: 2024-01-01
venue: Conference Name
---
```

### Language Toggle

The site supports bilingual content. Pages can specify language in front matter:
```yaml
lang: en  # or "zh" for Chinese
```

## Technologies Used

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [Kramdown](https://kramdown.gettalong.org/) - Markdown processor
- [Sass/SCSS](https://sass-lang.com/) - CSS preprocessor
- [Font Awesome](https://fontawesome.com/) - Icons
- [Academicons](https://jpswalsh.github.io/academicons/) - Academic icons
- [Google Analytics](https://analytics.google.com/) - Analytics

## Customization

### Site Settings

Edit `_config.yml` to customize:
- Site title and description
- Author information
- Social links
- Analytics tracking ID

### Navigation

Modify `_data/navigation.yml` to change the navigation menu structure.

### Styling

Customize styles in `_sass/` directory. Main stylesheet is in `assets/css/main.scss`.

## Deployment

The site is deployed to GitHub Pages. Any push to the `master` branch will automatically trigger a deployment.

## License

This project is for academic use. Content (publications, text, images) is copyrighted by the author unless otherwise noted.

## Contact

- **Email**: xjhuang@fudan.edu.cn
- **Google Scholar**: [Profile](https://scholar.google.com/citations?user=RGsMgZA4H78C)
- **Semantic Scholar**: [Profile](https://www.semanticscholar.org/author/Xuanjing-Huang/1790227)
- **ORCID**: [0000-0001-9197-9426](https://orcid.org/0000-0001-9197-9426)

## Acknowledgments

This website is built based on the [Jekyll Academic template](https://github.com/academicpages/academic-pages).
