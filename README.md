# open command prompt and type: "color 2" then enter, same for backend

- command prompt frontend: color 2 & backend: 6

## client site customize color

1. Create folder: .vscode
2. Create file inside ".vscode": settings.json
3. copy to past code bellow:

===============START==================
{
"workbench.colorCustomizations": {
// left side bar
"activityBar.background": "#279f09dc",
"activityBar.foreground": "#000",
"activityBar.activeBackground": "#ffff",
"activityBar.inactiveForeground": "#ff0000",
// bottom side bar
"statusBar.background": "#279f09dc",
"statusBar.foreground": "#ff0000",
// top side bar
"titleBar.activeBackground": "#279f09dc",
"titleBar.activeForeground": "#ff0000"
}
}
==================END===================

## backend customize color

===============START==================
{
"workbench.colorCustomizations": {
// left side bar
"activityBar.background": "#c51717",
"activityBar.foreground": "#000",
"activityBar.activeBackground": "#ffff",
"activityBar.inactiveForeground": "#2be51a",
// bottom side bar
"statusBar.background": "#c51717",
"statusBar.foreground": "#2be51a",
// top side bar
"titleBar.activeBackground": "#c51717",
"titleBar.activeForeground": "#2be51a"
}
}
=================END====================
