# Adarsh Koshiya — Personal Portfolio Website

[![Live Site](https://img.shields.io/badge/Live%20Site-adarsh--koshiya.github.io-blue?style=flat-square)](https://adarsh-koshiya.github.io/)
![Languages](https://img.shields.io/badge/HTML%2045.9%25%20%7C%20CSS%2050.5%25%20%7C%20PHP%203.6%25-informational?style=flat-square)

A personal academic portfolio and research website, hosted via GitHub Pages. The site showcases research interests, work experience, projects, honors, and courses — designed in the style of [Jon Barron's academic website template](https://github.com/jonbarron/jonbarron_website).

🔗 **Live:** [https://adarsh-koshiya.github.io/](https://adarsh-koshiya.github.io/)

---

## About

This is the source code for the personal portfolio of **Adarsh Koshiya**, a Master's student in Artificial Intelligence for Industrial Applications at [Ostbayerische Technische Hochschule Amberg-Weiden (OTH-AW)](https://www.oth-aw.de/en/), Germany.

**Research Keywords:** AI safety · multi-agent systems · AI governance · (multi-agent) reinforcement learning · cooperative AI

---

## Features

- Academic bio and research motivation
- Work experience timeline (Software Engineer, Developer Intern)
- Project showcase with links to code, posters, and documentation
- Honors, scholarships, and completed certifications
- Responsive single-page layout

---

## Projects Highlighted

| Project | Description |
|---|---|
| **NLP: Image-to-Text Dataset for Quantum Circuits** | Automated Python pipeline extracting quantum circuit images from arXiv with NLP-based text-figure alignment |
| **Sensor Fusion for IMU/BLE Indoor Localization** | Particle Filter-based indoor localization fusing IMU and BLE data; visualized with Pygame |
| **Plant Disease Classification with XAI** | MobileNetV2 + Grad-CAM binary classifier deployed on Raspberry Pi |
| **Stock Data Analysis & Prediction** | Time-series forecasting (ARMA/ARIMA) on AAPL stock data using Python |

---

## Tech Stack

- **HTML5** — page structure and content
- **CSS3** — styling and layout (`stylesheet.css`)
- **PHP** — contact form handling (`/forms`)
- **Assets** — images, fonts, and downloadable files (posters, PDFs)

---

## Repository Structure

```
.
├── index.html          # Main portfolio page
├── stylesheet.css      # Global styles
├── changelog.txt       # Version history
├── assets/             # Images and media
├── assests/            # Additional assets
├── imgs/               # Profile and project images
├── fonts/              # Custom web fonts
├── files/              # Downloadable files (posters, PDFs)
└── forms/              # PHP contact form handler
```

---

## Local Development

Since this is a static site (HTML/CSS), you can run it locally with any simple HTTP server:

```bash
# Using Python
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

> **Note:** PHP form functionality requires a PHP-enabled server (e.g., XAMPP, WAMP, or a hosting provider with PHP support).

---

## Deployment

This site is deployed automatically via **GitHub Pages** from the `main` branch. Any push to `main` is reflected live at [https://adarsh-koshiya.github.io/](https://adarsh-koshiya.github.io/).

---

## Credits

- Website template adapted from [jonbarron/jonbarron_website](https://github.com/jonbarron/jonbarron_website)

---

## Contact

For academic or professional inquiries, visit the live portfolio site linked above.
