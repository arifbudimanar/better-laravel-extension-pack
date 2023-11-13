![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/arifbudimanar.better-laravel-extension-pack?style=for-the-badge)
![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/arifbudimanar.better-laravel-extension-pack?style=for-the-badge)
![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/arifbudimanar.better-laravel-extension-pack?style=for-the-badge)
![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/arifbudimanar.better-laravel-extension-pack?style=for-the-badge)

# Better Laravel Extension Pack

Better Laravel Extension Pack for a collection of extensions that help you with Laravel development.

## Recommended Settings for minimal and better experience

### settings.json

```json
{
  "[blade]": {
    "editor.defaultFormatter": "shufo.vscode-blade-formatter"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[php]": {
    "editor.defaultFormatter": "open-southeners.laravel-pint"
    // "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
  },
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "blade.format.enable": true,
  "breadcrumbs.enabled": false,
  "database-client.telemetry.usesOnlineServices": false,
  "editor.bracketPairColorization.enabled": false,
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.inlineSuggest.enabled": true,
  "editor.lineHeight": 2.15,
  "editor.matchBrackets": "never",
  "editor.minimap.enabled": false,
  "editor.renderLineHighlight": "none",
  "editor.renderWhitespace": "none",
  "editor.smoothScrolling": true,
  "emmet.excludeLanguages": ["markdown", "php"],
  "errorLens.messageTemplate": "$severity $source - $message  ",
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "files.autoSave": "onWindowChange",
  "git-graph.graph.style": "angular",
  "git.confirmSync": false,
  "intelephense.telemetry.enabled": false,
  "intelephense.trace.server": "messages",
  "laravel-pint.enable": true,
  "laravel-pint.enableDebugLogs": true,
  "laravel-pint.preset": "laravel",
  "material-icon-theme.activeIconPack": "angular",
  "material-icon-theme.folders.color": "#808080",
  "material-icon-theme.folders.theme": "specific",
  "material-icon-theme.hidesExplorerArrows": true,
  "phpParameterHint.changeDelay": 0,
  "phpParameterHint.collapseHintsWhenEqual": true,
  "phpParameterHint.collapseTypeWhenEqual": true,
  "phpParameterHint.fontSize": 14,
  "phpParameterHint.onChange": true,
  "phpParameterHint.onSave": false,
  "phpParameterHint.opacity": 1,
  "phpParameterHint.saveDelay": 0,
  "phpParameterHint.showDollarSign": false,
  "phpParameterHint.textEditorChangeDelay": 0,
  "phpParameterHint.verticalPadding": 0,
  "scm.diffDecorations": "gutter",
  "screencastMode.fontSize": 30,
  "screencastMode.keyboardOverlayTimeout": 5000,
  "screencastMode.verticalOffset": 2,
  "security.workspace.trust.untrustedFiles": "open",
  "telemetry.telemetryLevel": "off",
  "terminal.explorerKind": "external",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.enableMultiLinePasteWarning": false,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "terminal.integrated.gpuAcceleration": "on",
  "typescript.inlayHints.enumMemberValues.enabled": true,
  "window.autoDetectColorScheme": true,
  "window.commandCenter": false,
  "window.menuBarVisibility": "compact",
  "window.title": "${rootName}",
  "workbench.activityBar.visible": false,
  "workbench.colorTheme": "ArifCode Theme",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.layoutControl.enabled": false,
  "workbench.list.smoothScrolling": true,
  "workbench.preferredDarkColorTheme": "ArifCode Theme",
  "workbench.preferredLightColorTheme": "GitHub Light Default",
  "workbench.startupEditor": "none",
  "workbench.statusBar.visible": false,
  "workbench.tree.indent": 16,
  "zenMode.centerLayout": false,
  "zenMode.fullScreen": false,
  "zenMode.hideLineNumbers": false
}
```

### keybindings.json

```json
[
  {
    "key": "alt+d",
    "command": "workbench.view.extension.github-cweijan-mysql"
  },
  {
    "key": "alt+t",
    "command": "workbench.view.extension.thunder-client"
  },
  {
    "key": "ctrl+shift+r",
    "command": "-workbench.view.extension.thunder-client"
  },
  {
    "key": "alt+b",
    "command": "workbench.action.toggleActivityBarVisibility"
  },
  {
    "key": "alt+m",
    "command": "workbench.action.toggleMenuBar"
  },
  {
    "key": "alt+n",
    "command": "workbench.action.toggleStatusbarVisibility"
  },
  {
    "key": "ctrl+n",
    "command": "-workbench.action.files.newUntitledFile"
  },
  {
    "key": "ctrl+n",
    "command": "explorer.newFile"
  },
  {
    "key": "ctrl+enter",
    "command": "-github.copilot.generate",
    "when": "editorTextFocus && github.copilot.activated"
  },
  {
    "key": "alt+g",
    "command": "git-graph.view"
  },
  {
    "key": "ctrl+alt+n",
    "command": "-extension.advancedNewFile"
  },
  {
    "key": "ctrl+0",
    "command": "workbench.action.zoomReset"
  },
  {
    "key": "ctrl+numpad0",
    "command": "-workbench.action.zoomReset"
  },
  {
    "key": "ctrl+enter",
    "command": "-github.copilot.generate",
    "when": "editorTextFocus && github.copilot.activated && !inInteractiveInput && !interactiveEditorFocused"
  },
  {
    "key": "alt+i",
    "command": "namespaceResolver.import",
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+k ctrl+c",
    "command": "workbench.files.action.collapseExplorerFolders"
  },
  {
    "key": "ctrl+k ctrl+shift+w",
    "command": "-workbench.action.closeAllGroups"
  },
  {
    "key": "ctrl+k ctrl+w",
    "command": "-workbench.action.closeAllEditors"
  },
  {
    "key": "ctrl+k w",
    "command": "-workbench.action.closeEditorsInGroup"
  },
  {
    "key": "ctrl+k ctrl+w",
    "command": "workbench.action.closeAllEditors"
  },
  {
    "key": "ctrl+k ctrl+shift+w",
    "command": "workbench.action.closeOtherEditors"
  }
]
```
