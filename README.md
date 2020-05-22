# TerminalConfig
windows terminal configuration of ubuntu


```json
{
  "$schema": "https://aka.ms/terminal-profiles-schema",
  "alwaysShowTabs": true,
  "copyOnSelect": false,
  "defaultProfile": "{2c4de342-38b7-51cf-b940-2309a097f518}",
  "initialCols": 140,
  "initialRows": 35,
  "keybindings": [
    {
      "command": "closePane",
      "keys": [
        "ctrl+shift+w"
      ]
    },
    {
      "command": "copy",
      "keys": [
        "ctrl+shift+c"
      ]
    },
    {
      "command": "duplicateTab",
      "keys": [
        "ctrl+shift+d"
      ]
    },
    {
      "command": "newTab",
      "keys": [
        "ctrl+shift+t"
      ]
    },
    {
      "command": "newTabProfile0",
      "keys": [
        "ctrl+shift+1"
      ]
    },
    {
      "command": "newTabProfile1",
      "keys": [
        "ctrl+shift+2"
      ]
    },
    {
      "command": "newTabProfile2",
      "keys": [
        "ctrl+shift+3"
      ]
    },
    {
      "command": "newTabProfile3",
      "keys": [
        "ctrl+shift+4"
      ]
    },
    {
      "command": "newTabProfile4",
      "keys": [
        "ctrl+shift+5"
      ]
    },
    {
      "command": "newTabProfile5",
      "keys": [
        "ctrl+shift+6"
      ]
    },
    {
      "command": "newTabProfile6",
      "keys": [
        "ctrl+shift+7"
      ]
    },
    {
      "command": "newTabProfile7",
      "keys": [
        "ctrl+shift+8"
      ]
    },
    {
      "command": "newTabProfile8",
      "keys": [
        "ctrl+shift+9"
      ]
    },
    {
      "command": "nextTab",
      "keys": [
        "ctrl+tab"
      ]
    },
    {
      "command": "openNewTabDropdown",
      "keys": [
        "ctrl+shift+space"
      ]
    },
    {
      "command": "openSettings",
      "keys": [
        "ctrl+,"
      ]
    },
    {
      "command": "paste",
      "keys": [
        "ctrl+shift+v"
      ]
    },
    {
      "command": "prevTab",
      "keys": [
        "ctrl+shift+tab"
      ]
    },
    {
      "command": "scrollDown",
      "keys": [
        "ctrl+shift+down"
      ]
    },
    {
      "command": "scrollDownPage",
      "keys": [
        "ctrl+shift+pgdn"
      ]
    },
    {
      "command": "scrollUp",
      "keys": [
        "ctrl+shift+up"
      ]
    },
    {
      "command": "scrollUpPage",
      "keys": [
        "ctrl+shift+pgup"
      ]
    },
    {
      "command": {
        "action": "switchToTab",
        "index": 0
      },
      "keys": "alt+1"
    },
    {
      "command": {
        "action": "switchToTab",
        "index": 1
      },
      "keys": "alt+2"
    },
    {
      "command": {
        "action": "switchToTab",
        "index": 2
      },
      "keys": "alt+3"
    },
    {
      "command": {
        "action": "switchToTab",
        "index": 3
      },
      "keys": "alt+4"
    },
    {
      "command": {
        "action": "switchToTab",
        "index": 4
      },
      "keys": "alt+5"
    },
    {
      "command": {
        "action": "switchToTab",
        "index": 5
      },
      "keys": "alt+6"
    }
  ],
  "requestedTheme": "system",
  "showTabsInTitlebar": true,
  "showTerminalTitleInTitlebar": true,
  "wordDelimiters": " ./\\()\"'-:,.;<>~!@#$%^&*|+=[]{}~?\u2502",
  "profiles": [
    {
      "acrylicOpacity": 0.75,
      "closeOnExit": true,
      "colorScheme": "Campbell",
      "commandline": "wsl.exe -d Ubuntu",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Noto Mono for Powerline",
      "fontSize": 11,
      "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{9acb9455-ca41-5af7-950f-6bca1bc9722f}.png",
      "name": "Ubuntu",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "%USERPROFILE%",
      "useAcrylic": false
    },
    {
      "acrylicOpacity": 0.5,
      "background": "#012456",
      "closeOnExit": true,
      "colorScheme": "Campbell",
      "commandline": "powershell.exe",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Noto Mono for Powerline",
      "fontSize": 10,
      "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{61c54bbd-c2c6-5271-96e7-009a87ff44bf}.png",
      "name": "Windows PowerShell",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "%USERPROFILE%",
      "useAcrylic": false
    },
    {
      "acrylicOpacity": 0.75,
      "closeOnExit": true,
      "colorScheme": "Campbell",
      "commandline": "cmd.exe",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Consolas",
      "fontSize": 10,
      "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{0caa0dad-35be-5f56-a8ff-afceeeaa6101}.png",
      "name": "cmd",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "%USERPROFILE%",
      "useAcrylic": true
    },
    {
      "acrylicOpacity": 0.59999999999999998,
      "closeOnExit": false,
      "colorScheme": "Vintage",
      "commandline": "Azure",
      "connectionType": "{d9fcfdfa-a479-412c-83b7-c5640e61cd62}",
      "cursorColor": "#FFFFFF",
      "cursorShape": "bar",
      "fontFace": "Consolas",
      "fontSize": 10,
      "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
      "historySize": 9001,
      "icon": "ms-appx:///ProfileIcons/{b453ae62-4e3d-5e58-b989-0a998ec441b8}.png",
      "name": "Azure Cloud Shell",
      "padding": "0, 0, 0, 0",
      "snapOnInput": true,
      "startingDirectory": "%USERPROFILE%",
      "useAcrylic": true
    }
  ],
  "schemes": [
    {
      "background": "#0C0C0C",
      "black": "#0C0C0C",
      "blue": "#0037DA",
      "brightBlack": "#767676",
      "brightBlue": "#3B78FF",
      "brightCyan": "#61D6D6",
      "brightGreen": "#16C60C",
      "brightPurple": "#B4009E",
      "brightRed": "#E74856",
      "brightWhite": "#F2F2F2",
      "brightYellow": "#F9F1A5",
      "cyan": "#3A96DD",
      "foreground": "#CCCCCC",
      "green": "#13A10E",
      "name": "Campbell",
      "purple": "#881798",
      "red": "#C50F1F",
      "white": "#CCCCCC",
      "yellow": "#C19C00"
    },
    {
      "background": "#000000",
      "black": "#000000",
      "blue": "#000080",
      "brightBlack": "#808080",
      "brightBlue": "#0000FF",
      "brightCyan": "#00FFFF",
      "brightGreen": "#00FF00",
      "brightPurple": "#FF00FF",
      "brightRed": "#FF0000",
      "brightWhite": "#FFFFFF",
      "brightYellow": "#FFFF00",
      "cyan": "#008080",
      "foreground": "#C0C0C0",
      "green": "#008000",
      "name": "Vintage",
      "purple": "#800080",
      "red": "#800000",
      "white": "#C0C0C0",
      "yellow": "#808000"
    },
    {
      "background": "#282C34",
      "black": "#282C34",
      "blue": "#61AFEF",
      "brightBlack": "#5A6374",
      "brightBlue": "#61AFEF",
      "brightCyan": "#56B6C2",
      "brightGreen": "#98C379",
      "brightPurple": "#C678DD",
      "brightRed": "#E06C75",
      "brightWhite": "#DCDFE4",
      "brightYellow": "#E5C07B",
      "cyan": "#56B6C2",
      "foreground": "#DCDFE4",
      "green": "#98C379",
      "name": "One Half Dark",
      "purple": "#C678DD",
      "red": "#E06C75",
      "white": "#DCDFE4",
      "yellow": "#E5C07B"
    },
    {
      "background": "#FAFAFA",
      "black": "#383A42",
      "blue": "#0184BC",
      "brightBlack": "#4F525D",
      "brightBlue": "#61AFEF",
      "brightCyan": "#56B5C1",
      "brightGreen": "#98C379",
      "brightPurple": "#C577DD",
      "brightRed": "#DF6C75",
      "brightWhite": "#FFFFFF",
      "brightYellow": "#E4C07A",
      "cyan": "#0997B3",
      "foreground": "#383A42",
      "green": "#50A14F",
      "name": "One Half Light",
      "purple": "#A626A4",
      "red": "#E45649",
      "white": "#FAFAFA",
      "yellow": "#C18301"
    },
    {
      "background": "#002B36",
      "black": "#073642",
      "blue": "#268BD2",
      "brightBlack": "#002B36",
      "brightBlue": "#839496",
      "brightCyan": "#93A1A1",
      "brightGreen": "#586E75",
      "brightPurple": "#6C71C4",
      "brightRed": "#CB4B16",
      "brightWhite": "#FDF6E3",
      "brightYellow": "#657B83",
      "cyan": "#2AA198",
      "foreground": "#839496",
      "green": "#859900",
      "name": "Solarized Dark",
      "purple": "#D33682",
      "red": "#DC322F",
      "white": "#EEE8D5",
      "yellow": "#B58900"
    },
    {
      "background": "#FDF6E3",
      "black": "#073642",
      "blue": "#268BD2",
      "brightBlack": "#002B36",
      "brightBlue": "#839496",
      "brightCyan": "#93A1A1",
      "brightGreen": "#586E75",
      "brightPurple": "#6C71C4",
      "brightRed": "#CB4B16",
      "brightWhite": "#FDF6E3",
      "brightYellow": "#657B83",
      "cyan": "#2AA198",
      "foreground": "#657B83",
      "green": "#859900",
      "name": "Solarized Light",
      "purple": "#D33682",
      "red": "#DC322F",
      "white": "#EEE8D5",
      "yellow": "#B58900"
    }
  ]
}
```
