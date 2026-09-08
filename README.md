# flockr

Small Go tool: declutter ~/Downloads in one command

## How to use

```bash
./bin/flockr ~/Downloads --dry-run
./bin/flockr ~/Downloads
```

## Getting started

```bash
go build -o bin/ ./...
```

## Features

- Groups files into folders by extension
- Skips hidden files and folders by default
- Single static binary, no runtime deps
- Dry-run prints the plan before moving anything

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```
