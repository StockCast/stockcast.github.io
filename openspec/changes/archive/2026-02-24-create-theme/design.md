## Context

The StockCast blog currently uses the default Jekyll minima theme. The main site (stockcast.com.br) has a distinct visual identity with blue branding (#00639C), card-based layouts, and specific typography. We need a custom Jekyll theme that provides brand consistency when users navigate from the main site to the news section.

Current state:
- Jekyll site with minima theme
- Blog structure (index shows posts, individual post pages)
- No custom styling matching stockcast.com.br

Constraints:
- Must work with existing Jekyll infrastructure
- Should be responsive (mobile + desktop)
- Keep theme files in repository (not gem-based)
- Maintain existing blog functionality

## Goals / Non-Goals

**Goals:**
- Create custom Jekyll theme matching stockcast.com.br visual identity
- Use correct brand color: #00639C (blue, NOT green)
- Implement blog index with post list (title, date, excerpt)
- Implement post layout with title, date, author
- Add simple header with StockCast logo → stockcast.com.br
- Add navigation (Blog, About links)
- Apply same colors, fonts, typography, card styles
- Ensure responsive design
- Maintain all existing blog functionality

**Non-Goals:**
- Create landing page sections (hero, features, audience, FAQ) - this is a BLOG, not landing page
- Add green color anywhere (brand is blue)
- Implement dark mode variant
- Add interactive charts or complex JavaScript
- Migrate to different static site generator

## Decisions

1. **Theme packaging**: Copy theme files into _layouts, _includes, assets/css
   - Alternative: Gem-based theme
   - Rationale: Simpler for single-site deployment, easier to customize

2. **CSS approach**: Plain CSS with CSS variables for theming
   - Alternative: Tailwind CSS, SCSS
   - Rationale: Simpler setup, no build step required, matches stockcast.com.br inline styles

3. **Navigation**: Simple header with logo + nav links
   - Rationale: Keep simple - users navigate FROM main site TO news

4. **Color palette** (from stockcast.com.br):
   - Primary: #00639C (blue)
   - Background: #CEE5FF (light blue)
   - Container: #FCFCFF (off-white)
   - Text: #1A1C1E
   - Border: #DEE3EB
   - Font: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial

## Risks / Trade-offs

- [Risk] Theme might not perfectly match stockcast.com.br over time → Mitigation: Create easily adjustable CSS variables
- [Risk] Existing blog posts may need layout adjustments → Mitigation: Test with sample posts, use flexible layout
- [Risk] Jekyll version compatibility → Mitigation: Use widely-supported CSS and vanilla JS
