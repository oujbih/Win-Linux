# Keyboard.json
```
// Place your key bindings in this file to override the defaults
[
    {
        "key": "shift+alt+down",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+up",
        "command": "editor.action.copyLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+left",
        "command": "cursorLineStartSelect"
    },
    {
        "key": "shift+alt+right",
        "command": "cursorLineEndSelect"
    },
    {
        "key": "Ctrl+enter",
        "command": "macros.pythonExecSelectionAndCursorDown", "when": "editorTextFocus && editorLangId == 'python'" 
    },
    // RStudio: Delete lines cmd-d
    {
        "key": "Ctrl+d",
        "command": "editor.action.deleteLines",
        "when": "editorTextFocus && !editorReadonly"
    },
    // Run current line in a terminal
    {
        "key": "Ctrl+enter",
        "command": "macros.pythonExecSelectionAndCursorDown", "when": "editorTextFocus && editorLangId == 'python'" 
    },
    {
        "key": "ctrl+shift+c",
        "command": "editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+[Period]",
        "command": "-editor.action.commentLine",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+enter",
        "command": "python.execInTerminal-icon"
    },
    {
        "key": "shift+end",
        "command": "-cursorEndSelect",
        "when": "textInputFocus"
    },
    {
        "key": "alt+right",
        "command": "cursorEnd",
        "when": "textInputFocus"
    },
    {
        "key": "end",
        "command": "-cursorEnd",
        "when": "textInputFocus"
    },
    {
        "key": "alt+left",
        "command": "cursorLineStart"
    }
    
]

```
