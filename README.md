# Visual Studio Code - Custom Monokai Theme

Custom settings for Visual Studio Code using the popular **Monokai** theme based in the **Monokai Seti** for Atom.


![alt text](https://github.com/vtisnado/visual-studio-code-custom-settings/blob/master/visual-studio-code-custom-monokai.png)


___

First of all make sure you have installed the Monokai Theme, then open the settings.json file in **Code > Preferences > Settings** and look for the **workbench.colorCustomizations** and copy that to the **USER SETTINGS**.

You will see something like this:

```javascript
{
    "editor.fontSize": 14,
    "workbench.colorTheme": "Monokai",
    "workbench.iconTheme": "vs-seti",
    "window.zoomLevel": 0,
    "workbench.colorCustomizations": {}
}
```

Then you just need to copy the following values under **workbench.colorCustomizations**


```javascript
    "sideBar.background": "#15191B",
    "sideBar.foreground": "#CCCCCC",
    "sideBar.border": "#090B0D",
    "list.hoverBackground": "#31393A",
    "sideBarSectionHeader.background": "#090B0D",
    "badge.background": "#CC9933",
    "tab.inactiveBackground": "#2C3233",
    "list.activeSelectionBackground": "#519ABA",
    "list.inactiveSelectionBackground": "#519ABA",
    "button.background": "#519ABA",
    "editor.background": "#151718",
    "editor.selectionBackground": "#49483D",
    "editor.lineHighlightBackground": "#31393A",
    "editor.findMatchBackground": "#49483D",
    "editor.findMatchHighlightBackground": "#31393A",
    "statusBar.background": "#090B0D",
    "titleBar.activeBackground": "#090B0D",
    "activityBar.background": "#090B0D",
    "statusBar.foreground": "#519ABA",
    "editorGutter.background": "#1C1F20"
```

You will end with something like this:


```javascript
{
    "editor.fontSize": 14,
    "workbench.colorTheme": "Monokai",
    "workbench.iconTheme": "vs-seti",
    "window.zoomLevel": 0,
    "workbench.colorCustomizations": {
        "sideBar.background": "#15191B",
        "sideBar.foreground": "#CCCCCC",
        "sideBar.border": "#090B0D",
        "list.hoverBackground": "#31393A",
        "sideBarSectionHeader.background": "#090B0D",
        "badge.background": "#CC9933",
        "tab.inactiveBackground": "#2C3233",
        "list.activeSelectionBackground": "#519ABA",
        "list.inactiveSelectionBackground": "#519ABA",
        "button.background": "#519ABA",
        "editor.background": "#151718",
        "editor.selectionBackground": "#49483D",
        "editor.lineHighlightBackground": "#31393A",
        "editor.findMatchBackground": "#49483D",
        "editor.findMatchHighlightBackground": "#31393A",
        "statusBar.background": "#090B0D",
        "titleBar.activeBackground": "#090B0D",
        "activityBar.background": "#090B0D",
        "statusBar.foreground": "#519ABA",
        "editorGutter.background": "#1C1F20"
    }
}
```

One last thing...

Some extensions force the tab indentation to 2 spaces, that's the case of the **Dart extension**, but we can fix it adding the following snippet before the last bracket:

```javascript
"[dart]": {
	"editor.tabSize": 4,
	"editor.insertSpaces": false,
	"editor.detectIndentation": false
}
```


That's all. **Happy coding!**



