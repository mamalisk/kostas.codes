# VS Code configuration:

```json
"workbench.colorCustomizations": {
        "titleBar.activeForeground": "#f8f6f6",
        "titleBar.inactiveForeground": "#cacec9cc",
        "titleBar.activeBackground": "#038080",
        "titleBar.inactiveBackground": "#a6e6ffcc"
    },
    "window.title": "${activeEditorMedium}${separator}${rootName}",
    "editor.cursorSmoothCaretAnimation": true
```

or even

```json
{
    "workbench.colorTheme": "Solarized Light",
    "workbench.iconTheme": "material-icon-theme",
    "gitlens.settings.mode": "advanced",
    "files.autoSave": "afterDelay",
    "editor.fontSize": 15,
    "editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace, Meslo LG L DZ for Powerline",
    "window.zoomLevel": 0,
    "markdown-preview-enhanced.liveUpdate": false,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "terminal.integrated.fontSize": 14,
    "terminal.integrated.shell.osx": "/bin/zsh",
    "mocha.files.glob": "**/*.spec.js",
    "mocha.files.ignore": [
        "**/.git/**/*",
        "**/node_modules/**/*",
        "**/pact*.spec.js"
    ],
    "npm.enableScriptExplorer": true,
    "terminal.integrated.rendererType": "dom",
    "javascript.implicitProjectConfig.experimentalDecorators": true,
    "breadcrumbs.enabled": true,
    "workbench.colorCustomizations": {
        "titleBar.activeForeground": "#f8f6f6",
        "titleBar.inactiveForeground": "#cacec9cc",
        "titleBar.activeBackground": "#038080",
        "titleBar.inactiveBackground": "#a6e6ffcc"
    },
    "window.title": "${activeEditorMedium}${separator}${rootName}",
    "editor.cursorSmoothCaretAnimation": true
}
```
