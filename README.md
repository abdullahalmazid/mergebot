# Mergebot 🤖 — Free PDF Merger and Page Picker

Pick any pages from multiple PDFs, put them in any order, and download one merged PDF.
Everything runs in the browser, so files are never uploaded to a server.

**Live demo:** https://YOUR-USERNAME.github.io/mergebot/

## Features

- Upload multiple PDFs (drag and drop or file picker)
- Pick single pages, or add many at once by range (`1 to 50`), list (`1-5, 8, 12-20`), all, odd or even
- Full-size page preview with page jump and swipe on mobile
- Drag to reorder, rotate, duplicate and remove pages
- Preview the merged result before downloading
- Works on desktop and mobile, light and dark mode
- 100% private: no backend, no uploads

## Tech

Plain HTML, CSS and JavaScript in a single file, with:
[PDF.js](https://mozilla.github.io/pdf.js/) (rendering),
[pdf-lib](https://pdf-lib.js.org/) (merging) and
[SortableJS](https://sortablejs.github.io/Sortable/) (drag and drop).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy on GitHub Pages

1. Create a repository named `mergebot` and upload these files.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Your site will be live at `https://YOUR-USERNAME.github.io/mergebot/`.

## Developer

**Abdullah Al Mazid** — Industrial and Production Engineer, BUET
Portfolio: [abdullahalmazid.vercel.app](https://abdullahalmazid.vercel.app)

## License

MIT © 2026 Abdullah Al Mazid
