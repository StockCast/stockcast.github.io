## Context

The StockCast News Jekyll blog currently has no README. The project uses:
- Jekyll 4.4.1
- Custom theme (not minima - custom CSS and layouts)
- jekyll-feed plugin
- Bundler for dependency management

Current project structure:
- `_layouts/` - custom layouts (default, home, post)
- `_includes/` - header, footer
- `assets/css/style.css` - custom theme styles
- `_posts/` - blog posts in Markdown
- `_config.yml` - Jekyll configuration

## Goals / Non-Goals

**Goals:**
- Create comprehensive README.md
- Document prerequisites (Ruby, Bundler)
- Document installation (bundle install)
- Document local development (bundle exec jekyll serve)
- Document production build (bundle exec jekyll build)
- Document deployment to GitHub Pages
- Document how to add new blog posts

**Non-Goals:**
- Add complex CI/CD documentation
- Document OpenSpec workflow (that's in .opencode/)
- Add contribution guidelines
- Add license file

## Decisions

1. **README location**: Root directory (README.md)
   - Rationale: Standard location, automatically shown on GitHub

2. **Format**: Markdown with clear sections
   - Rationale: Easy to read, Jekyll renders nicely

3. **Deployment**: GitHub Pages
   - Rationale: Simple, free, already configured in _config.yml

## Risks / Trade-offs

- [Risk] Instructions may become outdated → Mitigation: Keep instructions minimal, rely on standard Jekyll commands
- [Risk] Users may miss important setup steps → Mitigation: Include prerequisites section clearly

## Migration Plan

1. Create README.md with build instructions
2. Test instructions by following them fresh
3. Deploy to GitHub Pages
