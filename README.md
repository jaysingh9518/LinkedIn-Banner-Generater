# 🎨 LinkedIn Banner Studio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Demo-blue?style=flat&logo=github)](https://jaysingh9518.github.io/linkedin-banner-generator/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Dimensions](https://img.shields.io/badge/Dimensions-1584%20%C3%97%20396%20px-informational)](#-specifications)

A fast, client-side interactive tool to generate custom, pixel-perfect LinkedIn profile banners with real-time preview, portrait positioning sliders, customizable themes (with **Light Mode as default** and **Dark Mode** toggle), and 1-click high-resolution PNG export.

Designed specifically to match modern corporate identities and executive aesthetics[cite: 1, 3].

---

## 🌟 Key Highlights

- **Exact Aspect Ratio:** Renders at LinkedIn's official banner specification of **1584 × 396 px (4:1)** so your profile looks sharp on desktop, tablet, and mobile.
- **Light & Dark Mode UI:**
  - **Light mode by default** for a clean workspace.
  - Quick-switch toggle button that persists preference via `localStorage`.
- **Photo Positioning Controls:**
  - File uploader supporting PNG, JPG, and WebP headshots.
  - Zoom / scaling slider (0.5x to 2.5x).
  - Horizontal ($X$) and vertical ($Y$) translation sliders to frame your portrait.
- **Live Text & Contact Editor:** Real-time updates for Company Name, Full Name, Designation, Bio/Tagline, Phone, and LinkedIn Profile URL.
- **1-Click High-Res PNG Download:** High-fidelity rasterization using the native HTML5 Canvas API without compression artifacts.
- **Zero Dependencies:** Pure HTML5, CSS3 variables, and vanilla JavaScript. No Node.js build pipelines or backend required.

---

## 📐 Specifications

| Property | Value |
| :--- | :--- |
| **Output Canvas Width** | `1584 px` |
| **Output Canvas Height** | `396 px` |
| **Aspect Ratio** | `4 : 1` |
| **Export Format** | `image/png` (32-bit RGBA) |
| **Default Interface Theme** | `Light Mode` |

---

## 🚀 Quick Start

### Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/jaysingh9518/linkedin-banner-generator.git](https://github.com/jaysingh9518/linkedin-banner-generator.git)
   ```
2. Open the directory:
   ```bash
   cd linkedin-banner-generator
   ```
3. Open `index.html` in any modern browser:
   ```bash
   # macOS
   open index.html

   # Windows
   start index.html

   # Linux
   xdg-open index.html
   ```

### Deploy to GitHub Pages
1. Push your repository to GitHub.
2. Ensure the empty `.nojekyll` file exists in your root folder to disable Jekyll build filtering.
3. In your GitHub repository: Go to **Settings** $\rightarrow$ **Pages**.
4. Under **Branch**, select `main` and root `/`, then click **Save**.
5. Your application will be live at `https://<username>.github.io/<repo-name>/`.

---

## 📂 Project Structure

```text
linkedin-banner-generator/
├── .github/
│   └── workflows/
│       └── deploy.yml      # (Optional) Automated GitHub Actions deployment
├── .nojekyll               # Bypasses Jekyll processing on GitHub Pages
├── index.html              # Main application with embedded light/dark UI & canvas engine
├── LICENSE                 # MIT License
└── README.md               # Project documentation
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).