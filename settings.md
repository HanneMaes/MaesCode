# .devcontainer/devcontainer.json

- Prevent outside modifications: "security.workspace.trust.enabled": false,
- Removes the VSCode extension directory: rm -rf ~/.vscode/extensions
- Ensables word-based autocompletion: "editor.suggest.showWords": true,
- Remove the VSCode extension command: "postCreateCommand": "rm -rf ~/.vscode/extensions && sudo rm -f /usr/bin/code"

# .vscode/settings.json
