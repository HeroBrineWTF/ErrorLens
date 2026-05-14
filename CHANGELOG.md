# Changelog

All notable changes to ErrorLens will be documented in this file.

## [1.1] - 2026-05-13

### Added
- Sample errors in the popup for quick first-run testing
- Result actions for copying summaries, prefilling custom rules, searching docs, and opening DevTools tips
- Expanded built-in error coverage for auth, CORS, fetch, JSON parsing, hydration, chunk loading, and common backend/database errors
- In-extension privacy policy page linked from the popup footer
- Public privacy policy document for store submission and GitHub
- Publish-ready extension packaging zip

### Changed
- Improved the copy action to generate a cleaner summary format for tickets, docs, and chat
- Updated the extension icon and store-ready branding assets
- Clarified privacy wording around user-initiated external search actions

### Fixed
- Synced the result-panel copy button state with the main copy button
- Added a confirmation before sending current error text to external web search

## [1.0] - 2026-04-21

### Added
- Initial Chrome extension release
- Popup-based error analyzer for browser, HTTP, network, JavaScript, and app errors
- Plain-English explanations, likely causes, and user/developer next steps
- Context menu support for analyzing selected page text
- Custom rules for app-specific recurring errors
- Recent error history stored locally
- Chrome Web Store listing assets and submission materials
