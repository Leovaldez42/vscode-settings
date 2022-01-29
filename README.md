# VS Code Settings

# Font

* [Cascadia Code](https://github.com/microsoft/cascadia-code/releases)

# Extensions

See my full list of extensions [here](https://gist.github.com/Leovaldez42/5dd20d3df28095efe77a704dbce21543).

## Themes/Color

* Current theme:
  * [Monokai](https://marketplace.visualstudio.com/items?itemName=gerane.Theme-Monokai)
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
  * Matching parenthesis and curly brackets to with colors

## Workflow
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  * For writing better comments
* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 

## IntelliSense/AutoComplete

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * Provides CSS class name completion for the HTML class attribute based on the definitions found in your workspace or external files referenced through the link element
* [React snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
  * Complete React snippets
* [Vue snippets](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)
  * Complete Vue snippets

## Style/Formatting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS

## Useful/Extra

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  * Display inline the size of the required/imported package
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code

# Settings

```json
{
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontFamily": "Cascadia Code",
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "blockman.n01LineHeight": 0,
    "workbench.colorCustomizations": {
        "editor.lineHighlightBackground": "#1073cf2d",
        "editor.lineHighlightBorder": "#9fced11f"
    },
    "editor.wordWrap": "on",
    "editor.guides.indentation": true,
    "editor.guides.bracketPairs": false,
    "editor.bracketPairColorization.enabled": true,
    "workbench.colorTheme": "Monokai",
}
```

# Keybindings

```json
[
    {
        "key": "cmd+t cmd+s",
        "command": "workbench.action.toggleStatusbarVisibility"
    },
    {
        "key": "cmd+t cmd+a",
        "command": "workbench.action.toggleActivityBarVisibility"
    },
    
    { "key": "cmd+1","command": "workbench.action.openEditorAtIndex1" },
    { "key": "cmd+2","command": "workbench.action.openEditorAtIndex2" },
    { "key": "cmd+3","command": "workbench.action.openEditorAtIndex3" },
    { "key": "cmd+4","command": "workbench.action.openEditorAtIndex4" },
    { "key": "cmd+5","command": "workbench.action.openEditorAtIndex5" },
    { "key": "cmd+6","command": "workbench.action.openEditorAtIndex6" },
    { "key": "cmd+7","command": "workbench.action.openEditorAtIndex7" },
    { "key": "cmd+8","command": "workbench.action.openEditorAtIndex8" },
    { "key": "cmd+9","command": "workbench.action.openEditorAtIndex9" }
]
```