# Croatian Family Tree Public View

This repository hosts a public copy of the interactive Croatian family tree. It is designed for GitHub Pages at:

https://abundant-pasta.github.io/croatian-geneaology-public/

## What is included

- `index.html` - static interactive family tree page.
- `family_tree_data.json` - public chart data used by the page, with private source paths removed.

## What is intentionally excluded

Raw records, correspondence, request drafts, source screenshots, source notes, maps, and packets are not published here. The private research workspace remains the canonical source of truth.

Source references are shown as private-source placeholders rather than links to unpublished research files.

## Local preview

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```
