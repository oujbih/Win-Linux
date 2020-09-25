# vs code rstudio shortcuts
## keybindings.json
```
// Place your key bindings in this file to override the defaults
[
    {
        "key": "alt+Ctrl+down",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "alt+Ctrl+up",
        "command": "editor.action.copyLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
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
    }
]
```

## settings.json 

```
{   
    "python.pythonPath": "/usr/bin/python3",
    "macros": {  // update: requires macros extension by publisher:"geddski" 
        "pythonExecSelectionAndCursorDown": [
            "python.execSelectionInTerminal", 
            //"vscode.window.activeTextEditor.show()",
            "cursorDown" 
        ]
    }
    
}

```

## View mode 
```
If you want to disable Preview Mode all together, you can do so by setting "workbench.editor.enablePreview": false in your settings file. You can also use the "workbench.editor.enablePreviewFromQuickOpen" option to disable it only from the quick 
```
