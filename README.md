# SMTC Extension Pack

[![License][license-badge]][license-url]

> An opinionated extension pack for VS Code.

This extension pack provides the following extensions:

* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.editorconfig) - EditorConfig helps developers define and maintain consistent coding styles between different editors and IDEs.

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code.

* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - VS Code plugin that autocompletes filenames.

* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - VS Code package to format your JavaScript / TypeScript / CSS using Prettier.

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) - This extension provides a rich editing experience for Angular templates, both inline and external templates.

* [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint) - Integrates the tslint linter for the TypeScript language into VS Code.

* [Cobalt2 Theme Official](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2) - Cobalt2 Theme Official by Wes Bos.

* [vscode-icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons) - Bring icons to your VS Code.

* [Extension Manifest Editor](https://marketplace.visualstudio.com/items?itemName=ms-devlabs.extension-manifest-editor) - This extension lets you preview the details page for your extension from within VS Code.

* [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - A VS Code extension with rich support for the Python language.

* [Docker](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker) - Docker Support for VS Code.

* [VSCode Essentials Snippets](https://marketplace.visualstudio.com/items?itemName=robertoachar.vscode-essentials-snippets) - A collection of essentials snippets for VS Code.

# Development

* Clone the repo

```bash
$ git clone https://github.com/robertoachar/vscode-extension-pack.git
```

* Install vsce

```bash
$ npm install -g vsce
```

* Build the extension file

```bash
$ vsce package
```

* Install the extension from a package file (.vsix)

1. Launch Visual Studio Code
2. Choose **Extensions** from menu
3. Click **More** > **Install from VSIX...**
4. Select the file `vscode-extension-pack-x.x.x.vsix`
5. Click **Reload Now** to reload the Code

# Publishing

* Create a publisher

```bash
$ vsce create-publisher <publisher-name>
```

* Login

```bash
$ vsce login <publisher-name>
```

* Publish

```bash
$ vsce publish
```

# Author

[Roberto Achar](https://twitter.com/robertoachar)

# License

[MIT](https://github.com/robertoachar/vscode-extension-pack/blob/master/LICENSE)

[license-badge]: https://img.shields.io/github/license/robertoachar/vscode-extension-pack.svg
[license-url]: https://opensource.org/licenses/MIT
