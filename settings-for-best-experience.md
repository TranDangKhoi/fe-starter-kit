## Những sự tinh chỉnh cần thiết để có trải nghiệm tốt nhất với VSCode

Khi bắt đầu sử dụng VSCode, ta có thể sử dụng ngay lập tức lun cũng ok. Nhưng sẽ có một vài thứ thiệt thòi so với những người đã có kinh nghiệm sử dụng

### 1. Cài đặt Extensions

Để có thể thao tác nhanh hơn thì ta sẽ phải cài extensions cho VSCode. Có rất nhiều extensions, nhưng ở đây ta chỉ cần thứ tôi đã đề cập trên video.

- Babel Javascript
- DotENV
- EditorConfig for VS Code
- Một cái theme nào đó
- Evondev snippets
- Hero Icons
- html to JSX
- JavaScript (ES6) code snippets
- JavaScript Booster
- Live Server
- Material Icon Theme
- Multiple cursor case preserve
- npm Intellisense
- Path Intellisense
- Prettier - Code formatter
- Reactjs code snippets
- SCSS IntelliSense

### 2. Tinh chỉnh Settings

LƯU Ý: CHỈ THÊM ĐOẠN SETTING SAU KHI ĐÃ CÀI ĐẶT ĐẦY ĐỦ EXTENSIONS TRONG VIDEO

- Mở file `settings.json` lên, và copy paste đoạn JSON dưới đây vào

```json
{
  "files.associations": {
    "*html": "html",
    "*njk": "html"
  },
  "editor.quickSuggestions": {
    "strings": true
  },
  "html.autoClosingTags": true,
  "javascript.autoClosingTags": true,
  "typescript.autoClosingTags": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "git.autofetch": true,
  "editor.cursorBlinking": "smooth",
  "editor.minimap.enabled": false,
  "tailwindCSS.classAttributes": [
    "class",
    "className",
    "ngClass",
    ".*Styles",
    ".*ClassName"
  ],
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "color-highlight.markerType": "underline",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnPaste": true,
  "workbench.iconTheme": "material-icon-theme",
  "color-highlight.enable": true,
  "editor.formatOnSave": true,
  "editor.codeLens": false,
  "terminal.integrated.gpuAcceleration": "on",
  "files.exclude": {
    "**/node_modules": true,
    "**/.classpath": true,
    "**/.project": true,
    "**/.settings": true,
    "**/.factorypath": true
  },
  "html.format.wrapLineLength": 170,
  "editor.inlineSuggest.enabled": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "vue-html": "html"
  },
  "emmet.triggerExpansionOnTab": true,
  "[javascript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[jsonc]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "editor.suggestSelection": "first",
  "editor.wordWrapColumn": 100,
  "explorer.compactFolders": false,
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "tailwindCSS.emmetCompletions": true,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "editor.guides.bracketPairs": true,
  "javascript.inlayHints.functionLikeReturnTypes.enabled": true,
  "javascript.suggest.completeFunctionCalls": true,
  "css.lint.unknownAtRules": "ignore",
  "editor.lineHeight": 1.6,
  "scss.lint.unknownAtRules": "ignore",
  "editor.cursorSmoothCaretAnimation": "on",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.colorCustomizations": {
    "editorInfo.foreground": "#00000000"
  },
  "errorLens.enabledDiagnosticLevels": ["error", "warning"],
  "editor.inlayHints.enabled": "off",
  "workbench.editor.wrapTabs": true,
  "window.zoomLevel": 2,
  "editor.linkedEditing": true,
  "indentRainbow.colors": [
    "rgba(255, 214, 255, 0.07)",
    "rgba(231, 198, 255, 0.07)",
    "rgba(200, 182, 255, 0.07)",
    "rgba(184, 192, 255, 0.07)"
  ]
}
```

### 3. Cài đặt các Chrome Extensions cần thiết

- React Dev Tool (cho các bài giảng tương lai): https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi

- VisBug: https://chrome.google.com/webstore/detail/visbug/cdockenadnadldjbbgcallicgledbeoc

- WhatFont: https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm

- Colorpicker Eyedropper: https://chrome.google.com/webstore/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg

### 4. Tạo tài khoản Figma

Trong tương lai, mình sẽ phải thực hành bằng việc code giao diện theo thiết kế. Để làm được điều đó, ta sẽ cần phải có tài khoản Figma để xem thiết kế và thực hành code theo.
