# Public Changelog

This document outlines the major, user-facing changes and updates to DeboxHub. For detailed internal technical changes, please refer to `CHANGELOG.md`.

## [1.1.1] - 2026-06-23

### 🚀 What's New
- **2 New Tools Added**:
- **OTP/2FA Generator**: Generate TOTP/HOTP two-factor authentication codes securely and entirely offline, complete with algorithm configuration and real-time hex payload insights.
- **Shell Explainer**: Explains over 99 command-line utilities to help you understand complex terminal commands instantly.

### ✨ Improvements
- **Layout Enhancements**: Improved the main Header, Sidebar behavior, and Category Navigation for a smoother browsing experience.
- **JSON Formatter**: Added a new options formatter functionality to give users more control over JSON formatting rules.

### 🐛 Bug Fixes
- **UI Stability**: Fixed layout jumping issues when switching between tools.

---

## [1.1.0] - 2026-06-22

**📢 Rebranding Announcement**
The project has officially been renamed from **Debox Tools** to **DeboxHub**. We are now live at our official website: [deboxhub.com](https://deboxhub.com).

### 🚀 What's New
- **7 New Tools Added**: 
- **DateConverter Tool**: Convert timestamps, explore timezones, perform time math, and batch convert dates.
- **Image Color Extractor & Proxy API**: Extract color palettes from images, including support for image URLs.
- **Eyedropper Tool**: Extract colors from any pixel on your screen.
- **Chmod Calculator**: Easily calculate Linux file permissions.
- **String Escaper**: Escape and unescape strings.
- **QR Code Generator**: Create multi-purpose QR codes.
- **Encryptor Tool**: AES/DES encryption with random Key/IV generation.
- **Roadmap & Idea Submission**: Added a comprehensive Roadmap page with Kanban/Timeline views and an integrated "Submit an idea" feature for users.
- **Tool Documentation**: Introduced interactive modal documentation for tools to help users understand features better.
- **Comparator Workspace**: Added a dedicated workspace for comparison tools.

### ✨ Improvements
- **Tool Headers UI**: Redesigned tool headers to include Category Badges and neatly arranged functional buttons (Help/Info, Favorite, Fullscreen) on the right for an optimized user experience.
- **Home Header & Navigation**: Redesigned the Home Header layout and moved the Roadmap into the main Sidebar navigation for easier access.
- **Output Editing**: You can now directly edit output values across tools.
- **DateConvert Widget**: Added a seamless toggle to switch between entering timestamp numbers or selecting dates via a calendar.
- **Roadmap Usability**: Added search functionality to the Roadmap and real-time release dates on tool cards.
- **Enhanced UX**: Tools now auto-save your last input values (for formatters), include distinct icons to differentiate Converters vs. Formatters, and feature polished dark mode elements.
- **Localization**: Updated language translations.

### 🐛 Bug Fixes
- Fixed an issue where the QR Code tool was duplicated in the system.
- Fixed layout alignment and whitespace issues in the header navigation.

---

## [1.0.0] - 2026-06-16

### 🚀 What's New
- **Official Launch**: Released the first official version of DeboxHub with a robust, privacy-first platform loaded with 12 essential tools.
- **Converters**: Base64 Encoder/Decoder, URL Encoder/Decoder, HTML Entity Encoder, Markdown ↔ HTML.
- **Formatters**: JSON Validator & Formatter, HTML Beautifier, SQL Formatter (multi-dialect), XML Formatter.
- **Design Tools**: Color Converter (HEX/RGB/HSL/CMYK), CSS Gradient Generator, SVG Optimizer, Favicon Generator.
- **Privacy First**: All tools are guaranteed to run 100% locally in your browser.

### ✨ Improvements
- **Layout Engine**: Added seamless switching between Horizontal and Vertical Sidebar layouts.
- **Command Palette**: Hit `⌘K` to search and jump to any tool instantly.
- **Dark Mode**: Gorgeous, fully-optimized dark mode support with glassmorphism elements.
- **Localization**: Support for English and Vietnamese interfaces.

---

## [1.0.0-beta] - 2026-05-28

### 🚀 What's New
- Initial beta release for early testing.
- Added early versions of basic utilities: Base64 Encoder/Decoder, JSON Formatter, and HTML Formatter.
- Prototyped the initial UI shell with vertical layout.
