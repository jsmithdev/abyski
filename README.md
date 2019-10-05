# Abyski

## a turnt take on abyss & monokai 🦄

<img src="https://i.imgur.com/MfXP1JC.png">

*[Github repo here](https://github.com/jsmithdev/abyski)*

*[VS Code Marketplace here](https://marketplace.visualstudio.com/items?itemName=jamiesmiths.abyski)*

*compliments my linux repo manager [Reapo 🗃 ](https://github.com/jsmithdev/reapo)*

## What's in the repo

* This repo contains all of the files necessary for the color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/Abyski-color-theme.json` - the color theme definition file.

## Dev / Customizing

This has debug setup to easily customize:

* Press `F5` to open a new window with the extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Inspect TM Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

* Changes to the theme file are automatically applied to the Extension Development Host window (Ctrl+S)

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

---

Made with 💙 by [Jamie Smith](https://jsmith.dev)