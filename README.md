# Hao Hu — personal website

This is the Quarto source for a new academic website.

## Preview locally

```bash
quarto preview
```

## Build

```bash
quarto render
```

The rendered site is written to `_site/`. The included GitHub Actions workflow publishes the site to the `gh-pages` branch after the repository is connected to GitHub and changes are pushed to `main`.

The custom stylesheet uses a versioned filename to avoid stale browser caches. When changing its contents, rename it using the first eight characters of its SHA-256 hash and update `format.html.css` in `_quarto.yml` before rendering.

The custom domain is deliberately not configured yet. Add it only after the GitHub Pages preview has been reviewed and the existing WordPress site has been backed up.
