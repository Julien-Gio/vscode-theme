* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/JulienGio-color-theme.json` - the color theme definition file.


## Install this color theme to VSCode

Copy this folder into the `<user home>/.vscode/extensions` or `%localappdata%\Programs\Microsoft VS Code\resources\app\extensions` folder and restart Code.


## Editing theme

* Press `F5` to open a new window with your extension loaded.
* Open the color theme picker with  the `File > Preferences > Theme > Color Theme` menu item, or use the `Preferences: Color Theme command (Ctrl+K Ctrl+T)` and pick your theme
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.
