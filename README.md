# Blanker

Paste a doc, blank out words/letters by percentage, copy or download. Pure static HTML, no build step.

## Deploy on GitHub Pages

**Option A: branch deploy (simplest)**
1. Create a repo, add `index.html` at the root, push to `main`.
2. Repo > Settings > Pages > Source: *Deploy from a branch* > `main` / `(root)` > Save.
3. Live at `https://<username>.github.io/<repo>/` in ~1 min.

**Option B: GitHub Actions**
1. Keep `.github/workflows/pages.yml` in the repo.
2. Settings > Pages > Source: *GitHub Actions*.
3. Push to `main`; it deploys automatically.
