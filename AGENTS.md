# AGENTS.md

## Cursor Cloud specific instructions

This is a static HTML repository containing a commercial proposal one-pager (`index.html`) and business documentation (`docs/`). There is no build system, package manager, test framework, or linting setup.

### Running the site

Serve the page with any static HTTP server:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/index.html` in a browser. The page uses Google Fonts loaded via CDN, so internet access is required for full font rendering.

### Key facts

- **No dependencies to install** — no `package.json`, `requirements.txt`, or similar.
- **No build step** — the HTML file is self-contained with inline CSS and SVG.
- **No tests or linting** — none are configured.
- **`docs/`** contains business strategy documents (markdown and PDF) in Russian/Ukrainian.
