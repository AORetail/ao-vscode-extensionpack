# Vue VSCode Extension Pack

A collection of extensions for VS Code.

## Extensions Included

### Linting & Formatting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) JS Linting
  * [eslint-config-ao](https://www.npmjs.com/package/eslint-config-ao)
  * Suggested settings
    ```json
    {
        "eslint.enable": true,
    }
    ```
* [stylelint](https://marketplace.visualstudio.com/items?itemName=shinnn.stylelint)
  * [stylelint-preset-ao](https://www.npmjs.com/package/stylelint-preset-ao)
  * Suggested settings
    ```json
    {
        "stylelint.enable": true,
        "css.validate": false,
        "scss.validate": false
    }
    ```
* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.editorconfig) - DESC
  * [Example EditorConfig](https://github.com/AORetail/ao-vscode-extensionpack/.editorconfig)
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Suggested settings
    ```json
    {
        "prettier.useTabs": true,
        "prettier.semi": true,
        "prettier.singleQuote": true,
        "prettier.eslintIntegration": true,
        "prettier.stylelintIntegration": true
    }
    ```

### VCS

* [Hg](https://marketplace.visualstudio.com/items?itemName=mrcrowl.hg) - Mecurial

### Utils

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) - Displays an estimated size of import.
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense) - Visual Studio Code plugin that autocompletes npm modules in import statements.
  * Suggested Settings
    ```json
    {
        "npm-intellisense.importES6": true,
        "npm-intellisense.importQuotes": "'",
        "npm-intellisense.importLinebreak": ";\r\n",
        "npm-intellisense.importDeclarationType": "const",
        "npm-intellisense.scanDevDependencies": true
    }
    ```
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense) - Visual Studio Code plugin that autocompletes filenames

## Relevant Links

* [Github](ttps://github.com/AORetail/ao-vscode-extensionpack)
* [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=aoretail.ao-vscode-extensionpack)