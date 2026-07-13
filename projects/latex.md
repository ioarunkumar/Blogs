# AI LaTeX Repair Engine

> Offline-first, privacy-focused LaTeX debugging platform that fixes AI-generated LaTeX errors and compiles PDFs directly in the browser using WebAssembly.

![React](https://img.shields.io/badge/React-TypeScript-61DAFB)
![PWA](https://img.shields.io/badge/PWA-Enabled-purple)
![WebAssembly](https://img.shields.io/badge/WebAssembly-pdfLaTeX-orange)

---

## ✨ What it does

AI LaTeX Repair Engine is built to help developers and writers fix LaTeX problems quickly without sending source files to the cloud. It combines a browser-based LaTeX editor, a pdfLaTeX WebAssembly compiler, and AI repair guidance to make debugging faster and safer.

## ✨ Features

- 📝 Monaco Editor powered LaTeX editor
- 📄 Browser-side PDF compilation using pdfLaTeX WebAssembly
- 🤖 AI repair prompt generation for fixing LaTeX errors
- 🔍 Human-readable error explanations
- ✂️ Minimal failing snippet extraction
- ⚡ Instant PDF preview
- 📦 Progressive Web App (PWA)
- 🌐 Fully offline capable
- 🔒 Privacy-first (everything runs locally)
- 🚫 No backend required
- 🚫 No telemetry or analytics
- ❤️ Open Source

---

## 🏗 Architecture

```text
                 ┌──────────────────────────────┐
                 │        React Frontend        │
                 └──────────────┬───────────────┘
                                │
         ┌──────────────────────┼──────────────────────┐
         │                      │                      │
         ▼                      ▼                      ▼
  Monaco Editor         AI Prompt Generator      PDF Viewer
         │
         ▼
 LaTeX Source Editor
         │
         ▼
 pdfLaTeX WebAssembly
         │
         ▼
 Error Diagnostics
         │
         ▼
 Error Parser
         │
         ▼
 Minimal Snippet Extractor
         │
         ▼
 AI Repair Prompt
```

Everything executes inside the browser.

No servers.

No database.

No cloud processing.

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| React | Frontend |
| TypeScript | Type Safety |
| Vite | Build Tool |
| Monaco Editor | Code Editor |
| pdfLaTeX WebAssembly | PDF Compiler |
| Tailwind CSS | Styling |
| PWA | Offline Support |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 20+
- npm / pnpm / yarn

### Clone Repository

```bash
git clone https://github.com/ioarunkumar/LatextoPDF.git
cd LatextoPDF
```

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:5173
```

### Build for Production

```bash
npm run build
```

The production build will be generated inside:

```text
dist/
```

---

## 🌍 Deployment

The application is completely static after building. You can deploy it anywhere that hosts static sites, including GitHub Pages, Cloudflare Pages, Netlify, Vercel, Firebase Hosting, AWS S3, and CloudFront.

---

## 🤖 How It Works

```text
Write LaTeX

      │

      ▼

Compile with pdfLaTeX WASM

      │

      ▼

Parse Compilation Errors

      │

      ▼

Extract Minimal Broken Code

      │

      ▼

Generate AI Repair Prompt

      │

      ▼

Paste into your AI Assistant

      │

      ▼

Receive Fixed LaTeX

      │

      ▼

Compile Again
```

---

## 🔒 Privacy

Everything runs locally in your browser.

- No backend
- No login
- No cloud processing
- No analytics
- No cookies
- No telemetry
- No user tracking

Your LaTeX files never leave your device.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push your branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

## 🐛 Reporting Issues

Please include:

- Browser version
- Operating System
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)

---

## 📄 License

No license required — feel free to use it.

---

## 👨‍💻 Author

**Arun Kumar**

GitHub: https://github.com/ioarunkumar

Feel free to open issues, suggest improvements, or contribute to the project.
