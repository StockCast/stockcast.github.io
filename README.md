# StockCast News

A Jekyll-based blog for StockCast news and updates.

## Prerequisites

- **Ruby** 2.7 or higher
- **Bundler** gem (`gem install bundler`)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd stockcast-news
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

## Local Development

To start the local development server:

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Build for Production

To build the site for production:

```bash
bundle exec jekyll build
```

The static files will be generated in the `_site/` directory.

## Deployment

This site is configured for deployment to GitHub Pages:

1. Push your changes to the `main` branch on GitHub
2. Go to the repository settings on GitHub
3. Enable GitHub Pages from the `main` branch
4. Your site will be deployed at `https://<username>.github.io/<repo>/`

## Adding New Posts

Create a new Markdown file in the `_posts/` directory with the following naming convention:

```
YYYY-MM-DD-post-title.markdown
```

Add the required front matter:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0300
author: StockCast
categories: category1 category2
---
```

Your post content goes here...

## Project Structure

```
stockcast-news/
├── _config.yml          # Jekyll configuration
├── _layouts/           # Page layouts (default, home, post)
├── _includes/           # Reusable components (header, footer)
├── _posts/              # Blog posts (Markdown files)
├── assets/
│   └── css/
│       └── style.css   # Custom theme styles
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```
