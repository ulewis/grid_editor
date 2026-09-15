# GRID_EDITOR

A professional, privacy-first XML Grid Editor that runs entirely in the browser.

## Highlights

- Auto-detect repeated XML structures and turn them into editable tables
- Spreadsheet-style grid editing with sorting, filtering, pagination, row selection, duplication, deletion, and field creation
- Synchronized Tree, Inspector, Source, XPath, XSD Validation, and Diff workspaces
- XPath 3.1 through FontoXPath when available, with native browser XPath fallback
- XSD validation in-browser through libxml2 WebAssembly
- File System Access support for direct Open/Save where the browser allows it, with standard upload/download fallback
- Local-only processing: XML files are not uploaded to an application server
- Dark/light interface, PWA support, keyboard shortcuts, undo/redo, drag-and-drop, and responsive layout
- Dependency-free core UI; advanced XPath/XSD engines are loaded on demand

## Run locally

No build step is required. Serve the repository as static files with any local web server, or simply use the deployed GitHub Pages site.

For example:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

GitHub Pages deployment is configured in `.github/workflows/pages.yml`. The repository's Pages publishing source must be set to **GitHub Actions** once under **Settings → Pages → Build and deployment → Source**.

## Privacy

The core XML editing workflow runs locally in the browser. GRID_EDITOR does not include a backend, user accounts, or an XML upload API.
