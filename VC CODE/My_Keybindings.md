# Meu arquivo json para atalhos de teclado do vs-code

// Coloque as suas associações de teclas neste arquivo para substituir os padrõesauto[]
```JSON
[
    {
        "key": "ctrl+oem_1",
        "command": "workbench.action.nextEditor"
    },
    {
        "key": "ctrl+oem_1",
        "command": "workbench.action.focusNextGroup"
    },
    {
        "key": "f3",
        "command": "workbench.view.scm",
        "when": "workbench.scm.active"
    },
    {
        "key": "ctrl+j",
        "command": "-workbench.action.togglePanel"
    },
    {
        "key": "ctrl+j",
        "command": "workbench.action.gotoSymbol"
    },
    {
        "key": "shift+f3",
        "command": "commitMessageEditor.openSettingsPage"
    },
    {
        "key": "shift+f3",
        "command": "commitMessageEditor.openEditor"
    },
    {
        "key": "pausebreak",
        "command": "git.stageAll"
    },
    {
        "key": "ctrl+alt+f12",
        "command": "workbench.action.toggleLightDarkThemes"
    },
    {
        "key": "ctrl+oem_102",
        "command": "editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.reloadWindow",
        "when": "isDevelopment"
    },
    {
        "key": "ctrl+alt+oem_1",
        "command": "workbench.action.toggleEditorWidths"
    },
    {
        "key": "ctrl+oem_period",
        "command": "-editor.action.quickFix",
        "when": "editorHasCodeActionsProvider && editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+oem_period",
        "command": "-acceptSelectedCodeAction",
        "when": "codeActionMenuVisible"
    },
    {
        "key": "ctrl+oem_period",
        "command": "-problems.action.showQuickFixes",
        "when": "problemFocus"
    },
    {
        "key": "ctrl+oem_period",
        "command": "-workbench.action.terminal.showQuickFixes",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+oem_period",
        "command": "breadcrumbs.focusAndSelect",
        "when": "breadcrumbsPossible && breadcrumbsVisible"
    },
    {
        "key": "ctrl+shift+oem_period",
        "command": "-breadcrumbs.focusAndSelect",
        "when": "breadcrumbsPossible && breadcrumbsVisible"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.terminal.runRecentCommand",
        "when": "accessibilityModeEnabled && terminalFocus && terminalHasBeenCreated || accessibilityModeEnabled && terminalFocus && terminalProcessSupported"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.quickOpenNavigateNextInRecentFilesPicker",
        "when": "inQuickOpen && inRecentFilesPicker"
    },
    {
        "key": "ctrl+r",
        "command": "-workbench.action.openRecent"
    },
    {
        "key": "ctrl+r",
        "command": "workbench.files.action.showActiveFileInExplorer"
    },
    // Project Manager [extensão] (oem_102 = \)
    {
        "key": "scrolllock",
        "command": "workbench.view.extension.project-manager"
    },
    {
        "key": "ctrl+shift+oem_102",
        "command": "workbench.view.extension.project-manager"
    },
    {
        "key": "ctrl+shift+r",
        "command": "workbench.view.extension.project-manager"
    }
]
```
