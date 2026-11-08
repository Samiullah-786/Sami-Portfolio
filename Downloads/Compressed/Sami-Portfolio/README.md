# 🌐 Sami-Portfolio — Interactive 3D Portfolio

Personal portfolio of **Sami Ullah Khan** ([@Samiullah-786](https://github.com/Samiullah-786)) — web developer from Lahore, Pakistan.

![Three.js](https://img.shields.io/badge/Three.js-WebGL-00f0ff) ![Tailwind](https://img.shields.io/badge/Tailwind-CSS-8a2be2) ![Single File](https://img.shields.io/badge/build-single--file-ff007f)

## ✨ Features

- **Wireframe Hologram Portrait** — my GitHub photo rendered as a live 3D wireframe/point-cloud hologram (Wireframe Mode **ON** by default), with scanline, glow rings and drag-to-rotate.
- **3D Hologram Lab** — upload any photo, switch shapes (hologram / torus / cube / sphere), toggle wireframe, change glow color, rotation speed & hologram depth.
- **GitHub-powered content** — profile, repos and language mix embedded from the GitHub API, with a one-click **live refresh**.
- **Real projects** — every project card links to an actual repository.
- **Clean 3-file structure** — `index.html` (markup), `style.css` (styles), `script.js` (logic). No CDN/network needed (Three.js, fonts, photo all embedded). Works offline.

## 📁 File Structure

```
Sami-Portfolio/
├── index.html   → page structure (photo embedded here)
├── style.css    → fonts + Tailwind + custom styles (edit SECTION 3)
├── script.js    → Three.js library + GitHub data + app code (edit SECTION 3)
└── README.md
```

> Open `index.html` in any browser — no build step, no internet required.
- Responsive, reduced-motion friendly, keyboard accessible, SEO meta tags.

## 🚀 Deploy on GitHub Pages

1. Push this folder to the `main` branch of `Samiullah-786/Sami-Portfolio`.
2. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `/ (root)` → Save.
3. Site will be live at: `https://samiullah-786.github.io/Sami-Portfolio/`

## 🛠 Customize

Open `index.html` and search for `CONFIG` near the bottom:

```js
const CONFIG = {
  githubUsername: 'Samiullah-786',
  email: '', // ← add your email to make the contact form use mailto
  typedPhrases: [ ... ]
};
```

---
Built with Three.js, WebGL & Tailwind CSS · © 2026 Sami Ullah Khan
