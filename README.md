# focusfolio

Chrome extension that tracks reading time per tab

## Features

- Manifest V3, service worker based
- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time

## Installation

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Examples

```bash
# click the toolbar icon to see today's reading time
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
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
