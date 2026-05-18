# AGENTS.md

## Cursor Cloud specific instructions

This is a static HTML/CSS/JS website with no build tools, package managers, or backend services. The entire site is a single `index.html` file with inline styles and scripts.

### Running the site

Serve the site with any static file server from the repository root:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` in a browser.

### Key notes

- There are no dependencies to install — no `package.json`, `requirements.txt`, or similar.
- There is no build step, linter, or test framework configured.
- The contact form is client-side only (no backend submission).
- External Google Fonts are loaded via CDN; the site falls back to system fonts if unavailable.
- `NBAG index.html` is a duplicate of `index.html`.
