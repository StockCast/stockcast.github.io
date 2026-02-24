## Why

The current Jekyll blog uses the default minima theme which doesn't match the StockCast brand. We need a custom Jekyll theme that provides a cohesive visual experience when users navigate from stockcast.com.br to the news section (news.stockcast.com.br), maintaining brand consistency.

## What Changes

- Create a custom Jekyll theme with stockcast.com.br visual identity (NOT landing page structure)
- Use correct brand color: blue #00639C (NOT green)
- Implement blog index with post list (title, date, excerpt)
- Implement post layout (title, date, author "StockCast", content)
- Add simple header with StockCast logo linking to stockcast.com.br
- Add navigation links (Blog, About)
- Apply same colors, fonts, typography, card styles from stockcast.com.br
- Responsive design for mobile/desktop
- Apply same styling to About page and 404 page

## Capabilities

### New Capabilities
- `jekyll-theme-stockcast`: Custom Jekyll theme with stockcast.com.br visual identity

### Modified Capabilities
- None

## Impact

- New theme files (layouts, includes, assets)
- Modified `_config.yml` to use new theme
- Updated existing pages (index, about, 404)
- Affected: blog appearance, navigation, all pages
