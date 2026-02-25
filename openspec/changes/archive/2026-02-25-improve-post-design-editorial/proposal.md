## Why

The current blog post layout was designed generically and feels like a standard blog rather than a professional news publication. Individual posts lack editorial hierarchy, the typography isn't optimized for comfortable long-form reading, and the main page uses "Blog" terminology instead of presenting news professionally. This undermines the credibility of the content.

## What Changes

- **Post layout**: Transform individual posts to follow editorial/news design patterns
  - Add category tag with uppercase styling
  - Create dramatic title hierarchy (larger, bolder)
  - Add subtitle/dek support
  - Enhance byline with author, date, and read time
  - Narrow content column (max 680px) for optimal reading
  - Increase body font size (18-20px)
  - Improve line-height (1.8) and paragraph spacing
  - Add styled pull quotes with left border accent
- **Main page**: Rename "Blog" to "News" terminology
  - Update header navigation
  - Enhance post cards with date prominence
  - Make the index feel like a news front page
- **Keep brand identity**: Maintain #00639C blue for headings/links

## Capabilities

### New Capabilities
- `editorial-post-layout`: News-style individual post layout with improved typography
- `news-homepage`: Main page styled as news front page

### Modified Capabilities
- `jekyll-theme-stockcast`: Enhanced styling for editorial design

## Impact

- Modified: `_layouts/post.html` - new editorial layout
- Modified: `_layouts/home.html` - news-style homepage
- Modified: `assets/css/style.css` - typography and spacing improvements
- Modified: `_includes/header.html` - "News" terminology
- Affected: All blog posts, homepage appearance
