# Presentations

Reveal.js presentations for CUH Bioinformatics / East Genomics.

## Presentations

- [Contamination Screen](contamination-screen/) — Design, validation, and testing of the pairwise cross-sample contamination detection tool for the Uranus pipeline

## Adding a new presentation

1. Create a new directory at the repo root (e.g. `my-talk/`)
2. Add an `index.html` using `../reveal.js/` paths for all reveal.js resources
3. Copy an existing presentation as a template
4. Commit and push — GitHub Pages will serve it automatically

## Viewing locally

```bash
python3 -m http.server 8000
# Open http://localhost:8000/contamination-screen/
```
