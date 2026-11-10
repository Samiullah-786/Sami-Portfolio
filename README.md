# Sami Portfolio — 3D Wireframe Edition

Professional, responsive portfolio for Sami Ullah Khan with a live GitHub section and interactive 3D wireframe portrait.

## Files

- `index.html` — page structure and embedded professional portrait
- `style.css` — embedded fonts, utility styles, and custom styling
- `script.js` — Three.js, GitHub snapshot, hologram and app logic

Keep all three files together. Open `index.html` in a modern browser; no build step or external network is required.

## Portrait

The submitted portrait was professionally styled with a navy suit, white shirt and tie, then used throughout the portfolio, including the cyan wireframe holograms. To use another portrait, replace the image data URI in the `gh-avatar` image `src` in `index.html`; `script.js` reads the same image for the 3D hologram.

## Customize

- `style.css`: search for `SECTION 3: CUSTOM STYLES`.
- `script.js`: search for `SECTION 3: APP CODE` (the minified Three.js library above it is vendor code).
- `index.html`: update visible copy, links, and contact details.

The GitHub profile/repository snapshot is embedded for offline use; use the portfolio's refresh control when online to request current public GitHub information.

## GitHub Pages deployment

1. Push the three files and this README to the `main` branch of `Samiullah-786/Sami-Portfolio`.
2. In the repository, open **Settings → Pages**.
3. Select **Deploy from a branch**, choose **main** and **/ (root)**, then save.
4. The site will appear at `https://samiullah-786.github.io/Sami-Portfolio/` after GitHub Pages finishes deploying.
