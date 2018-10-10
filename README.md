# SMTC Extension Pack

[![License][license-badge]][license-url]

> An opinionated extension pack for VS Code.

This extension pack provides the following extensions:

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) - Automatically add HTML/XML close tag.

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) - Auto rename paired HTML/XML tag.

- [Cobalt2 Theme Official](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2) - Official theme by Wes Bos.

- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula) - Official Dracula Theme. A dark theme for many editors, shells, and more.

- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=editorconfig.editorconfig) - EditorConfig Support for Visual Studio Code.

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint JavaScript into VS Code.

- [language-stylus](https://marketplace.visualstudio.com/items?itemName=sysoev.language-stylus) - Stylus language support.

- [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl) - A VS Code theme for the night owls out there.

- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames.

- [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode) - Polaroid for your code.

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - VS Code plugin for prettier/prettier.

- [VS Live Share](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare) - Real-time collaborative development from the comfort of your favorite tools.

- [VSCode Essentials Snippets](https://marketplace.visualstudio.com/items?itemName=robertoachar.vscode-essentials-snippets) - A collection of essentials snippets for Visual Studio Code.

- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - Icons for Visual Studio Code.

# Development

- Clone the repo

```bash
$ git clone https://github.com/robertoachar/vscode-extension-pack.git
```

- Install vsce

```bash
$ npm install -g vsce
```

- Build the extension file

```bash
$ vsce package
```

- Install the extension from a package file (.vsix)

1. Launch Visual Studio Code
2. Choose **Extensions** from menu
3. Click **More** > **Install from VSIX...**
4. Select the file `vscode-extension-pack-x.x.x.vsix`
5. Click **Reload Now** to reload the Code

# Publishing

- Create a publisher

```bash
$ vsce create-publisher <publisher-name>
```

- Login

```bash
$ vsce login <publisher-name>
```

- Publish

```bash
$ vsce publish
```

# Author

[Roberto Achar](https://twitter.com/robertoachar)

# License

[MIT](https://github.com/robertoachar/vscode-extension-pack/blob/master/LICENSE)

[license-badge]: https://img.shields.io/github/license/robertoachar/vscode-extension-pack.svg
[license-url]: https://opensource.org/licenses/MIT
