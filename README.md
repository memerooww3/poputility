# ⚡ PopUtility v2.0 — Everyday Micro Tools

> **100% Client-Side, Private, & Offline-First Utilities Powered by Astro.js**

![PopUtility Banner](public/favicon.svg)

PopUtility is a modern, neo-brutalist suite of essential everyday browser tools designed to work entirely on the client side. No server uploads, zero API latency, and complete user privacy.

---

## 🛠️ Included Tools

### 1. 📸 Photo Resizer & Format Converter
- **Government Exam & Official Presets:** One-click presets for UPSC / SSC passport photos ($3.5 \times 4.5\text{ cm}$, $20\text{KB} - 50\text{KB}$) and official signature crops ($10\text{KB} - 20\text{KB}$).
- **Modern Formats:** Instant client-side conversion from WebP, PNG, JPG, and iPhone HEIC.
- **Client-Side Compression:** Custom target KB slider with intelligent JPEG compression algorithms.

### 2. 🎙️ Voice Summarizer & Audio Transcriber
- **Universal Format Support:** Accepts `.mp3`, `.wav`, `.m4a`, `.aac`, `.ogg`, `.opus`, `.amr`, and `.flac`.
- **Audio Waveform Canvas:** Real-time visual audio waveform generation and playback controls.
- **Instant Takeaway Generation:** Smart offline extraction of core bullet points and takeaways.
- **Interactive Transcript Editor:** Fully editable transcript box with one-click copy and `.txt` file export.
- **Sample Audio:** Includes a built-in sample audio generator to test features immediately.

### 3. 🛡️ Privacy Redactor & ID Shield
- **1-Click Auto Face Blur:** Instantly identifies face zones on IDs and documents and applies high-density Gaussian pixelation.
- **Freehand Drag-to-Blur:** Click or touch-drag over sensitive areas (Aadhaar / ID numbers, phone numbers, signatures).
- **Mask Styles:** Toggle between Gaussian Blur and Deep Blackout Redaction.
- **Undo History:** Step-by-step undo stack with keyboard shortcuts.

---

## 🎨 Design Philosophy
- **Neo-Brutalist Sticker Aesthetic:** High-contrast borders, bold drop shadows, and responsive pill-based navigation.
- **Responsive Architecture:** Customized layout for mobile screens (stacked privacy badge, full-width 3-column sticker tabs) and spacious desktop interfaces.
- **Neutral Dark Mode:** Clean charcoal and deep ink dark theme with persistent state in `localStorage` and zero blue glare.

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18.14.1 or higher)
- npm or pnpm

### Installation

```bash
# Clone the repository
git clone https://github.com/memerooww3/poputility.git

# Navigate into the project folder
cd poputility

# Install dependencies
npm install
```

### Development Server

```bash
npm run dev
```
The local server will start at `http://localhost:4321/` and be accessible across your local network.

### Production Build

```bash
npm run build
```
Builds the static output to the `dist/` directory, ready to deploy instantly to **Vercel**, **Cloudflare Pages**, **Netlify**, or **GitHub Pages**.

---

## 🌐 Deploy to Vercel

PopUtility is pre-configured for zero-configuration deployment on Vercel:
1. Push this repository to GitHub.
2. Go to [Vercel](https://vercel.com) and import the repository.
3. Framework Preset will be automatically detected as **Astro**.
4. Click **Deploy**!

---

## 📄 License
MIT License. Built with ❤️ for privacy and productivity.
