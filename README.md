<div align="center">

# 🌌 Nexus AI
### Advanced Neural Voice Processing Hub

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Speech API](https://img.shields.io/badge/Web_Speech_API-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API)

*An immersive, high-performance web application designed to seamlessly bridge the gap between text and voice using modern browser APIs and a premium "Neon Cyberpunk" UI.*

[Live Demo](https://kajal121343.github.io/textvoice/) 

</div>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features](#-key-features)
- [Tech Stack](#-tech-stack)
- [UI/UX Design System](#-uiux-design-system)
- [Getting Started](#-getting-started)
- [Browser Compatibility](#-browser-compatibility)
- [License](#-license)

---

## 🚀 About the Project

**Nexus AI** is a fully responsive, client-side web application that provides two core utilities:
1. **Text-to-Speech (TTS):** Converts written text into natural-sounding audio.
2. **Speech-to-Text (STT):** Transcribes live microphone input into written text.

Unlike traditional utility apps, Nexus AI is built with a **dark-mode, neon-accented, glassmorphic interface**. It requires zero backend servers, relying entirely on the native **Web Speech API** built into modern browsers, ensuring complete privacy and ultra-low latency.

---

## ✨ Key Features

*   **🎙️ Real-Time Voice Recognition:** Utilizes `SpeechRecognition` with `interimResults` to transcribe your voice as you speak.
*   **🔊 Dynamic Text-to-Speech:** Uses `SpeechSynthesis` to read text aloud with adjustable browser voices.
*   **💎 Premium Glassmorphism UI:** Frosted glass cards, animated gradient backgrounds, and floating glowing orbs.
*   **⚡ Interactive Micro-Interactions:** 
    *   Buttons have a "shimmer" hover effect.
    *   The microphone button pulses with a red heartbeat animation while actively listening.
    *   Cards feature 3D scaling on hover.
*   **📱 100% Responsive:** Fluid typography and Flexbox layouts ensure the app looks flawless on mobile, tablet, and 4K monitors.
*   **🔒 Privacy First:** All voice processing happens via the browser. No audio or text data is ever sent to an external database.

---

## 🛠️ Tech Stack

This project was built from scratch without any heavy frameworks (like React or Bootstrap), proving that pure, vanilla web technologies can create stunning results.

*   **Frontend Structure:** HTML5 (Semantic tags)
*   **Styling & Animation:** CSS3 (Flexbox, CSS Variables, `@keyframes`, `backdrop-filter`, custom scrollbars, and neon `box-shadow` glows).
*   **Logic:** Vanilla JavaScript (ES6)
*   **Core APIs:** 
    *   `window.SpeechSynthesis` (Text to Voice)
    *   `window.SpeechRecognition` / `webkitSpeechRecognition` (Voice to Text)

---

## 🎨 UI/UX Design System

The application uses two distinct color palettes to differentiate the tools:
*   **Text-to-Speech:** Uses a **Cyan/Blue** neon glow (`#00f2fe`).
*   **Speech-to-Text:** Uses a **Pink/Red** neon glow (`#ff416c`).
*   **Backgrounds:** Animated CSS gradients (`linear-gradient` shifting over 15s) accompanied by heavily blurred (`filter: blur(80px)`) floating background orbs.

---

## 💻 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
You do not need Node.js or any package managers. You only need a modern web browser and a code editor (like VS Code).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Kajal121343/textvoice.git