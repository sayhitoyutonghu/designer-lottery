# Designer Lottery

Interactive scratch-off lottery ticket tool for designers.

**Play it:** https://sayhitoyutonghu.github.io/designer-lottery/ (enable GitHub Pages first, see below)

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy (GitHub Pages)

1. Upload everything in this folder to the repo (drag the whole folder into GitHub's web upload, it preserves the `assets/` structure).
2. Repo Settings → Pages → Source: **Deploy from a branch** → Branch: **main** → **/(root)** → Save.
3. Wait ~1 minute, the site goes live.

## Structure

- `index.html` — the whole tool (markup, styles, logic)
- `assets/` — fonts (`.woff2`) and images (`.jpg`, `.png`) referenced by `index.html`
