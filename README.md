# Split PDF - All to One

A client-side web app that splits a multi-page PDF into individual single-page PDF files and bundles them into a ZIP for easy download.

## Features

- **Client-side only** — no server needed, easy to host on any static hosting (GitHub Pages, Netlify, etc.)
- **Drag & drop** or click to upload a PDF
- Splits every page into its own PDF file
- Downloads all pages as a single **ZIP** file
- Progress indicator while splitting

## How to Use

1. Open `index.html` in a browser (or visit the hosted version)
2. Drag & drop a PDF file or click to browse
3. Click **Split & Download ZIP**
4. A ZIP file containing one PDF per page will be downloaded

## Tech Stack

- [pdf-lib](https://pdf-lib.js.org/) — PDF manipulation in the browser
- [JSZip](https://stuk.github.io/jszip/) — ZIP file generation
- Vanilla HTML, CSS, and JavaScript — no build step required