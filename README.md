# 🎨 Interactive Glassmorphic Developer Portfolio

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Deployment](https://img.shields.io/badge/Deployed_on-GitHub_Pages-black?logo=github)](https://pages.github.com/)

A modern, high-end, responsive personal portfolio website designed for **Justin Joe Mathew**, a Computer Science Engineering student. Rebuilt from a standard static template into a premium dark glassmorphic developer-themed workspace.

---

## ✨ Features & Interactive Elements

*   🌌 **Cyber-Obsidian Theme**: Deep black obsidian canvas integrated with moving radial neon gradient glows (violet and coral) and high-tech vector grids.
*   💻 **IDE Profile Terminal**: The traditional "About" section is styled as an interactive VS Code code window, presenting biography data in syntax-highlighted JSON code structures.
*   🌀 **Fluid SVG Morphing**: A hardware-accelerated SVG backdrop blob morphs dynamically using native SMIL `<animate>` tags, creating a smooth backdrop without relying on heavy external scripts or frameworks.
*   ✍️ **Cycling Typewriter**: Vanilla JavaScript typing engine that prints, pauses, deletes, and cycles through developer roles with a custom blinking cursor.
*   📊 **Circular Progress Dials**: Upgraded skills progress bars into glowing radial SVG progress indicators with numeric text percentages.
*   📱 **Responsive Mobile Menu**: Fully responsive slider menu triggered by an animated hamburger toggle.
*   ✉️ **Frosted Contact Form**: Glassmorphic form inputs with radial glow shadows upon hover and active focus.

---

## 📁 Repository Directory Structure

```text
portfolio/
├── images/
│   ├── bg.jpg              # High-resolution hero background
│   └── gallery/
│       ├── image1.jpg      # Piano performance photograph
│       ├── image2.jpg      # Landscape/Nature photography
│       └── image3.jpg      # Photoshop creative manipulation art
├── index.html              # Core single-page template (HTML5, styled CSS, and JS)
└── README.md               # Project documentation
```

---

## 🛠️ Local Execution

This portfolio is written in vanilla HTML, CSS, and JS with zero build dependencies, meaning you can run it instantly:

1. Clone the repository:
   ```bash
   git clone https://github.com/jvstin47/001.git
   ```
2. Double-click `index.html` or open it with any modern browser.
3. Alternatively, serve it locally with Python or Node:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (Live Server)
   npx live-server
   ```

---

## 🌐 Deploying to GitHub Pages

To host this portfolio for free using GitHub Pages:

1. Create a repository on GitHub (e.g. named `portfolio`).
2. Go to **Settings** -> **Pages** in your repository sidebar.
3. Under **Build and deployment**, select **Deploy from a branch** and set the branch to `main` (folder `/root`).
4. Click **Save**. Your site will be published at `https://jvstin47.github.io/portfolio/`.
