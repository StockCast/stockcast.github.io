## ADDED Requirements

### Requirement: Post displays category tag
The post SHALL display an optional category tag in uppercase with letter spacing.

#### Scenario: Post has category
- **WHEN** post has categories in front matter
- **THEN** category tag displays above title in uppercase with 2px letter-spacing

#### Scenario: Post has no category
- **WHEN** post has no categories in front matter
- **THEN** no category tag displays (graceful fallback)

### Requirement: Post title has editorial hierarchy
The post SHALL display title with dramatic sizing appropriate for news.

#### Scenario: Title displays large on desktop
- **WHEN** post renders on desktop viewport
- **THEN** title uses 48px font size, bold weight

#### Scenario: Title displays appropriately on mobile
- **WHEN** post renders on mobile viewport (< 768px)
- **THEN** title uses 32px font size

### Requirement: Post displays enhanced byline
The post SHALL display byline with author, date, and read time.

#### Scenario: Byline shows all elements
- **WHEN** post renders
- **THEN** byline displays: "By AUTHOR · Date · X min read"

#### Scenario: Read time is calculated
- **WHEN** post renders
- **THEN** read time is estimated at ~200 words per minute from content

### Requirement: Post content is reading-optimized
The post SHALL use typography optimized for comfortable long-form reading.

#### Scenario: Content width is narrow
- **WHEN** post renders on desktop
- **THEN** content column is maximum 680px wide, centered

#### Scenario: Body text is larger
- **WHEN** post renders
- **THEN** body text uses 18px font size

#### Scenario: Line height is increased
- **WHEN** post renders
- **THEN** body text uses line-height of 1.8

#### Scenario: Paragraphs have ample spacing
- **WHEN** post renders
- **THEN** paragraphs have 24px bottom margin

### Requirement: Pull quotes are styled
The post SHALL style blockquotes as prominent pull quotes.

#### Scenario: Blockquote renders as pull quote
- **WHEN** post contains blockquote
- **THEN** blockquote has 4px left border in primary color (#00639C), larger font, italic style

### Requirement: Subtitles/dek are supported
The post SHALL display optional subtitle below the main title.

#### Scenario: Post has subtitle
- **WHEN** post has subtitle in front matter
- **THEN** subtitle displays below title in slightly smaller size

### Requirement: Brand colors are maintained
The post SHALL use StockCast brand colors for headings and accents.

#### Scenario: Headings use brand color
- **WHEN** post renders
- **THEN** h1, h2, h3 use #00639C (primary blue)

#### Scenario: Links use brand color
- **WHEN** post renders
- **THEN** links use #00639C with underline on hover
