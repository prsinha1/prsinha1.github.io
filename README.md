# Priyanka Sinha Academic Website

This repository contains the source for [prsinha1.github.io](https://prsinha1.github.io).

The site uses plain HTML and CSS. GitHub Pages serves the files directly from the repository root, so no build step or package installation is required.

## Local preview

From the repository root, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## Tests

Run the full audit from the repository root:

```bash
python3 -m unittest discover -s tests -v
```

The audit checks page structure, approved content, publication and CV coverage, accessibility features, and internal links.

## Deployment

GitHub Pages publishes the `main` branch for the `prsinha1` account. Changes become public after they are committed and pushed to the repository.
