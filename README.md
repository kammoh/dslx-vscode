# DSLX Language Support for Visual Studio Code

<div align='center'>
<img src='https://raw.githubusercontent.com/kammoh/dslx-vscode/main/images/xls_logo.png' alt='XLS Logo'>
</div>



## Functionality

- Completions
- Diagnostics

## Structure

```
.
├── src // Language Client
│   ├── test // End to End tests for Language Client / Server
│   └── extension.ts // Language Client entry point
└── package.json // The extension manifest.
```

## Build

- Run `npm install`
- Run `npm run compile` to compile the client.
- To generate the VSIX package run `npm run package`.

## TODO

[ ] Install LSP for platform. Right now `dslx_ls` must be available on the path for the extension to work.
