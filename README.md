# NAAb TextMate Grammar

TextMate grammar for the [NAAb programming language](https://github.com/b-macker/NAAb) — syntax highlighting for `.naab` files.

## Scope

`source.naab`

## Features

- **Keywords**: control flow, declarations, functions, structures, imports, error handling
- **Polyglot blocks**: `<<python ... >>`, `<<rust ... >>`, etc. with language tag highlighting
- **Variable binding**: `<<python[x, y] ... >>` parameter highlighting
- **Strings**: single/double quoted with escape sequences and `${interpolation}`
- **Comments**: `//`, `#`, and `/* ... */`
- **Operators**: pipeline `|>`, arrow `=>`, range `..`, comparison, logical, arithmetic
- **Standard library**: module name highlighting (`array.push()`, `json.parse()`, etc.)
- **Numbers**: integers and floats

## Usage

This grammar is used by:
- [vscode-naab](https://github.com/b-macker/vscode-naab) — VS Code extension
- [GitHub Linguist](https://github.com/github-linguist/linguist) — GitHub syntax highlighting (pending)

## License

MIT
