
## Agile software development under ISO 27001

As applied to TSD, at UiO.

## Build

```bash
pandoc \
    -f markdown-implicit_figures \
    --filter pandoc-citeproc \
    --bibliography=paper.bib \
    --variable papersize=a4paper \
    -s paper.md \
    -o paper.pdf
```
