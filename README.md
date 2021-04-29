# vscode-mql

https://code.visualstudio.com/api/working-with-extensions/publishing-extension

create build:
```sh
vsce package
```

install Linux:
```sh
code --install-extension mql-lang-0.0.38.vsix
```

publish:
```sh
vsce login (publisher name)
vsce publish -p <token>
```