# CV (LaTeX → GitHub Pages)

This repo builds `cv.pdf` from `resume.tex` on every push to `main` and publishes it via GitHub Pages.

## Files
- `resume.tex` — source CV
- `index.html` — landing page embedding the PDF
- `.github/workflows/pages.yml` — build + deploy workflow

## Publish
1. Push to `main`
2. GitHub: Settings → Pages → Source: **GitHub Actions**
3. Your CV will appear at: `https://<username>.github.io/<repo>/`

