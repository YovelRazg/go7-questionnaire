# GO7 design questionnaire

Static HTML page — airline website design questionnaire with live preview.

**Live site:** https://yovelrazg.github.io/go7-questionnaire/

## Build

No build step. The app is a single static `index.html` (CSS and JavaScript are inline).

## Deployment

Pushes to `main` deploy automatically via [GitHub Pages](.github/workflows/deploy.yml).

| | |
|---|---|
| **Workflow** | `.github/workflows/deploy.yml` |
| **Trigger** | Push to `main` or manual *Run workflow* |
| **Published URL** | `https://yovelrazg.github.io/go7-questionnaire/` |

To enable Pages the first time (if the workflow fails on permissions):

1. Repo → **Settings** → **Pages**
2. **Build and deployment** → Source: **GitHub Actions**

Check deployment status under **Actions** → *Deploy to GitHub Pages*.

## Open locally

Double-click `index.html`, or:

```bash
open index.html
```

Or serve it (optional):

```bash
npx --yes serve .
```

## What it does

- Three-section questionnaire (project, brand, structure)
- Template picker with mini previews
- Submit validates required fields
- **Preview my website** builds a mock homepage from your answers
