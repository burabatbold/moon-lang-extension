# Moon Language Extension for VS Code

This extension provides syntax highlighting and language support for the Moon programming language.

## Features

- Syntax highlighting for Moon language files
- Bracket matching and auto-closing
- Auto-indentation
- Comment support
- Language configuration for Moon files

## Supported Syntax Elements

- Keywords: `хэрэв`, `бол`, `буц`, `давтах`, `зарла`, `функц`, `extern`, `үндсэн`
- Types: `тоо64`, `тоо`, `хоосон`, `мөр`
- Operators: `+`, `-`, `*`, `/`, `==`, `<=`, `>=`, `<`, `>`, `=`
- Comments: Single-line comments with `//`
- Strings: Double-quoted strings with escape sequences

## Requirements

- VS Code version 1.100.0 or higher

## Installation

1. Download the `.vsix` file from the releases page
2. Open VS Code
3. Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac) to open the command palette
4. Type "Install from VSIX" and select the downloaded file

## Usage

1. Create a new file with the `.mn` extension
2. Start writing Moon language code
3. Enjoy syntax highlighting and language features

## Example Code

```mn
// Test file for Moon Language

функц үндсэн() -> тоо {
    зарла n: тоо64 = 10;
    хэвлэ(n);
    буц 0;
}
```

## Language Features

- Function declarations with return types
- Variable declarations with type annotations
- Control flow statements (if, loops)
- External function declarations
- Basic arithmetic operations
- String handling

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
