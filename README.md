# portfolio-archive

Every earlier version of my portfolio site, oldest to newest, in one place so you can see how my web work has grown.

Open the live archive and use the floating toolbar to switch versions: the arrows (or ← → keys) step through them, the middle button lists all of them, and the chevron hides the toolbar.

| # | Version | When | Built with |
|---|---------|------|-----------|
| 1 | First portfolio | September 2025 | HTML, CSS |
| 2 | React portfolio | October–December 2025 | React, Vite, designed in Figma |

Each site lives untouched in `sites/`, except that resume PDFs are left out and their links point to a short note instead. The React site is the production build (`vite build --base=./`).

## Adding a version

Copy the built site into `sites/<yyyy-mm>-<name>/` and add an entry to the `versions` list in `index.html`.

## Running locally

```sh
python3 -m http.server 8765
```

Then open http://localhost:8765.
