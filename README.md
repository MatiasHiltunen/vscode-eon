# EON Support for VS Code

This extension provides syntax highlighting for the [EON](https://github.com/eon-config/eon) configuration language in Visual Studio Code.

## Features

*   Syntax highlighting for `.eon` files.
*   Comment toggling (`//`).
*   Bracket matching for `{}`, `[]`, and `()`.
*   Auto-closing pairs for brackets and quotes.

![EON Syntax Highlighting Screenshot](https://raw.githubusercontent.com/eon-config/eon/main/assets/screenshot.png) 
(Note: You will need to provide a real screenshot here)

## Installation

You can install this extension from the Visual Studio Code Marketplace (once it's published).

For local development:

1.  Clone this repository.
2.  Install `vsce` (the Visual Studio Code Extension manager): `npm install -g @vscode/vsce`.
3.  Package the extension: `vsce package`.
4.  Install the generated `.vsix` file in VS Code via `Extensions: Install from VSIX...` in the command palette.

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

## License

MIT

