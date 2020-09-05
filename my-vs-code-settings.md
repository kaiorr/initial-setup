{
    /**
     * Better Defaults
     **/
    "editor.copyWithSyntaxHighlighting": false,
    "diffEditor.ignoreTrimWhitespace": false,
    "editor.emptySelectionClipboard": false,
    "workbench.editor.enablePreview": false,
    "window.newWindowDimensions": "inherit",
    "files.trimTrailingWhitespace": true,
    "diffEditor.renderSideBySide": false,
    "editor.snippetSuggestions": "inline",
    "editor.detectIndentation": false,
    "window.nativeFullScreen": false,
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,

    /**
     * Workbench Settings
     */
    "workbench.colorTheme": "Omni",
    "workbench.sideBar.location": "right",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "none",
    "workbench.editor.highlightModifiedTabs": true,
    "workbench.editor.labelFormat": "short",
    "workbench.list.keyboardNavigation": "filter",
    "workbench.editor.enablePreviewFromQuickOpen": false,

    /**
     * Silence Some Noise
     */
    "breadcrumbs.enabled": true,
    "breadcrumbs.filePath": "last",
    "workbench.tips.enabled": false,
    "editor.colorDecorators": false,
    "git.decorations.enabled": false,
    // "editor.lightbulb.enabled": false,
    "editor.overviewRulerBorder": false,
    "editor.renderLineHighlight": "all",
    "editor.occurrencesHighlight": false,
    "editor.renderControlCharacters": false,
    "editor.gotoLocation.multipleReferences": "goto",
    "editor.gotoLocation.multipleDefinitions": "goto",
    "editor.gotoLocation.multipleDeclarations": "goto",
    "editor.gotoLocation.multipleImplementations": "goto",
    "editor.gotoLocation.multipleTypeDefinitions": "goto",

    /**
     * Editor Settings
     */
    "editor.cursorBlinking": "phase",
    "editor.cursorStyle": "line",
    "editor.tabSize": 2,
    "editor.fontSize": 18,
    "editor.lineHeight": 28,
    "editor.suggestFontSize": 14,
    "editor.fontFamily": "Fira Code Retina, FiraCode-Retina",
    "editor.fontLigatures": true,
    "editor.insertSpaces": true,
    "editor.rulers": [80, 120],
    "editor.wordWrap": "on",
    "editor.wordWrapColumn": 150,
    "editor.smoothScrolling": true,
    "editor.renameOnType": true,
    "editor.formatOnSave": false,
    "editor.codeActionsOnSave": {
      "source.fixAll.eslint": true
    },
    "editor.suggestSelection": "first",
    "editor.quickSuggestions": true,
    "editor.wordBasedSuggestions": true,
    "editor.parameterHints.enabled": false,
    "editor.semanticHighlighting.enabled": false,
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "vsintellicode.typescript.completionsEnabled": true,

    /**
     * Explorer Settings
     */
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "explorer.compactFolders": false,

    /**
     * Search Settings
     **/
    "search.useIgnoreFiles": false,
    "search.exclude": {
      "**/public/{[^i],?[^n]}*": true,
      "**/node_modules": true,
      "**/dist": true,
      "**/yarn.lock": true,
      "**/package-lock.json": true
    },

    /**
     * Window Settings
     */
    "window.zoomLevel": 0,
    "window.titleSeparator": " | ",
    "window.closeWhenEmpty": false,
    // Note for Windows users:
    // Unfortunately, "Full-bleed" isn't possible in Windows.
    // The best you can do is use the native "Windows" window
    // style and add these CSS selectors to clean it up further.
    "window.menuBarVisibility": "toggle",
    "window.titleBarStyle": "custom", // Switch to Native if in MacOS
    "window.nativeTabs": true, //MacOS only
    "customizeUI.stylesheet": {
      // ".editor .title": "background: transparent !important;",
      // ".editor .title .label-container": "visibility: hidden;",
      // Hide top-right buttons
      ".editor .title .actions-container .action-item a:not(.codicon-close)": "visibility: hidden;",
      // Show top-right "settings goto icon"
      ".editor .title .actions-container .action-item a[title=\"Open Settings (UI)\"]": "visibility: initial;",
      ".editor .title .actions-container .action-item a[title=\"Open Settings (JSON)\"]": "visibility: initial;",
      // Make it the "right-most" icon.
      ".editor .title .actions-container": "flex-direction: row-reverse;",
      // Only show the scrollbar on hover.
      ".editor .scrollbar": "cursor:pointer;",
      ".editor .scrollbar .slider": "opacity: 0; transition: opacity 180ms ease-in-out;",
      ".editor .scrollbar:hover .slider": "opacity: 1",
      // Change cursor color.
      ".monaco-editor .cursor": "background: #04D361 !important; color: #292D3E !important"
    },

    /**
     * Files Settings
     */
    "files.eol": "\n",
    "files.autoSave": "onFocusChange",
    "files.defaultLanguage": "typescript",
    "files.associations": {
      "*.html": "html",
      "*.js": "javascriptreact",
      "ace": "javascript",
      ".env.testing.example": "dotenv",
      ".sequelizerc": "javascript",
      ".prettierrc": "json",
      ".stylelintrc": "json"
    },
    "files.exclude": {
      "**/.git": true,
      "**/.svn": true,
      "**/.hg": true,
      "**/CVS": true,
      "**/.DS_Store": true,
      "node_modules": true
    },

    /**
     * Emmet Settings
     */
    "emmet.syntaxProfiles": { "javascript": "jsx" },
    "emmet.includeLanguages": { "javascript": "javascriptreact" },
    "emmet.triggerExpansionOnTab": true,

    /**
     * TS and JS Server Settings
     */
    "typescript.tsserver.log": "verbose",
    "typescript.suggest.autoImports": true,
    "typescript.updateImportsOnFileMove.enabled": "never",

    "javascript.suggest.autoImports": true,
    "javascript.updateImportsOnFileMove.enabled": "never",
    // "javascript.implicitProjectConfig.checkJs": true,

    /**
     * Extensions Settings
     */
    "extensions.ignoreRecommendations": true,
    "extensions.autoCheckUpdates": true,
    "extensions.autoUpdate": true,

    /**
     * Parameter Hints Settings
     */
    "parameterHints.hintingType": "variableOnly",

    /**
     * Project Manager Extension Settings
     */
    "projectManager.git.baseFolders": ["$home/work", "$home/www"],

    /**
     * Git Settings
     */
    "git.autofetch": true,
    "git.enableSmartCommit": true,
    "git.enableCommitSigning": true,

    /**
     * GitLens Extension Settings
     */
    "gitlens.codeLens.recentChange.enabled": false,
    "gitlens.codeLens.authors.enabled": false,
    "gitlens.codeLens.enabled": false,

    /**
     * ESLint Extension Settings
     **/
    "eslint.run": "onType",
    "eslint.packageManager": "yarn",
    "eslint.validate": [
      "javascript",
      "javascriptreact",
      "typescript",
      "typescriptreact"
    ],

    /**
     * Prettier Extension Settings
     **/
    "[javascript, javascriptreact]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "prettier.useTabs": false,
    // "prettier.requireConfig": true,
    "prettier.useEditorConfig": false,

    /**
     * Material Icon Theme Settings
     */
    "material-icon-theme.folders.color": "#8257e5",
    "material-icon-theme.activeIconPack": "react_redux",
    "material-icon-theme.folders.associations": {
      "start": "core",
      "patches": "packages",
      "seeds": "generator",
      "functional": "tasks",
      "unit": "tasks",
      "config": "tools",
      "pages": "routes",
      "assets": "images",
      "styles": "theme",
      "exceptions": "error",
      "components": "react-components",
      "store": "redux-store",
      "infra": "app",
      "entities": "class",
      "schemas": "class",
      "typeorm": "database",
      "repositories": "mappings",
      "http": "container",
      "migrations": "tools",
      "modules": "components",
      "implementations": "core",
      "dtos": "typescript",
      "fakes": "mock",
      "websockets": "pipe",
      "protos": "pipe",
      "grpc": "pipe"
    },
    "material-icon-theme.files.associations": {
      "package.json": "nodejs_alt",
      "*.example": "tune",
      "ormconfig.json": "database",
      "jsconfig.json": "settings",
      "tsconfig.json": "settings",
      "styles.js": "css",
      "styles.ts": "css",
      "ace": "adonis",
      "*.proto": "3d",
    },

    /**
     * Import Cost Extension Settings
     */
    "importCost.largePackageColor": "#EC3A37F5",
    "importCost.mediumPackageColor": "#e7de79",
    "importCost.smallPackageColor": "#67e480",

    /**
     * CodeSnap Extension Settings
     */
    "codesnap.transparentBackground": true,
    "codesnap.showWindowTitle": true,

    /**
     * Error Lens Extension Settings
     */
    "errorLens.enabledDiagnosticLevels": ["error", "info", "warning"],

    /**
     * Advanced New File Extension Settings
     */
    "advancedNewFile.exclude": {
      "node_modules": true,
      "node_modules_electron": true,
      "dev": true,
      "dist": true,
      "android": true,
      "ios": true
    },
    "advancedNewFile.showInformationMessages": true,
    "advancedNewFile.convenienceOptions": ["current", "last", "root"],


    /**
     * Live Server Estension Settings
     */
    "liveServer.settings.donotShowInfoMsg": true,

    /**
     * CSpell Extension Settings
     */
    "cSpell.language": "pt-BR,en",
    "cSpell.enableFiletypes": ["dotenv", "jsx-tags"],
    "cSpell.userWords": [
      "Devtools",
      "Mentoria",
      "Reactotron",
      "Rocketseat",
      "adonisjs",
      "allowed",
      "allowed envs",
      "bootcamp",
      "bootcamps",
      "cerbero",
      "changelogs",
      "desaturate",
      "envs",
      "esnext",
      "gamificate",
      "gamification",
      "gostack",
      "heatmap",
      "immer",
      "iphone",
      "launchbase",
      "linkedin",
      "middlewares",
      "minmax",
      "navs",
      "onboarded",
      "persistor",
      "pickone",
      "postgres",
      "readonly",
      "scrollbar",
      "stylesheet",
      "toastify",
      "unform",
      "youtube"
    ],

    /**
     * Create React Component Extension Settings
     */
    "createReactTSXComponent.fileExtension": "js",

    /**
     * TabNine Extension Settings
     */
    "tabnine.experimentalAutoImports": true,
    "java.project.importHint": false
  }
