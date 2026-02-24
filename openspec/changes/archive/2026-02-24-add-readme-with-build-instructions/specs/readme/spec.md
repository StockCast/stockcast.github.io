## ADDED Requirements

### Requirement: README contains prerequisites
The README SHALL document all prerequisites needed to build and run the project.

#### Scenario: Prerequisites section exists
- **WHEN** user opens README.md
- **THEN** a Prerequisites section lists required software (Ruby, Bundler)

### Requirement: README contains installation instructions
The README SHALL provide commands to install dependencies.

#### Scenario: Installation commands work
- **WHEN** user runs `bundle install`
- **THEN** all dependencies install without errors

### Requirement: README contains local development instructions
The README SHALL explain how to run the site locally for development.

#### Scenario: Local server starts
- **WHEN** user runs `bundle exec jekyll serve`
- **THEN** development server starts and site is accessible

### Requirement: README contains build instructions
The README SHALL explain how to build the site for production.

#### Scenario: Production build succeeds
- **WHEN** user runs `bundle exec jekyll build`
- **THEN** static files are generated in _site/ directory

### Requirement: README contains deployment instructions
The README SHALL document how to deploy to GitHub Pages.

#### Scenario: Deployment steps are clear
- **WHEN** user follows deployment instructions
- **THEN** site deploys to GitHub Pages successfully

### Requirement: README documents how to add posts
The README SHALL explain how to create new blog posts.

#### Scenario: New post format is documented
- **WHEN** user wants to add a new post
- **THEN** README explains the required file naming convention and front matter

### Requirement: README documents project structure
The README SHALL provide an overview of the project's directory structure.

#### Scenario: Structure section exists
- **WHEN** user opens README.md
- **THEN** a Project Structure section describes key directories and files
