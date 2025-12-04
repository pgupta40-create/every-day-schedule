# Every Day Schedule

A minimal, static starting point for a personal scheduling web app. This repo contains a single responsive HTML file (`index.html`) with embedded styles and a small visual flourish (animated background bubbles) so you can preview and iterate quickly.

## Files

- `index.html` — The full static site (HTML + embedded CSS + small JS for decorative bubbles).

## Preview locally

Open a terminal in this folder and run a static file server. For example, with Python 3:

```bash
# macOS / Linux / WSL
python3 -m http.server 8000

# then open http://localhost:8000 in your browser
```

Or, if you prefer Node.js and have `http-server` installed:

```bash
npx http-server -c-1 . 8080
```

## Notes

- The project intentionally keeps styles embedded in `index.html` per current conventions. If you plan to expand the app, consider extracting CSS to a separate `styles.css` and adding a small build toolchain.
- The example schedule is static HTML to make it easy to edit and iterate; replace with dynamic UI or framework of your choice.

Happy hacking! — Every Day Schedule