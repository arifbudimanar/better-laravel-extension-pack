# Better Laravel Extension Pack

Better Laravel Extension Pack for a collection of extensions that help you with Laravel development.

## Recommended Settings for minimal and better experience

### settings.json

```json
  "editor.inlineSuggest.enabled": true,
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "git.confirmSync": false,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "explorer.confirmDelete": false,
  "terminal.integrated.gpuAcceleration": "on",
  "php.validate.enable": false,
  "emmet.excludeLanguages": [
    "markdown",
    "php"
  ],
  "[php]": {
    "editor.defaultFormatter": "open-southeners.laravel-pint"
    // "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
  },
  "[blade]": {
    "editor.defaultFormatter": "shufo.vscode-blade-formatter"
  },
  "[typescript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "telemetry.telemetryLevel": "off",
  "typescript.inlayHints.enumMemberValues.enabled": true,
  "scm.diffDecorations": "gutter",
  "files.autoSave": "onWindowChange",
  "editor.renderLineHighlight": "none",
  "editor.matchBrackets": "never",
  "workbench.startupEditor": "none",
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.fontFamily": "JetBrains Mono",
  "editor.fontLigatures": true,
  "editor.lineHeight": 2.15,
  "security.workspace.trust.untrustedFiles": "open",
  "explorer.confirmDragAndDrop": false,
  "zenMode.centerLayout": false,
  "workbench.preferredDarkColorTheme": "ArifCode Theme",
  "window.autoDetectColorScheme": true,
  "workbench.preferredLightColorTheme": "GitHub Light Default",
  "explorer.compactFolders": false,
  "workbench.tree.indent": 16,
  "editor.smoothScrolling": true,
  "terminal.integrated.cursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "terminal.integrated.enableMultiLinePasteWarning": false,
  "editor.bracketPairColorization.enabled": false,
  "laravel-pint.enable": true,
  "terminal.explorerKind": "external",
  "terminal.integrated.cursorBlinking": true,
  "zenMode.fullScreen": false,
  "blade.format.enable": true,
  "LaravelExtraIntellisense.basePath": "App\\",
  "intelephense.environment.phpVersion": "8.1.21",
  "laravel-pint.enableDebugLogs": true,
  "editor.formatOnSave": true,
  "zenMode.hideLineNumbers": false,
  "laravel-pint.preset": "laravel",
  "window.title": "${rootName}",
  "editor.minimap.enabled": false,
  "workbench.list.smoothScrolling": true,
  "workbench.layoutControl.enabled": false,
  "editor.renderWhitespace": "none",
  "git-graph.graph.style": "angular",
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.folders.color": "#808080",
  "intelephense.runtime": "C:\\laragon\\bin\\nodejs\\node-v18.17.0-win-x64\\node.exe",
  "material-icon-theme.folders.theme": "specific",
  "phpParameterHint.collapseTypeWhenEqual": true,
  "phpParameterHint.onChange": true,
  "phpParameterHint.changeDelay": 0,
  "phpParameterHint.saveDelay": 0,
  "phpParameterHint.verticalPadding": 0,
  "phpParameterHint.collapseHintsWhenEqual": true,
  "phpParameterHint.onSave": false,
  "phpParameterHint.textEditorChangeDelay": 0,
  "phpParameterHint.opacity": 1,
  "phpParameterHint.fontSize": 14,
  "material-icon-theme.activeIconPack": "angular",
  "phpParameterHint.showDollarSign": true,
  "errorLens.messageTemplate": "$severity $source - $message  ",
  "breadcrumbs.enabled": false,
  "database-client.telemetry.usesOnlineServices": false,
  "window.commandCenter": false,
  "diffEditor.ignoreTrimWhitespace": false,
  "workbench.colorTheme": "ArifCode Theme",
  "workbench.activityBar.visible": false,
  "workbench.statusBar.visible": false,
  "window.menuBarVisibility": "compact"
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
