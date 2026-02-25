## ADDED Requirements

### Requirement: Header displays News terminology
The site SHALL use "News" terminology in navigation instead of "Blog".

#### Scenario: Navigation shows News link
- **WHEN** page renders
- **THEN** header navigation shows "News" linking to homepage

### Requirement: Homepage displays as news front page
The homepage SHALL present posts in a news-style layout.

#### Scenario: Page title reflects news
- **WHEN** homepage renders
- **THEN** page title or heading says "News" or "Últimas Notícias"

#### Scenario: Post cards emphasize date
- **WHEN** homepage renders
- **THEN** post cards display date prominently

#### Scenario: Post cards feel like news items
- **WHEN** homepage renders
- **THEN** post cards have clear title, date, and excerpt with professional spacing

### Requirement: Post list is responsive
The homepage SHALL display post grid responsively across devices.

#### Scenario: Posts stack on mobile
- **WHEN** homepage renders on mobile (< 768px)
- **THEN** posts display in single column

#### Scenario: Posts grid on desktop
- **WHEN** homepage renders on desktop
- **THEN** posts display with appropriate spacing in grid or list format
