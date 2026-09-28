# Friends of Ashley Holding Page

The standalone pre-launch holding page for The Friends of Ashley.

It is deliberately separate from the in-progress `foa-website` project so the public domain can show only this page while the full site remains available for development and review at `https://nicholascaplan.github.io/foa-website/`.

## Deployment

Pushes to `main` deploy the static files to GitHub Pages through `.github/workflows/deploy.yml`.

Before publishing publicly, configure `thefriendsofashley.org` as this repository's GitHub Pages custom domain and point its DNS at GitHub Pages. The custom-domain setting belongs in GitHub Pages, not in this repository.
