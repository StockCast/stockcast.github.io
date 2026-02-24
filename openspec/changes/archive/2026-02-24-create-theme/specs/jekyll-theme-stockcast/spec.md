## ADDED Requirements

### Requirement: Theme provides stockcast.com.br visual identity
The theme SHALL implement visual styling that matches stockcast.com.br, including blue color scheme (#00639C), typography, and layout patterns.

#### Scenario: Theme loads with correct colors
- **WHEN** page loads with StockCast theme
- **THEN** primary color is #00639C (blue)

#### Scenario: Theme provides consistent fonts
- **WHEN** page loads with StockCast theme
- **THEN** headings use font family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial

### Requirement: Blog index displays post list
The theme SHALL show a list of blog posts with title, date, and excerpt.

#### Scenario: Blog index shows posts
- **WHEN** user visits blog index (homepage)
- **THEN** list of posts displays with title, date, excerpt

#### Scenario: Post list uses card styling
- **WHEN** posts are rendered in list
- **THEN** each post appears in a card with white background, rounded corners, subtle border

### Requirement: Individual post layout
The theme SHALL display individual blog posts with title, date, author, and content.

#### Scenario: Post displays title and date
- **WHEN** user views a blog post
- **THEN** post shows title and date prominently

#### Scenario: Post shows author
- **WHEN** user views a blog post
- **THEN** author "StockCast" is displayed

#### Scenario: Post content renders correctly
- **WHEN** user views a blog post
- **THEN** post content displays with proper typography and spacing

### Requirement: Header with navigation
The theme SHALL include a header with StockCast logo linking to main site and navigation links.

#### Scenario: Header shows logo link
- **WHEN** page loads
- **THEN** header displays "StockCast" logo linking to https://stockcast.com.br

#### Scenario: Header shows navigation
- **WHEN** page loads
- **THEN** header shows navigation links (Blog, About)

### Requirement: About page styling
The theme SHALL apply stockcast.com.br visual identity to the About page.

#### Scenario: About page uses brand styling
- **WHEN** user visits About page
- **THEN** page uses same colors, fonts, and card styles as main site

### Requirement: 404 page styling
The theme SHALL apply stockcast.com.br visual identity to the 404 error page.

#### Scenario: 404 page uses brand styling
- **WHEN** user visits 404 page
- **THEN** page uses same colors, fonts as main site

### Requirement: Responsive design
The theme SHALL work on both desktop and mobile devices.

#### Scenario: Layout adapts to mobile
- **WHEN** page is viewed on mobile viewport (< 768px)
- **THEN** layout adjusts to single column

#### Scenario: Navigation works on mobile
- **WHEN** page is viewed on mobile
- **THEN** navigation is accessible and usable
