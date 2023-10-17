## client site customize color

- create folder **.vscode**
- create file inside ".vscode" **settings.json**
- copy the codes below

```http
{
    "workbench.colorCustomizations": {
        // top side bar
        "titleBar.activeBackground": "#279f09dc",
        "titleBar.activeForeground": "#ff0000",
        // left side bar
        "activityBar.background": "#279f09dc",
        "activityBar.foreground": "#000",
        "activityBar.activeBackground": "#ffff",
        "activityBar.inactiveForeground": "#ff0000",
        // bottom side bar
        "statusBar.background": "#279f09dc",
        "statusBar.foreground": "#ff0000"
    }
}
```

## backend customize color

```http
{
    "workbench.colorCustomizations": {
        // top side bar
        "titleBar.activeBackground": "#c51717",
        "titleBar.activeForeground": "#2be51a",
        // left side bar
        "activityBar.background": "#c51717",
        "activityBar.foreground": "#000",
        "activityBar.activeBackground": "#ffff",
        "activityBar.inactiveForeground": "#2be51a",
        // bottom side bar
        "statusBar.background": "#c51717",
        "statusBar.foreground": "#2be51a"

    }
}
```

### command prompt

- command prompt frontend **color 2** and backend **color 6**
- open command prompt and type `color 2` then enter, same for backend `color 6`
- type: `color -h` (see all cmd color)
