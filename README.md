# DeboxHub - v1.1.2 (Pre-built Release)

A blazing-fast, offline-capable, and highly extensible collection of essential developer tools. 

**Note:** This is the **pre-built static release** of DeboxHub. It contains production-ready static assets (HTML/CSS/JS) and requires no build steps or backend servers.

## ✨ Features

- **🔒 100% Privacy-First:** All processing (formatting, converting, generating) happens locally inside your browser. No data leaves your machine.
- **🛠️ 22+ Built-in Tools:** Base64, URL Encode/Decode, JSON Formatter, OTP/2FA Generator, Shell Explainer, URL Parser, QR Code Generator, Image Color Extractor, AES/DES Encryptor, CSS Gradient Generator, DateConverter and more.
- **⚡ Lightning Fast:** Powered by pre-compiled Svelte for optimal reactivity.
- **🧠 Smart Quick Parse:** Automatically detects input types (JSON, Base64, HTML, URL).
- **💾 Auto-Persistence:** Every tool is equipped with a smart storage engine. Your input and configurations are automatically saved locally.
- **🎨 Minimalist Visual Identity:** DeboxHub strictly adheres to a minimalist visual branding.
- **🔐 Robust Tool Suites:** Includes comprehensive Workspaces for Code Formatting, Security (AES/DES Encryption, OTP/2FA), Comparators, and Web utilities (URL Parser, Shell Explainer).
- **🌓 Appearance Modes:** Full support for Light, Dark, and System modes.

## 🚀 How to Run (Local Deployment)

Since this is a modern Single Page Application (SPA) using ES modules, you cannot simply double-click the `index.html` file (due to browser CORS policies). You need to serve it using a local web server.

Open your terminal in this folder and run one of the following commands:

### Option 1: Using Node.js (npx)
If you have Node.js installed:
```bash
npx serve .
```
Then open `http://localhost:3000` in your browser.

### Option 2: Using Python
If you have Python installed:
```bash
# Python 3
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

## 🌍 How to Host (Public Deployment)

You can easily host this pre-built folder on any static hosting provider for free. It is fully compatible with any static web host.

### Vercel / Netlify / Cloudflare Pages (Recommended)
1. Drag and drop this folder into the "Deploy manually" dropzone of Netlify or Cloudflare Pages.
2. Wait a few seconds, and your tools are live!

### Nginx / Apache
Simply copy the contents of this folder into your web server's public root directory (e.g., `/var/www/html`).

## ⚙️ Configuration & Analytics

- **Zero Tracking:** This public release has been stripped of all analytics and tracking scripts (e.g., Google Analytics). It respects your privacy 100%.
- **Local Storage:** Your settings (Theme, Layout preference, Favorite tools) are saved locally in your browser's `localStorage` and will automatically persist across sessions.
