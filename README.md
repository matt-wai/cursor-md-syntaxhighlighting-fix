# 🐳 Markdown Syntax Enhanced

Enhanced markdown syntax highlighting for Cursor/VS Code with full TextMate grammar support.

## Why?

Cursor's default markdown syntax highlighting only shows a subset of the supposed syntax coloring. This extension overrides it with a comprehensive TextMate grammar that supports all markdown features.

## Features

- **Headers** - ATX (`#`) and Setext (underline) style
- **Emphasis** - Bold, italic, bold+italic
- **Strikethrough** - `~~text~~`
- **Code** - Inline \`code\` and fenced code blocks with language-specific highlighting
- **Links & Images** - Inline, reference, and autolinks
- **Blockquotes** - Nested support
- **Lists** - Ordered, unordered, and task lists
- **Tables** - GFM tables
- **Footnotes** - Definition and reference
- **Math** - Inline `$math$`
- **HTML** - Inline HTML tags
- **Emoji** - `:emoji:` shortcodes
- **Extended syntax** - Highlight `==text==`, subscript `~text~`, superscript `^text^`

### Embedded Language Support

Fenced code blocks with language identifiers get proper syntax highlighting:

- JavaScript/TypeScript/JSX/TSX
- Python, Ruby, Go, Rust
- HTML, CSS, SCSS
- JSON, YAML, TOML, XML
- SQL, GraphQL
- Shell/Bash
- C, C++, Java, Kotlin, Swift
- PHP, Lua, R
- Dockerfile, Diff
- And more...

## Installation

### From VSIX

1. Download the latest `.vsix` from [Releases](https://github.com/matt-wai/cursor-md-syntaxhighlighting-fix/releases)
2. In Cursor/VS Code: `Cmd+Shift+P` → "Extensions: Install from VSIX..."
3. Select the downloaded file

### From Source

```bash
git clone https://github.com/matt-wai/cursor-md-syntaxhighlighting-fix
cd cursor-md-syntaxhighlighting-fix
npm install
npm run package
```

## License

MIT
