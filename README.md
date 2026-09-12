# focusfolio

Chrome extension that tracks reading time per tab

Side project, maintained when I have time.

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Usage

```bash
# click the toolbar icon to see today's reading time
```

## Features

- Popup shows today's total focus time
- Manifest V3, service worker based
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   └── usage.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```

## License

MIT licensed, see LICENSE.
