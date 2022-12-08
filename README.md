# vscode-list-opened-files-as-text README

List all currently opened files as a sorted plain-text.

Example output in a new text buffer could look like this:

```
/home/my-user/projects/my-project/my-root/my-app/models/service_comment.py
/home/my-user/projects/my-project/my-root/my-app/static/js/eventHandlers.js
/home/my-user/projects/my-project/my-root/my-app/static/js/home.js
/home/my-user/projects/my-project/my-root/my-app/templates/service/detail.html
/home/my-user/projects/my-project/my-root/my-app/views/service.py
/home/my-user/projects/my-project/my-root/urls.py
```

Please note, file tabs are lazily accessed in vscode and may not show up in the list if not clicked/visited for a long time, see this issue: https://github.com/microsoft/vscode/issues/15178

## Installation from source

```bash
npm install -g vsce
vsce package
code --install-extension vscode-list-opened-files-as-text-0.0.1.vsix
```
