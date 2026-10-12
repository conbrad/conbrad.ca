# conbrad.ca

Personal site — a collection of technical notes on machine learning and data science.

Built with [Quarto](https://quarto.org/), deployed to [GitHub Pages](https://pages.github.com/) via the `docs/` output directory. Domain `conbrad.ca` is managed by Cloudflare DNS.

## Install

```bash
brew install quarto
```

## Build

```bash
quarto render
```

Generates the site into `docs/`.

## Deploy

```bash
git add -A
git commit -m "Update site"
git push origin main
```

GitHub Pages auto-deploys from `docs/` on every push to `main`. The live site updates within a minute or two.

## Preview locally

```bash
quarto preview
```

Starts a local server (usually `http://localhost:4320`) with live reload — edit and refresh to see changes before committing.
