# VS Code to SublimeText flatland theme
HACK CSS file to makes VS Code more like SublimeText flatland theme

Warning
----------
This hack would cause VS Code display **UNSUPPORTED** warning on title bar, DO NOT install if you mind it.

Screen Shot
----------
![Screen Shot](https://raw.githubusercontent.com/gbabook/vscode_to_sublimetext-flatland/master/screen_shot.png)

Install
----------
- Search keyword `flatland` in VS Code extention market, install `Flatland Monokai` (Thành Trang) and `flatland icon theme` (gebilaoxiong).
- Copy `tab` foler and `workbench.main-mod.css` to `/Applications/Visual\ Studio\ Code.app/Contents/Resources/app/out/vs/workbench/electron-browser/` on OSX or `C:\Program Files (x86)\Microsoft VS Code\resources\app\out\vs\workbench\electron-browser` on Windows.
- Back up the orignal css file `workbench.main-mod.css` and rename `workbench.main-mod.css` to `workbench.main-mod.css`.
- Config VS Code Settings, mine for example below, then restart VS Code to take affect.
``` json
{
    "editor.fontSize": 16,
    "editor.fontFamily": "Monaco",
    "editor.lineHeight": 24,
    "editor.wordWrap": "on",
    "workbench.colorTheme": "Flatland Monokai",
    "editor.minimap.enabled": true,
    "explorer.openEditors.visible": 0,
    "explorer.autoReveal": false,
    "workbench.iconTheme": "flatland-icon-theme",
    "workbench.sideBar.location": "left",
    "workbench.activityBar.visible": false
}
```
