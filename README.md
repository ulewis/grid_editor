# GRID_EDITOR

A professional, privacy-first XML Grid Editor that runs entirely in the browser.

## Highlights

- Auto-detect repeated XML structures and turn them into editable tables
- Excel-like grid editing with sorting, filtering, ranges, clipboard, row actions, and column movement
- Synchronized Tree, Source, XPath 3.1, XSD Validation, and Diff workspaces
- Real XSD validation in-browser through libxml2 WebAssembly
- XPath 3.1 / XQuery expressions through FontoXPath
- Local-only processing: XML files are not uploaded to a server
- Dark/light interface, PWA support, keyboard shortcuts, undo/redo, and responsive layout

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

GitHub Pages deployment is configured in `.github/workflows/pages.yml`.
