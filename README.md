# vscode-in-rainbows-lp7-theme

vscode colors inspired by lp7 

![In Rainbows Color Palette](assets/in-rainbows-color-palette.png)

## Installation

1. open command palette: `cmd+shift+p` or `ctrl+shift+p`
2. search for `preferences: open user settings (json)`
3. paste json color themeing into ide user settings
4. tweak at your leisure
```json
{
  "workbench.colorCustomizations": {
    "editor.background": "#202020",
    "editorGutter.background": "#202020",
    "sideBar.background": "#2b2b2b",
    "activityBar.background": "#2b2b2b",
    "terminal.background": "#1d1d1d",
    "panel.background": "#1d1d1d",
    "titleBar.activeBackground": "#1d1d1d",
    "editorGroupHeader.tabsBackground": "#1d1d1d",
    "tab.inactiveBackground": "#34352f",
    "tab.activeBackground": "#272822",
    "list.activeSelectionBackground": "#75715e",
    "list.hoverBackground": "#3e3d32",
    "editorWidget.background": "#1e1f1c",
    "input.background": "#414339"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": ["variable", "variable.other", "variable.parameter", "property", "support.variable"],
        "settings": {
          "foreground": "#ec2427"
        }
      },
      {
        "scope": ["keyword", "keyword.control", "storage.type", "storage.modifier"],
        "settings": {
          "foreground": "#f36525"
        }
      },
      {
        "scope": ["constant.numeric", "constant.language.numeric"],
        "settings": {
          "foreground": "#edb41f"
        }
      },
      {
        "scope": ["entity.name.class", "entity.name.type.class", "support.class", "support.constant"],
        "settings": {
          "foreground": "#f7ee49"
        }
      },
      {
        "scope": ["entity.name.function", "support.function", "meta.method"],
        "settings": {
          "foreground": "#4686c5"
        }
      },
      {
        "scope": ["string", "string.quoted", "string.template"],
        "settings": {
          "foreground": "#45b64a"
        }
      },
      {
        "scope": ["keyword.operator", "support.type.builtin", "constant.language.special"],
        "settings": {
          "foreground": "#a4dde6"
        }
      }
    ]
  }
}
```

## in rainbows color palette
| color     | hex      | rgb               |
|-----------|----------|-------------------|
| yellow    | #F7EE49  | (247, 238, 073)   |
| blue      | #4686C6  | (070, 134, 198)   |
| orange    | #F36525  | (243, 101, 037)   |
| green     | #45B64A  | (069, 182, 074)   |
| gold      | #EDB41F  | (237, 180, 031)   |
| red       | #EC2427  | (236, 036, 039)   |
| light blue| #A4DDE6  | (164, 221, 230)   |

## credits
- sd & the gang `(lp10 wehn?)`