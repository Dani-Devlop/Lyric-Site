# 🎵 Lyric-Site

> A beautifully styled, responsive lyric display page for *Marino – Lust (feat. Alexandria)*

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-brightgreen)](https://dani-devlop.github.io/Lyric-Site/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/Dani-Devlop/Lyric-Site/blob/main/LICENCE)

---

## 📸 Website Preview

<p align="center">
  <img src="assets/screenshot.png" alt="Lyric-Site Preview" width="700">
</p>

> *Replace `assets/screenshot.png` with an actual screenshot of your live site.*

---

## 📖 Overview

**Lyric-Site** is a minimalist, single-page web application designed to present song lyrics in an elegant, immersive format. Built with pure HTML and CSS, it focuses on delivering a clean typographic experience with subtle visual enhancements—making the lyrics the star of the page.

The page features the full lyrics to *Marino – Lust (feat. Alexandria)*, formatted with clear section headers (Chorus, Verse, Bridge, Outro) and a stylized album cover placeholder.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **Sleek Dark Theme** | Black background with subtle gradients and accents creates a moody, music-focused atmosphere. |
| 📱 **Fully Responsive** | Adapts seamlessly to desktop, tablet, and mobile viewports. |
| 🎯 **Lyric-First Design** | Clean typography with proper spacing, scrollable lyric container, and highlighted section titles. |
| 🖼️ **Visual Album Art** | Styled image placeholder with a red glow shadow effect. |
| ⚡ **Lightweight & Fast** | Zero JavaScript, no external dependencies—just HTML and vanilla CSS. |
| 🚀 **GitHub Pages Ready** | Configured with a GitHub Actions workflow for automatic deployment. |

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
├── Static/
│   ├── Css/
│   │   └── Style.css          # Primary stylesheet
│   └── Image/
│       └── cover.jpg          # Album cover image
├── .github/
│   └── workflows/
│       └── static.yml         # GitHub Actions workflow
└── README.md                  # Project documentation
```

> **Note:** The backup `Index.html` and clone CSS files (`Style-Clone.css`, `Syle-Clone2.css`) have been removed for clarity. They are not used in the live deployment.

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

The page includes responsive breakpoints to ensure optimal viewing across all devices:

| Breakpoint | Target Devices |
|------------|----------------|
| `max-width: 600px` | Small phones |
| `min-width: 601px` | Tablets and small desktops |
| `min-width: 992px` | Large screens |

---

## 🚢 Deployment

This project is configured for automatic deployment to **GitHub Pages** via GitHub Actions.

### How it works:

1. **Push** to the `main` branch.
2. **GitHub Actions** triggers the `static.yml` workflow.
3. The workflow checks out the repository, configures GitHub Pages, and deploys the site.

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

This project is open-source and available under the [MIT License](https://github.com/Dani-Devlop/Lyric-Site/blob/main/LICENCE).

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
