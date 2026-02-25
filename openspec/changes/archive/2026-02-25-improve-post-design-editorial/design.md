## Context

The StockCast News site currently uses a generic blog layout that doesn't convey professionalism. The posts span full width (900px), use small typography (16px), and lack the visual hierarchy expected from a news publication.

Current issues:
- Post content stretches to full 900px container (too wide for reading)
- Body text is 16px with line-height 1.6 (not optimized for reading)
- No category tags or byline enhancements
- Header says "Blog" not "News"
- No pull quote styling

## Goals / Non-Goals

**Goals:**
- Create editorial-style post layout matching news publication standards
- Implement reading-optimized typography (18-20px body, 680px max width, 1.8 line-height)
- Add category tags, enhanced bylines with read time
- Add pull quote styling
- Update main page to feel like news front page
- Maintain brand colors (#00639C)

**Non-Goals:**
- Add dark mode
- Add comments system
- Add social sharing buttons
- Implement complex animations
- Add subscription/email capture

## Decisions

1. **Content width**: 680px centered for posts
   - Rationale: 60-75 characters per line is optimal for reading speed/comprehension
   - Industry standard: NYT, Medium, Substack use 600-700px

2. **Typography scale**:
   - H1: 48px (desktop), 32px (mobile) - dramatic, attention-grabbing
   - Body: 18px - comfortable reading
   - Line-height: 1.8 - prevents eye strain
   - Paragraph spacing: 24px - visual breathing room

3. **Category tags**: Uppercase, letter-spacing 2px, small (12px)
   - Rationale: Standard editorial convention ( NYT, WSJ style)

4. **Pull quotes**: Left border 4px #00639C, larger font, italic
   - Rationale: Breaks up text, adds visual interest

5. **Main page terminology**: "News" instead of "Blog"
   - Rationale: Conveys professional publishing, not personal blogging

## Risks / Trade-Offs

- [Risk] Long titles may break layout → Mitigation: CSS text-wrap: balance where supported
- [Risk] Existing posts don't have categories → Mitigation: Make optional, fall back gracefully
- [Risk] Mobile reading experience → Mitigation: Responsive adjustments for smaller screens

## Migration Plan

1. Update CSS with new typography variables
2. Modify post.html layout for editorial structure
3. Update home.html for news-style presentation
4. Update header navigation
5. Test with existing posts
6. Deploy to production

No rollback needed - changes are additive and improve readability.
