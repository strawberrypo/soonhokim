# Personal Website (Quarto)

## Prerequisite
- Quarto CLI installed

## Local build
- `quarto check`
- `quarto render`

## Publishing concept
- GitHub Actions renders the site from `main`.
- The rendered HTML is published to GitHub Pages via the `gh-pages` branch.
- Built artifacts are not committed to `main`.
