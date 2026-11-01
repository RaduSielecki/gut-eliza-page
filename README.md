# Gut — Eliza’s page

A GitHub Pages-ready copy of the supplied design export.

## Publish on GitHub Pages

1. Create an empty public repository named `gut-eliza-page`.
2. Upload this folder’s **contents**, so `index.html`, `support.js`, `vendor/`, and `assets/` are at the repository root, and commit to `main`.
3. Open **Settings → Pages**. Choose **Deploy from a branch**, select **main** and **/ (root)**, then save.
4. Wait for the Pages deployment to finish. For the account `RaduSielecki`, the expected URL is `https://radusielecki.github.io/gut-eliza-page/`.

No package installation, build step, or backend is required. `.nojekyll` disables Jekyll processing; include it when pushing with Git.

## Preview locally

Run `python3 -m http.server 8000` in this folder and open `http://localhost:8000/`.

## Export status

This publishes the supplied design as a preview. Its checkout link and video controls are placeholders. Review text, seller details, and disclaimers also contain placeholders. The promotion date is hardcoded to October 31, 2026.

The page uses its bundled React runtime and images, with Google Fonts loaded externally. The original export instructions are retained in `EXPORT-README.md`.

Hosting preparation renamed `Gut.dc.html` to `index.html` and added a mobile viewport meta tag. All other site files are unchanged.
