# dirdust-x

Go CLI that organizes a messy folder by file extension

## Examples

```bash
./bin/dirdust-x ~/Downloads --dry-run
./bin/dirdust-x ~/Downloads
```

## What it does

- Single static binary, no runtime deps
- Skips hidden files and folders by default
- Groups files into folders by extension
- Dry-run prints the plan before moving anything

## Installation

```bash
go build -o bin/ ./...
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
│   ├── faq.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## Acknowledgments

- README structure inspired by popular OSS templates
- Thanks to everyone opening issues with ideas
