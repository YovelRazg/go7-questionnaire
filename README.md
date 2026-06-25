# GO7 design questionnaire

Static HTML page — airline website design questionnaire with live preview.

## Run locally

```bash
npm install
npm run dev
```

Then open **http://localhost:3000**

| Page | URL |
|------|-----|
| Original questionnaire | http://localhost:3000/ |
| **Questionnaire v2** (Level 1 S package) | http://localhost:3000/questionnaire-v2.html |

Or double-click the HTML files in Finder (no server needed).

**Live (deployed):** https://yovelrazg.github.io/go7-questionnaire/

## Questionnaires

- **index.html** — original full questionnaire (5 templates, tone/mood options)
- **questionnaire-v2.html** — Level 1 (S package): simplified 5-section form, same 5-template picker, same preview simulator

## What it does

- Three-section questionnaire (project, brand, structure)
- Template picker with mini previews
- Submit validates required fields
- **Preview my website** builds a mock homepage from your answers
