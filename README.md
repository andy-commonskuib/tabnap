# tabnap

MV3 extension playground: page reading-time estimator

Small but I use it weekly.

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## What it does

- No remote calls, everything stays local
- Per-tab time persisted to chrome.storage
- Popup shows today's total focus time
- Manifest V3, service worker based

## Project structure

```text
├── .github/
│   └── ISSUE_TEMPLATE/
│       └── bug_report.md
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
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
