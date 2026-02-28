# GetGems | Premium NFT Marketplace Landing Page

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tech: HTML/CSS/JS](https://img.shields.io/badge/Tech-Vanilla_JS-blue.svg)]()
[![Animation: GSAP](https://img.shields.io/badge/Animation-GSAP_3-green.svg)]()

A high-performance, visually stunning Web3 landing page for the GetGems NFT marketplace. This project is specifically architected for **Android WebView encapsulation**, ensuring 60 FPS animations and native-like touch interactions.

## 🚀 Key Features

- **Advanced GSAP Animations:** Orchestrated entry sequences, scroll-triggered reveals, and smooth parallax effects.
- **WebView Optimization:** Pure "Transform & Opacity" animations to ensure GPU acceleration and prevent reflow/layout shifts on mobile devices.
- **Glassmorphism UI:** Modern dark-themed design with vibrant neon accents and blurred overlays.
- **Custom SplitText Logic:** Lightweight, open-source implementation for character-by-character text animations without premium dependencies.
- **Magnetic Interactions:** Interactive UI elements that react to pointer and touch movements.

## 🛠 Tech Stack

- **Core:** Semantic HTML5, Vanilla CSS3 (Custom Properties), JavaScript (ES6+).
- **Animation Engine:** [GSAP 3](https://gsap.com/) (GreenSock Animation Platform).
- **Plugins:** ScrollTrigger, Observer (for touch normalization).
- **Tooling:** Browser-sync for rapid development and real-time preview.

## 🏗 Architecture & Performance

The project follows a "Performance First" approach, critical for mobile WebView environments:
- **GPU Compositing:** Uses `will-change: transform, opacity` for optimized layer rendering.
- **Event Normalization:** Implements GSAP's `Observer` to handle complex touch/swipe behaviors consistently across Android/iOS devices.
- **Zero Framework Bloat:** No React/Vue overhead – just pure, fast-parsing code for immediate "Largest Contentful Paint" (LCP).

## 📦 Getting Started

To run this project locally, ensure you have [Node.js](https://nodejs.org/) installed, then follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/getgems-nft-landing.git
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
