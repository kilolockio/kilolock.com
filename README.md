# kilolockwebsite

Static landing page for `kilolock.com`.

GitHub Pages in this repository publishes from `docs/`, so the deployable site files are mirrored there.

## Contents

- `index.html` - root copy of the landing page source
- `styles.css` - root copy of the site styles
- `assets/` - root copy of favicon and KiloLock icon assets
- `docs/` - GitHub Pages publish directory
- `CNAME` - custom domain source file

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In repository settings, enable GitHub Pages from the `docs/` folder on the default branch.
3. Make sure the `kilolock.com` DNS records point to GitHub Pages.

## Notes

The page is intentionally simple and dependency-free so it can be hosted directly as a static site.
The `docs/.nojekyll` file is included so GitHub Pages serves the files as plain static assets without a Jekyll build step.
