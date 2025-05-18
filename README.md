<<<<<<< HEAD
# Story App - Submission

Proyek ini merupakan aplikasi cerita (Story App) sebagai bagian dari submission Dicoding, menggunakan **Webpack** untuk proses bundling, **Babel** untuk transpile JavaScript modern, serta mendukung **Progressive Web App (PWA)** dan **IndexedDB** untuk penyimpanan offline.

## Table of Contents

- [Getting Started](#getting-started)
- [Scripts](#scripts)
- [Project Structure](#project-structure)
- [Features](#features)

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (disarankan versi 12 atau lebih tinggi)
- [npm](https://www.npmjs.com/) (Node package manager)

### Installation

1. Clone atau download proyek ini.
2. Ekstrak file jika berupa .zip.
3. Jalankan perintah berikut untuk memasang dependencies:
   ```bash
   npm install
   ```

## Scripts

- **Build for Production:**
  ```bash
  npm run build
  ```
  Menjalankan webpack dalam mode production menggunakan `webpack.prod.js`. Output akan masuk ke folder `dist/`.

- **Start Development Server:**
  ```bash
  npm run start-dev
  ```
  Menjalankan server pengembangan dengan live reload (mode development) via `webpack-dev-server`.

- **Serve Production Build:**
  ```bash
  npm run serve
  ```
  Menyajikan folder `dist/` menggunakan [`http-server`](https://www.npmjs.com/package/http-server).

## Project Structure

```text
story-app-submission/
├── dist/                     # Hasil build production (siap deploy ke Netlify)
│   ├── index.html
│   ├── app.bundle.js
│   └── ...
├── src/
│   ├── scripts/              # JavaScript source
│   │   ├── views/
│   │   ├── routes/
│   │   ├── utils/
│   │   ├── data/
│   │   └── index.js
│   ├── styles/
│   │   └── styles.css
│   └── index.html            # Template HTML
├── public/                   # Public assets (ikon, manifest, service worker)
│   ├── icons/
│   ├── sw.js
│   └── manifest.json
├── package.json
├── webpack.common.js
├── webpack.dev.js
├── webpack.prod.js
├── .babelrc
├── .eslintrc
├── .gitignore
├── README.md
└── STUDENT.txt
```

## Features

- ✅ Webpack Configuration (Dev + Prod)
- ✅ Babel untuk ES6+
- ✅ PWA (manifest + service worker)
- ✅ IndexedDB untuk penyimpanan offline
- ✅ Responsive layout
- ✅ Modular JS structure
- ✅ Support deploy ke Netlify

---

> Untuk melakukan deploy ke Netlify, jalankan `npm run build`, lalu upload folder `dist/` ke Netlify melalui metode drag-and-drop atau Git integration.
=======
# story-app-pwa
Aplikasi Story App Submission Dicoding - Web App modern dengan Webpack, PWA, dan IndexedDB. Dibuat sebagai bagian dari submission kelas Menjadi Front-End Web Developer Expert.
>>>>>>> b9797b53be9a2b6d154f046ec0799dcfddb6bb37
