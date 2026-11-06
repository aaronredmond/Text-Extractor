# Text Extractor

Extract text from screenshots in your browser using [Tesseract.js](https://github.com/naptha/tesseract.js).
Your image is never uploaded; the OCR engine and language data are downloaded once from a CDN.

## Usage

Open `index.html` in a browser, then upload, drag & drop, or paste (Ctrl/Cmd+V) a screenshot.
No build step or server required.

## Features

- Language selection (English, German, French, Spanish, Italian, Portuguese, Dutch)
- Image enhancement (upscale, grayscale, auto-invert dark themes, contrast stretch)
- Layout modes (code / single block, document, single column)
- Copy to clipboard or download as `.txt`

## Known limitations

OCR is imperfect. Markup symbols such as `**bold**` are often misread as letters, and
look-alike characters (`l`/`1`/`I`, `O`/`0`) can be swapped. Please proofread results.

## Files

- `index.html` – markup
- `styles.css` – styling
- `app.js` – OCR and UI logic
