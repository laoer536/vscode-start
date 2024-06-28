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
  ]
}
```

## Extensions

```
aaron-bond.better-comments@3.0.2
adam-bender.commit-message-editor@0.25.0
antfu.where-am-i@0.2.0
astro-build.astro-vscode@2.10.2
bradlc.vscode-tailwindcss@0.12.2
burkeholland.simple-react-snippets@1.2.8
chakrounanas.turbo-console-log@2.10.4
codezombiech.gitignore@0.9.0
cweijan.dbclient-jdbc@1.3.5
cweijan.vscode-postgresql-client2@7.5.2
daltonmenezes.aura-theme@2.1.2
dbaeumer.vscode-eslint@3.0.10
eamodio.gitlens@15.1.0
editorconfig.editorconfig@0.16.4
esbenp.prettier-vscode@10.4.0
formulahendry.auto-close-tag@0.5.15
formulahendry.auto-rename-tag@0.1.10
formulahendry.code-runner@0.12.2
gruntfuggly.todo-tree@0.0.226
hancel.markdown-image@1.1.41
intellsmi.comment-translate@2.3.3
isudox.vscode-jetbrains-keybindings@0.1.9
kisstkondoros.vscode-gutter-preview@0.31.2
lokalise.i18n-ally@2.12.0
mariusalchimavicius.json-to-ts@1.8.0
meganrogge.template-string-converter@0.6.1
mhutchie.git-graph@1.30.0
mikestead.dotenv@1.0.1
ms-azuretools.vscode-docker@1.29.1
ms-ceintl.vscode-language-pack-zh-hans@1.90.2024061209
ms-vscode-remote.remote-containers@0.369.0
naumovs.color-highlight@2.8.0
orta.vscode-jest@6.2.5
pkief.material-icon-theme@5.4.2
pmneo.tsimporter@2.0.1
pranaygp.vscode-css-peek@4.4.1
prisma.prisma@5.16.1
streetsidesoftware.code-spell-checker@3.0.1
svga-perview.svga-perview@1.0.0
usernamehw.errorlens@3.20.0
vue.volar@1.6.4
wix.vscode-import-cost@3.3.0
yoavbls.pretty-ts-errors@0.5.4
yzhang.markdown-all-in-one@3.6.2
ziyasal.vscode-open-in-github@1.3.6
znck.grammarly@0.24.0
```
