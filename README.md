# linkstash-api

Learning project: clean Express API structure

Started as a weekend hack, grew on me.

## Installation

```bash
npm install
npm run dev
```

## Highlights

- Morgan logging and centralized error handler
- env-driven port, runs anywhere Node does
- In-memory store with optional JSON persistence
- REST endpoints: list / create / delete / search
- Request validation helpers, no framework magic

## How to use

```bash
curl -X POST localhost:3000/api/bookmarks \
  -H 'content-type: application/json' \
  -d '{"url": "https://example.com", "tags": ["reading"]}'
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── src/
│   ├── config.js
│   ├── index.js
│   └── store.js
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
└── package.json
```

## Development

```bash
npm install
```
