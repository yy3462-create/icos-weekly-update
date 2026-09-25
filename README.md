# ICOS weekly update · 24 Sep 2026

Interactive weekly update for the ICOS modular legged robot. Open `index.html` (or the GitHub Pages link) in a browser; it has three tabs:

1. **Printed dock · video**: the first PLA print of the quick-release dock (root block + receiver), fitted by hand.
2. **Latch assembly · animation** (`assembly.html`): step-by-step assembly of the Southco draw latches on the printed parts, docking, latching and release.
3. **Leg CAD V70 · 3D** (`leg.html`): the latest leg CAD next to GPT’s V69, with the list of fixes, joint sliders, leg removal, sections and exploded view.

Everything is static HTML. The 3D views use three.js r128 (`vendor/three.r128.min.js`, MIT licence); the video is H.264 MP4, 1080p, 5.4 MB.

## Publish with GitHub Pages

1. Create a new repository on github.com (for example `icos-weekly-update`). GitHub Pages on a free account needs the repository to be **public**.
2. *Add file → Upload files*, drag in everything in this folder (keep the `media` and `vendor` subfolders), then *Commit changes*.
3. *Settings → Pages → Build and deployment*: Source **Deploy from a branch**, branch **main**, folder **/ (root)**, *Save*.
4. After about a minute the site is at `https://<your-username>.github.io/icos-weekly-update/`.

To view it without GitHub, open `index.html` directly; the 3D pages also work offline.
