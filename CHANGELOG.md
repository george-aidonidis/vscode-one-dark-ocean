# Change Log

All notable changes to the "one-dark-ocean" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.2.0] - 2025-11-05

### Added
- **Semantic Highlighting Support**: Added `semanticHighlighting: true` and comprehensive `semanticTokenColors` configuration for enhanced syntax highlighting in TypeScript, JavaScript, and other supported languages
- **Bracket Pair Colorization**: Added 6-level bracket highlighting colors (`editorBracketHighlight.foreground1-6`) plus unexpected bracket warning color for better code readability
- **Git Decorations**: Added git status colors for file explorer (added, modified, deleted, untracked, ignored, conflicting, submodule)
- **Testing UI Colors**: Added complete testing UI color support (passed, failed, queued, skipped, error states, coverage indicators)
- **Notification System**: Added notification center and toast colors including info/warning/error icon colors
- **Base Colors**: Added missing base colors (disabledForeground, descriptionForeground, errorForeground, icon.foreground)
- **Input Validation**: Added input validation colors for error, warning, and info states with backgrounds and borders
- **Breadcrumb Navigation**: Added breadcrumb colors for file navigation (foreground, background, focus, active selection)
- **Test Samples**: Created test-samples directory with example files for TypeScript, JavaScript, Python, Java, HTML, CSS, JSON, Markdown, and Shell scripts

### Changed
- **Engine Requirement**: Updated minimum VS Code version from ^1.45.0 to ^1.85.0 to support modern theme features
- **Version**: Bumped version from 0.1.2 to 0.2.0

### Technical Details
- Added ~56 new workbench color properties
- Added 25 semantic token color mappings
- All new colors use existing theme palette for consistency
- Theme now supports modern VS Code features introduced since 2020

## [0.1.2] - Previous Release

- Initial release
