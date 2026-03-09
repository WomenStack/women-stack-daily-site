# Women Stack Daily Site

Static site for publishing `Women Stack Daily` via GitHub Pages.

## Structure

```text
.
├── index.html
├── daily/
│   └── 2026-03-08.html
├── data/
│   └── recent.json
└── README.md
```

## Publishing Model

- Put each daily issue at `daily/YYYY-MM-DD.html`.
- Keep `index.html` pointed at the latest issue.
- Update `data/recent.json` with recent issue metadata for homepage generation.
- Publish the repo directly with GitHub Pages. No extra server is required.

## Current Seed Content

- Latest issue: `2026-03-08`
- Source copied from the existing Women Stack workflow output in the old repo

## Next Step

- Replace the temporary iframe embed in `index.html` with a generated inline embed from the reader HTML.
- Add a publish script in the old repo to copy daily pages, refresh `recent.json`, and regenerate `index.html`.
