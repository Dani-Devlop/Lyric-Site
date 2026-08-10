# 🎵 Lyric-Site

**A beautifully styled, responsive lyric display page for *Marino – Lust (feat. Alexandria)***

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)](https://dani-devlop.github.io/Lyric-Site/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📖 Overview

**Lyric-Site** is a minimalist, single-page web application designed to present song lyrics in an elegant, immersive format. Built with pure HTML and CSS, it focuses on delivering a clean typographic experience with subtle visual enhancements—making the lyrics the star of the page.

The page features the full lyrics to *Marino – Lust (feat. Alexandria)*, formatted with clear section headers (Chorus, Verse, Bridge, Outro) and a stylized album cover placeholder.

---

## ✨ Features

- **🎨 Sleek Dark Theme** – A black background with subtle gradients and accents creates a moody, music-focused atmosphere.
- **📱 Fully Responsive** – Adapts seamlessly to desktop, tablet, and mobile viewports (see responsive CSS breakpoints).
- **🎯 Lyric-First Design** – Clean typography with proper spacing, scrollable lyric container, and highlighted section titles.
- **🖼️ Visual Album Art** – Includes a styled image placeholder with a red glow shadow effect.
- **⚡ Lightweight & Fast** – Zero JavaScript, no external dependencies—just HTML and vanilla CSS.
- **🚀 GitHub Pages Ready** – Configured with a GitHub Actions workflow for automatic deployment.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Styling, theming, and responsive design |
| **GitHub Actions** | CI/CD for automatic deployment to GitHub Pages |

---

## 📂 Project Structure

```
Lyric-Site/
├── index.html                 # Main entry point (lyrics page)
├── Index.html                 # Duplicate/backup entry (same content)
├── Static/
│   ├── Css/
│   │   ├── Style.css          # Primary stylesheet (dark theme, scrollbar styling)
│   │   ├── Style-Clone.css    # Responsive test styles (various background colors per breakpoint)
│   │   └── Syle-Clone2.css    # Refined theme (pre-wrap whitespace, styled scrollbar)
│   └── Image/
│       └── .gitkeep           # Placeholder for album cover image
├── .github/
│   └── workflows/
│       └── static.yml         # GitHub Actions workflow for Pages deployment
└── README.md                  # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server for development

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dani-Devlop/Lyric-Site.git
   cd Lyric-Site
   ```

2. **Open the page**
   - Simply open `index.html` in your browser, or
   - Use a local development server (e.g., VS Code Live Server, Python `http.server`)

3. **Make changes**
   - Edit `index.html` to update lyrics or structure.
   - Modify `Static/Css/Style.css` to adjust styling.
   - Add your album cover image to `Static/Image/` and update the `<img>` `src` attribute in `index.html`.

---

## 🎨 Styling Highlights

| CSS Variable | Value | Description |
|--------------|-------|-------------|
| `--background-color` | `black` | Primary background |
| `--text-color` | `oklch(0.85 0 0)` | Light gray text for readability |
| `--Border-color` | `rgba(196, 127, 127, 0.74)` | Soft red border accents |
| `--Cover-Shadow-Color` | `rgba(255, 0, 0, 0.74)` | Red glow shadow for album art |
| `--Scroll-Color` | `#db1520` | Custom scrollbar thumb color |

The design uses:
- **Radial gradients** for subtle depth on the title.
- **Custom scrollbars** for a polished look.
- **Flexbox** for centering and layout control.

---

## 📱 Responsive Design

The page includes responsive breakpoints (primarily in `Style-Clone.css`) for testing across device sizes:

| Breakpoint | Target Devices |
|------------|----------------|
| `max-width: 600px` (landscape) | Small phones in landscape |
| `max-width: 600px` (portrait) | Small phones in portrait |
| `min-width: 601px` | Tablets and small desktops |
| `min-width: 768px` | Medium screens |
| `min-width: 992px` | Large screens |

> **Note:** `Style.css` is the primary active stylesheet. The clone files serve as experimental/backup variants.

---

## 🚢 Deployment

This project is configured for automatic deployment to **GitHub Pages** via GitHub Actions.

### How it works:

1. **Push** to the `main` branch.
2. **GitHub Actions** triggers the `static.yml` workflow.
3. The workflow:
   - Checks out the repository.
   - Configures GitHub Pages.
   - Uploads the entire repository as an artifact.
   - Deploys to the `gh-pages` environment.

### Manual Deployment

You can also deploy manually by enabling GitHub Pages in your repository settings and selecting the `main` branch as the source.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/amazing-improvement`).
3. Commit your changes (`git commit -m 'Add some amazing feature'`).
4. Push to the branch (`git push origin feature/amazing-improvement`).
5. Open a Pull Request.

---

## 📄 License

This project is open-source and available under the **MIT License**.

---

## 🙏 Acknowledgments

- **Marino & Alexandria** – For the powerful lyrics that inspired this project.
- **GitHub Pages** – For free and easy static hosting.

---

## 📬 Contact

**Developer:** Dani-Devlop  
**GitHub:** [@Dani-Devlop](https://github.com/Dani-Devlop)

---

*Made with ❤️ for the love of music and code.*