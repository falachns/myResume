# Static Web CV

This is a simple single-page CV website built with plain HTML and CSS.

## Files

- `index.html` - the resume content
- `styles.css` - screen styles
- `print.css` - print and PDF export styles
- `favicon.svg` - browser tab icon
- `README.md` - project notes

## How to Edit

Open `index.html` to edit the CV text, links, SEO meta tags, and Open Graph tags.

Open `styles.css` for screen styling and `print.css` for PDF export styling.

## Preview Locally

Use a local server from this folder:

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Export to PDF

1. Open the page in your browser.
2. Press `Cmd + P` on Mac or `Ctrl + P` on Windows.
3. Choose `Save as PDF`.
4. Use A4 paper size.
5. Turn off browser headers and footers if they appear.

## Deploy to Vercel

This project is ready for Vercel as a static website because `index.html` is in the root folder and there are no build tools.

In Vercel, use these settings:

- Framework Preset: `Other`
- Build Command: leave empty
- Output Directory: leave empty
