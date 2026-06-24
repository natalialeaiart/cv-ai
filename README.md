# cv-ai — Natalja Levaskovica · AI Visual Content Creator

A clean, print-ready HTML CV with lilac accent palette. No frameworks, no dependencies.

## Files

```
cv-ai/
├── index.html   — CV page (open in browser or deploy to GitHub Pages)
├── photo.jpg    — profile photo (keep this filename — referenced in index.html)
├── cv.pdf       — PDF version for the Download button
└── README.md
```

## How to update

Open `index.html` in any text editor. All styles are in the `<style>` block at the top (CSS variables make recoloring easy — just change `--accent`).

To regenerate the PDF after edits:
1. Deploy the updated files to GitHub Pages
2. Open the live page in Chrome
3. `Ctrl+P` - Save as PDF - A4 - Margins: Default - Headers/footers: OFF
4. Save as `cv.pdf` and upload to this repo

## Deploy to GitHub Pages

1. Upload all files to this repository
2. Go to **Settings -> Pages**
3. Source: **Deploy from a branch** -> `main` -> `/ (root)`
4. Live at: `https://natalialeaiart.github.io/cv-ai`

## Adapting for different roles

Each role variant = duplicate `index.html` and edit:
- `.job-title` - target position
- `.summary` - reframe for the role
- `.expertise-card` blocks - reorder or remove
- `.tool-chip` spans - trim to relevant tools

Example: `index-video.html`, `index-automation.html`, `index-hr-ai.html`

---

*Last updated June 2026*
