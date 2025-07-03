# Comenzi utile pentru dezvoltarea extensiilor VSCode

## Create project
```bash
npm i -g yo generator-code
```

## Generate a new extension
```
yo code
```

## Package the extension
```
vsce package
```

## Install dependencies in case vsce is not installed
```
npm install -g @vscode/vsce
```