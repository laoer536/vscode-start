# Vscode start

Vscode repo setting.

## Font for Vscode

[JetBrainsMono](https://www.jetbrains.com/lp/mono/)

## Settings

```json
{
  /** Editor appearance **/
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Aura Soft Dark",
  "editor.fontFamily": "'JetBrains Mono','Helvetica',Consolas, 'Courier New', monospace",
  "editor.fontWeight": 300,
  "editor.lineHeight": 1.7,
  /** Prettier **/
  "prettier.enable": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  /** Eslint **/
  "eslint.enable": true,
  "eslint.useFlatConfig": true,
  "eslint.format.enable": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.organizeImports": "explicit"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact",
    "vue",
    "html",
    "markdown",
    "json",
    "jsonc",
    "yaml"
  ],
  /** For a better coding experience **/
  "editor.quickSuggestions": {
    "strings": "on"
  },
  "cSpell.userWords": ["antd"],
  "editor.stickyScroll.enabled": true,
  "editor.guides.bracketPairs": "active",
  "editor.smoothScrolling": true,
  "workbench.list.smoothScrolling": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "expand",
  "editor.suggest.insertMode": "replace",
  "editor.suggest.snippetsPreventQuickSuggestions": false,
  "editor.acceptSuggestionOnEnter": "smart",
  "editor.suggestSelection": "recentlyUsedByPrefix",
  "typescript.inlayHints.enumMemberValues.enabled": true,
  "editor.minimap.enabled": false,
  "editor.foldingStrategy": "indentation",
  "update.mode": "manual",
  "search.followSymlinks": false,
  "search.exclude": {
    "**/node_modules": true,
    "**/pnpm-lock.yaml": true,
    "**/package-lock.json": true,
    "**/.DS_Store": true,
    "**/.git": true,
    "**/.gitignore": true,
    "**/.idea": true,
    "**/.svn": true,
    "**/.vscode": true,
    "**/build": true,
    "**/dist": true,
    "**/tmp": true,
    "**/yarn.lock": true
  },
  "typescript.updateImportsOnFileMove.enabled": "always",
  /** Personal personalized configuration **/
  "files.associations": {
    "*.css": "tailwindcss",
    "*.wxss": "css",
    "*.wxml": "html",
    "*.svg": "html",
    "*.xml": "html",
    "*.wxs": "javascript",
    "*.cjson": "jsonc",
    "*.json": "jsonc"
  },
  "tailwindCSS.experimental.classRegex": [
    ["cva\\(([^)]*)\\)", "[\"'`]([^\"'`]*).*?[\"'`]"],
    ["cx\\(([^)]*)\\)", "(?:'|\"|`)([^']*)(?:'|\"|`)"]
  ],
  "typescript.inlayHints.parameterNames.enabled": "all",
  "typescript.inlayHints.parameterTypes.enabled": true,
  "typescript.inlayHints.variableTypes.enabled": true,
  "typescript.inlayHints.propertyDeclarationTypes.enabled": true
  // "typescript.inlayHints.functionLikeReturnTypes.enabled": true
}
```

## Extensions

```json
{
  "recommendations": [
    "aaron-bond.better-comments",
    "adam-bender.commit-message-editor",
    "antfu.where-am-i",
    "astro-build.astro-vscode",
    "bradlc.vscode-tailwindcss",
    "burkeholland.simple-react-snippets",
    "chakrounanas.turbo-console-log",
    "codezombiech.gitignore",
    "cweijan.dbclient-jdbc",
    "cweijan.vscode-postgresql-client2",
    "daltonmenezes.aura-theme",
    "dbaeumer.vscode-eslint",
    "eamodio.gitlens",
    "editorconfig.editorconfig",
    "esbenp.prettier-vscode",
    "formulahendry.auto-close-tag",
    "formulahendry.auto-rename-tag",
    "formulahendry.code-runner",
    "gruntfuggly.todo-tree",
    "hancel.markdown-image",
    "intellsmi.comment-translate",
    "isudox.vscode-jetbrains-keybindings",
    "kisstkondoros.vscode-gutter-preview",
    "lokalise.i18n-ally",
    "mariusalchimavicius.json-to-ts",
    "meganrogge.template-string-converter",
    "mhutchie.git-graph",
    "mikestead.dotenv",
    "ms-azuretools.vscode-docker",
    "ms-ceintl.vscode-language-pack-zh-hans",
    "ms-vscode-remote.remote-containers",
    "naumovs.color-highlight",
    "orta.vscode-jest",
    "pkief.material-icon-theme",
    "pmneo.tsimporter",
    "pranaygp.vscode-css-peek",
    "prisma.prisma",
    "streetsidesoftware.code-spell-checker",
    "svga-perview.svga-perview",
    "usernamehw.errorlens",
    "vue.volar",
    "wix.vscode-import-cost",
    "yoavbls.pretty-ts-errors",
    "yzhang.markdown-all-in-one",
    "ziyasal.vscode-open-in-github",
    "znck.grammarly"
  ]
}
```
