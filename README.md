# Croatian Family Tree Public View

This repository hosts a redacted public copy of the interactive Croatian family tree. It is designed for GitHub Pages at:

https://abundant-pasta.github.io/croatian-geneaology-public/

## What is included

- `index.html` - static interactive family tree page.
- `family_tree_data.json` - redacted chart data used by the page.

## What is intentionally excluded

Raw records, correspondence, request drafts, source screenshots, source notes, maps, packets, and the private research god file are not published here. The private research workspace remains the canonical source of truth.

Likely living or recent family members are represented as private placeholders so relationships can still be understood without exposing personal details.

## Local preview

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```
