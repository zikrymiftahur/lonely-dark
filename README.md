# Lonely Dark Themes

Inspired by One Dark Pro Themes

But this background is darker, and there is a slight color change

## Screenshots

![App Screenshot](https://cdn.jsdelivr.net/gh/zikrymiftahur/lonely-dark-vscode/screenshots/screenshot-1.png)

![App Screenshot](https://cdn.jsdelivr.net/gh/zikrymiftahur/lonely-dark-vscode/screenshots/screenshots-2.png)

### Tweaks & theming

If you want to play around with new colors, use the setting
`workbench.colorCustomizations` to customize the currently selected theme. For
example, you can add this snippet in your "settings.json" file:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#282c34",
  "activityBar.background": "#282c34",
  "sideBar.background": "#282c34",
  "tab.activeBorder": "#d19a66",
}
```

or use the setting `editor.tokenColorCustomizations`

```json
"editor.tokenColorCustomizations": {
  "[Lonely Dark]": {
    "textMateRules": [
      {
        "scope": ["entity.name.tag.html"],
        "settings": {
          "foreground": "#e06c75"
        }
      }
    ]
  }
}
```

## Feedback

If you have any feedback, please reach out to us at iki.miftahur@gmail.com
