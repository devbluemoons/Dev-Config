## Terminal `VSCode`

- apply `iTerm.app`
- change `Theme`

```json
{
    // eslint
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "editor.formatOnSave": true,

    // Google's material-design-colors
    "terminal.integrated.defaultProfile.osx": "zsh",
    "terminal.external.osxExec": "iTerm.app",
    "terminal.integrated.fontFamily": "MesloLGS NF",
    "workbench.colorCustomizations": {
        "terminal.background": "#263137",
        "terminal.foreground": "#eceef0",
        "terminal.ansiBlack": "#546d79",
        "terminal.ansiRed": "#ff5151",
        "terminal.ansiGreen": "#69f0ad",
        "terminal.ansiYellow": "#ffd73f",
        "terminal.ansiBlue": "#00b0ff",
        "terminal.ansiMagenta": "#ff3f80",
        "terminal.ansiCyan": "#64fcda",
        "terminal.ansiWhite": "#fefefe",
        "terminal.ansiBrightBlack": "#b0bec4",
        "terminal.ansiBrightRed": "#ff8980",
        "terminal.ansiBrightGreen": "#b9f6c9",
        "terminal.ansiBrightYellow": "#ffe47e",
        "terminal.ansiBrightBlue": "#80d7fe",
        "terminal.ansiBrightMagenta": "#ff80ab",
        "terminal.ansiBrightCyan": "#a7fdeb",
        "terminal.ansiBrightWhite": "#fefefe"
    },

    // bracket pair colorizer-2
    "bracket-pair-colorizer-2.colors": [
        "DeepSkyBlue",
        "DodgerBlue",
        "MediumSlateBlue",
        "BlueViolet",
        "MediumVioletRed",
        "DeepPink",
        "Red",
        "DarkOrange",
        "Gold",
        "GreenYellow",
        "LimeGreen",
        "LightSeaGreen",
        "DarkTurquoise"
    ],

    // indent rainbow
    "indentRainbow.colors": [
        "rgba(0,191,255,0.07)",
        "rgba(30,144,255,0.07)",
        "rgba(123,104,238,0.07)",
        "rgba(138,43,226,0.07)",
        "rgba(199,21,133,0.07)",
        "rgba(255,20,147,0.07)",
        "rgba(255,0,0,0.07)",
        "rgba(255,140,0,0.07)",
        "rgba(255,215,0,0.07)",
        "rgba(173,255,47,0.07)",
        "rgba(50,205,50,0.07)",
        "rgba(32,178,170,0.07)",
        "rgba(0,206,209,0.07)"
    ],
    // display whitespace
    "editor.renderWhitespace": "all",
    "workbench.iconTheme": "material-icon-theme",

    "editor.tabSize": 4,
    "editor.insertSpaces": true,
    "editor.detectIndentation": false,
    "bracket-pair-colorizer-2.depreciation-notice": false,
    "prettier.tabWidth": 4,
    "typescript.updateImportsOnFileMove.enabled": "always",
    "go.toolsManagement.autoUpdate": true,
    "workbench.startupEditor": "none",
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "terminal.integrated.copyOnSelection": true
}
```
