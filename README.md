# TY QR Toolkit – Scan, Generate & Customize QR Codes

**A sleek, all-in-one QR code solution built with HTML, CSS, and Vanilla JS.**  
Perfect for businesses, developers, and creatives who need a fast, privacy-first QR tool.

---

## ✨ Features

- **📷 QR Scanner** – Scan QR codes using your device camera or upload an image.
- **✨ QR Generator** – Create custom QR codes from URLs, text, or contacts (vCard).
- **🎨 Color Customization** – Choose any foreground (dot) and background color.
- **⬇️ Download PNG** – Save generated QR codes as high-quality PNG images.
- **🔦 Flashlight Support** – Toggle torch on supported devices for low-light scanning.
- **📁 Drag & Drop** – Upload images by dragging them onto the app.
- **🔒 100% Client-Side** – No data ever leaves your browser – complete privacy.

---

## 🚀 Quick Start

1. **Download** the ZIP package.
2. **Extract** the contents to any folder.
3. **Open** `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
4. **Start scanning or generating** – it's that simple!

> **No server, no installation, no dependencies** – just a single HTML file!

---

## 🎨 Customization Guide

### 1. Change Brand Colors
Open `index.html` and find the `:root` CSS block near the top.  
Modify these variables to match your brand:

```css
:root {
  --primary-start: #667eea;    /* your main gradient start */
  --primary-end: #764ba2;      /* your main gradient end */
  --secondary-start: #22c55e;  /* success / download button */
  --secondary-end: #16a34a;
}
