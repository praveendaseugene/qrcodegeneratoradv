# QR Code Generator Advanced

A fast, fully client-side QR code generator with rich customization — colors, dot styles, frames, logos, titles, descriptions, and multi-format export. No server, no tracking, no data leaves your browser.

🔗 **Live demo:** [https://praveendaseugene.github.io/qrcodegeneratoradv/](https://praveendaseugene.github.io/qrcodegeneratoradv/)
<img width="625" height="289" alt="image" src="https://github.com/user-attachments/assets/bc462241-98cb-4cc0-80fa-d5eadc8d8399" />


![QR Code Generator Advanced](https://img.shields.io/badge/status-live-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![No backend](https://img.shields.io/badge/backend-none-success)

---

## ✨ Features

### Core
- **Instant generation** — type any text or URL, QR appears live (debounced).
- **Fully client-side** — nothing is uploaded, stored, or tracked. Works offline after first load.
- **Responsive** — usable on mobile, tablet, and desktop.

### Customization
- 🎨 **Colors** — independent foreground & background pickers with hex input, plus 8 quick preset themes (Classic, Ocean, Forest, Sunset, Berry, Mono, Crimson, Midnight).
- 🔷 **Design styles** — Square, Rounded, Dots, Smooth module rendering.
- 🖼️ **Frames** — None, Simple, Rounded, Label, Banner, Speech, Shadow, Double.
- 🖼️ **Logo** — drag & drop or click to upload (PNG/JPG/SVG/WebP, max 4 MB), adjustable size (12–25% of QR), optional background pad.
- 📝 **Title & Description** — optional text below the QR, with **custom title color** and **custom title size**.
- ⚙️ **Advanced** — QR size (200–1000 px), quiet-zone margin (1–10 modules).

### Export
- 📥 **PNG** — lossless, transparent-capable.
- 📥 **JPEG** — flattened on your chosen background color, 95% quality.
- 📥 **SVG** — vector wrapper embedding the composed QR (preserves frames, logos, and text).
- 📋 **Copy to clipboard** — one-click PNG copy (requires HTTPS or localhost).

### Reliability
- **Automatic error correction** — High (30%) when a logo is present, Medium (15%) otherwise. No footguns.
- **Module-aligned rendering** — every QR module is drawn at an integer pixel size, so codes stay crisp at any zoom and scan reliably.
- **Stale generation guard** — rapid typing or slider changes can't render an outdated QR.
- **`file://` fallback** — if your browser blocks auto-downloads when the page is opened locally, a manual "click here" link appears.

---

## 🚀 Quick Start

### Use the hosted version
Open [https://praveendaseugene.github.io/qrcodegeneratoradv/](https://praveendaseugene.github.io/qrcodegeneratoradv/) — that's it.

### Run locally
```bash
git clone https://github.com/praveendaseugene/qrcodegeneratoradv.git
cd qrcodegeneratoradv
# open index.html in your browser
