# AJJ 2027 conference website prototype

A lightweight, mobile-first prototype for **AJJ 2027: Shifting Borders**, taking place 12–13 June 2027 at Nanzan University, Nagoya.

## Prototype features

- Home and practical information
- Example two-day program
- Live-style “Now & Next” view with preview times
- Session and abstract pages
- Provisional Q Building room map
- Registration and call-for-papers placeholders
- Accessible, responsive, dependency-free static pages

All schedule entries are clearly marked as examples. Conference data lives in [`data/program.json`](data/program.json), so the program can be updated without editing page templates.

## Local preview

The site uses `fetch()` to load its program data, so serve it through a local web server rather than opening the HTML files directly.

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publishing

The site is published directly from the repository's `main` branch using GitHub Pages. No build step is required.

The custom domain is intentionally not configured in this prototype.
Website for AJJ 2027 Conference at Nanzan University
