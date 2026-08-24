# 🚀 Icon Resizer

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Pure JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Client-Side Processing](https://img.shields.io/badge/Privacy-100%25%20Client--Side-orange.svg)](#-privacy--security)

> **Icon Resizer Pro** is an ultra-fast, client-side web application built with a modern **iOS 18 Liquid Glass (Glassmorphism)** UI design. It allows mobile app developers, web creators, and UI/UX designers to convert a single master icon into all standard icon assets for **Flutter, Android Native, iOS (Xcode), Web/PWA, macOS, and Windows** with a single click.

---

## ✨ Features

- **🎨 Modern iOS Liquid Glass UI**: Designed with glassmorphism effects, dynamic glow animations, crisp blur backdrops, and responsive controls.
- **🌐 Multi-Language Support (i18n)**: Instant, real-time language switching between **English (LTR)** and **Persian / فارسی (RTL)**.
- **⚡ 100% Client-Side & Private**: All image processing and Canvas operations happen directly inside your browser. No images are uploaded to external servers.
- **📁 Automated ZIP Directory Structuring**:
  - **Flutter**: Ready-to-use directory paths (`android/app/src/main/res/`, `ios/Runner/Assets.xcassets/`, `web/icons/`).
  - **Android Native**: Auto-populated `mipmap-hdpi`, `xhdpi`, `xxhdpi`, `xxxhdpi`, and `playstore-icon.png` (512x512).
  - **iOS / Xcode**: `AppIcon.appiconset` with all scaling requirements (`@1x`, `@2x`, `@3x`) for iPhone, iPad, and App Store Marketing, including an auto-generated `Contents.json`.
  - **Web & PWA**: Favicons (`16x16`, `32x32`), `apple-touch-icon.png` (180x180), Android Chrome icons, and an auto-generated `site.webmanifest`.
  - **Desktop (macOS & Windows)**: Standard square resolution sizes from `16x16` up to `1024x1024`.
- **🖼 Drag & Drop Support**: Instant file handling for PNG, SVG, WEBP, and JPEG images.
- **🔍 High-Quality Resampling**: Utilizes HTML5 Canvas high-quality smoothing for clear, sharp icon scaling.

---

## 🛠 Tech Stack

- **HTML5 & CSS3**: Custom CSS variables, CSS Backdrop-Filter, keyframe ambient animations, and responsive CSS Grid/Flex layout.
- **JavaScript (ES6+)**: Async/Await workflow, Canvas 2D API for high-resolution resampling, FileReader API, and Blob handling.
- **[JSZip](https://stuk.github.io/jszip/)**: Client-side ZIP file generation and packaging.

---

## 🚀 Live Demo & Quick Start

Because **Icon Resizer Pro** is built as a single-page standalone web tool, no complex build process or server installation is required.

### Quick Start (Local Setup)

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/icon-resizer-pro.git](https://github.com/your-username/icon-resizer-pro.git)
