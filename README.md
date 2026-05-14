# ErrorLens

ErrorLens is a Chrome extension that translates technical errors into plain English.

It helps users and developers understand browser, network, HTTP, JavaScript, and app-related errors faster by showing:

- what the error means
- likely causes
- user-facing next steps
- developer-focused troubleshooting guidance

## Features

- Analyze pasted errors, stack traces, and console output
- Explain selected page text through the context menu
- Show category, source, match type, and confidence
- Provide separate guidance for users and developers
- Save custom rules for recurring app-specific errors
- Keep recent error history locally in the browser
- Copy a clean summary for tickets, docs, or chat
- Open quick follow-up actions like docs search and DevTools tips

## Example use cases

- Explaining browser errors like `ERR_NAME_NOT_RESOLVED`
- Understanding API failures like `HTTP 500 Internal Server Error`
- Interpreting auth and access issues such as `401`, `403`, or token errors
- Breaking down JavaScript runtime errors like `TypeError: Cannot read properties of undefined`
- Catching framework and backend issues such as hydration failures, CORS errors, or database connection problems

## Local development

1. Open Chrome and go to `chrome://extensions`
2. Enable `Developer mode`
3. Click `Load unpacked`
4. Select this project folder

The extension popup is defined by:

- `popup.html`
- `popup.css`
- `popup.js`

The built-in error database lives in:

- `error-database.js`

The context menu and background behavior live in:

- `background.js`

## Publish build

A publish-ready package can be created from the files in `publish-build`.

This repo also includes a packaged archive:

- `ErrorLens Publish Ready.zip`

## Privacy

ErrorLens stores recent history, custom rules, and preferences locally using Chrome extension storage.

The extension also includes:

- `PRIVACY_POLICY.md`
- `privacy.html`

If a user intentionally chooses an external action like web search, the current error text may be included in the destination search query.

## Store assets

Store listing source files and exports are in:

- `store-assets/`

This includes screenshots, promo tiles, and the extension icon source.

## Changelog

Release history is tracked in:

- `CHANGELOG.md`

## Roadmap

Short-term ideas are tracked in:

- `V1_1_ROADMAP.md`

## License

No license has been added yet.
