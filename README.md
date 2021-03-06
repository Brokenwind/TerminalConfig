# TerminalConfig
windows terminal 的配置文件

### ubuntu的效果
![](ubuntu-terminal.png)

### powershell的效果
![](powershell.png)

### 具体的配置内容

```json
{
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "defaultProfile": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
    "copyOnSelect": false,
    "copyFormatting": false,
    "profiles":
    {
        "defaults":
        {
        },
        "list":
        [
            {
                "guid": "{07b52e3e-de2c-5db4-bd2d-ba144ed6c273}",
                "hidden": false,
                "name": "Ubuntu-20.04",
                "source": "Windows.Terminal.Wsl",
                "colorScheme": "AdventureTime",
                "backgroundImage": "C://star-night.jpg",
                "backgroundImageOpacity": 0.8,
                "cursorColor": "#FFFFFF",
                "fontFace": "Delugia Nerd Font",
                "hidden": false,
                "background": "#000000"
           },
            {
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "name": "Windows PowerShell",
                "commandline": "powershell.exe",
                "hidden": false,
                "colorScheme": "Material",
                "backgroundImage": "C://moutain-star.jpg",
                "backgroundImageOpacity": 0.8,
                "fontFace": "Delugia Nerd Font"
            },
            {
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "命令提示符",
                "commandline": "cmd.exe",
                "hidden": false
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure"
            }
        ]
    },
    "schemes": [
        {
            "name":"Material",
            "background":"#263238",
            "foreground":"#eeffff",
            "black":"#000000",
            "blue":"#82aaff",
            "brightBlack":"#546e7a",
            "brightBlue":"#82aaff",
            "brightCyan":"#89ddff",
            "brightGreen":"#c3e88d",
            "brightPurple":"#c792ea",
            "brightRed":"#ff5370",
            "brightWhite":"#ffffff",
            "brightYellow":"#ffcb6b",
            "cyan":"#89ddff",
            "green":"#c3e88d",
            "purple":"#c792ea",
            "red":"#ff5370",
            "white":"#ffffff",
            "yellow":"#ffcb6b"
        },
        {
            "name":"3024 Day",
            "black":"#090300",
            "red":"#db2d20",
            "green":"#01a252",
            "yellow":"#fded02",
            "blue":"#01a0e4",
            "purple":"#a16a94",
            "cyan":"#b5e4f4",
            "white":"#a5a2a2",
            "brightBlack":"#5c5855",
            "brightRed":"#e8bbd0",
            "brightGreen":"#3a3432",
            "brightYellow":"#4a4543",
            "brightBlue":"#807d7c",
            "brightPurple":"#d6d5d4",
            "brightCyan":"#cdab53",
            "brightWhite":"#f7f7f7",
            "background":"#f7f7f7",
            "foreground":"#4a4543"
        },
        {
            "name":"AdventureTime",
            "black":"#050404",
            "red":"#bd0013",
            "green":"#4ab118",
            "yellow":"#e7741e",
            "blue":"#0f4ac6",
            "purple":"#665993",
            "cyan":"#70a598",
            "white":"#f8dcc0",
            "brightBlack":"#4e7cbf",
            "brightRed":"#fc5f5a",
            "brightGreen":"#9eff6e",
            "brightYellow":"#efc11a",
            "brightBlue":"#1997c6",
            "brightPurple":"#9b5953",
            "brightCyan":"#c8faf4",
            "brightWhite":"#f6f5fb",
            "background":"#1f1d45",
            "foreground":"#f8dcc0"
        }
    ],
    "keybindings":
    [
        { "command": {"action": "copy", "singleLine": false }, "keys": "ctrl+shift+c" },
        { "command": "paste", "keys": "ctrl+shift+v" },
        { "command": "find", "keys": "ctrl+shift+f" },
        { "command": { "action": "splitPane", "split": "auto", "splitMode": "duplicate" }, "keys": "alt+shift+d" },
        { "command": { "action": "switchToTab", "index": 0 }, "keys": "alt+1" },
        { "command": { "action": "switchToTab", "index": 1 }, "keys": "alt+2" },
        { "command": { "action": "switchToTab", "index": 2 }, "keys": "alt+3" },
        { "command": { "action": "switchToTab", "index": 3 }, "keys": "alt+4" },
        { "command": { "action": "switchToTab", "index": 4 }, "keys": "alt+5" },
        { "command": { "action": "switchToTab", "index": 5 }, "keys": "alt+6" },
        { "command": { "action": "switchToTab", "index": 6 }, "keys": "alt+7" },
        { "command": { "action": "switchToTab", "index": 7 }, "keys": "alt+8" },
        { "command": { "action": "switchToTab", "index": 8 }, "keys": "alt+9" }
    ]
}
```
