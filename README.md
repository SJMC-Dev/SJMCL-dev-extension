# SJMCL Developer VSCode Extension

Developer extension for SJMCL workspace, created with ❤️ and 🤖 (Codex).

## Compile

```bash
cd tools/vscode-extension
npm install
npm run compile
 npx vsce package
```

## Features

1. Jump from a frontend `invoke("...")` call to the corresponding backend Tauri command.
2. Hover a locale key segment in `t("...")` and jump to (or create) that key in locale files.
