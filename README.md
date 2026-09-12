# dirdust

Small Go tool: declutter ~/Downloads in one command

## Highlights

- Single static binary, no runtime deps
- Skips hidden files and folders by default
- Groups files into folders by extension
- Dry-run prints the plan before moving anything

## Usage

```bash
./bin/dirdust ~/Downloads --dry-run
./bin/dirdust ~/Downloads
```

## Installation

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── docs/
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## Development

```bash
go build ./...
go vet ./...
```

## License

MIT. Do whatever you want.
