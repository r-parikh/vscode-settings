# VS Code Settings

# Font

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

# Extensions

See my full list of extensions [here](https://gist.github.com/r-parikh/bc8e491833cfb893f2af017b0a43bcb8)

## Themes/Color

* Current theme:
  * [Ayu Mirage](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)
  
## Workflow

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts
  
## IntelliSense/AutoComplete

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import/require statements
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)
  * Vue tooling

## Style/Formatting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files
  

# Settings
```json
{
    "workbench.startupEditor": "newUntitledFile",
    "workbench.colorTheme": "Ayu Mirage",
    "workbench.iconTheme": "ayu",
    "editor.fontLigatures": true,
    "terminal.integrated.fontSize": 14,
    "editor.fontFamily": "Anonymous Pro",
    "editor.fontSize": 14,
    "terminal.integrated.shell.osx": "/bin/zsh",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "editor.detectIndentation": true,
    "eslint.enable": true,
    "eslint.validate": [
        {
            "language": "vue",
            "autoFix": true
        },
        {
            "language": "html",
            "autoFix": true
        },
        {
            "language": "javascript",
            "autoFix": true
        }
    ],
    "liveshare.featureSet": "insiders",
    "[vue]": {
        "editor.defaultFormatter": "octref.vetur"
    },
    "workbench.colorCustomizations": {},
    "[scss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    }
}
```
