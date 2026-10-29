# Aikya Sira Kumar: portfolio

Static site (no build step), deployed by GitHub Actions.

## Publish
1. Create a repo named `AikyaKumar.github.io` (gives you `https://aikyakumar.github.io`) or any name (URL gets `/repo-name`).
2. Push this folder to the `main` branch.
3. On GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Each push to `main` redeploys. Check the **Actions** tab.

## Before you push
- Add `assets/resume.pdf` and `assets/photo.jpg` (optional; the photo block hides itself if missing).
- In `index.html`, search for `TODO` and fill in: LinkedIn URL, project links, your own wording.
- Replace the site URL in the `og:url` tag after you know it.

## Preview locally
`python3 -m http.server 8000`, then open http://localhost:8000
