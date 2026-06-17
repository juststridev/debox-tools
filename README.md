# Debox Tools - v1.0.0 (Pre-built Release)

A blazing-fast, offline-capable, and 100% client-side collection of essential developer tools. Built with Svelte 5 and designed with an uncompromising focus on performance and privacy.

**Note:** This is the **pre-built static release** of Debox Tools. It contains production-ready static assets (HTML/CSS/JS) and requires no build steps or backend servers.

## ✨ Features

- **🔒 100% Privacy-First:** All processing (formatting, converting, generating) happens locally inside your browser. No data leaves your machine.
- **🛠️ 12 Built-in Tools:** Base64, URL Encode/Decode, JSON Formatter, HTML/SQL/XML Beautifiers, CSS Gradient Generator, SVG Optimizer, and more.
- **⚡ Lightning Fast:** Powered by Svelte 5 Runes for optimal reactivity.
- **🔍 Command Palette:** Press `⌘K` or `Ctrl+K` to instantly search and jump to any tool.
- **🌓 Dark Mode & Layouts:** Sleek dark mode support and seamless toggling between horizontal and vertical layouts.

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

- **Zero Tracking:** This public release has been stripped of all analytics and tracking scripts (e.g., PostHog). It respects your privacy 100%.
- **Local Storage:** Your settings (Theme, Layout preference, Favorite tools) are saved locally in your browser's `localStorage` and will automatically persist across sessions.
