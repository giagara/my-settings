# Set of rules for my dev env

## VS Code

### Eslint

[Install](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

### Prettier

[Install](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### Settings.json

```
{
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true,
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "typescript",
        "typescriptreact"
    ],
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
    }    
}
```

---