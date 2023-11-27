# DSLX Language Support for Visual Studio Code

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
- Run `npm run compile`
