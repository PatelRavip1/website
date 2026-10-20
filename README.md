# 🕹️ Ravi Patel — Personal Portfolio Website

[![Astro](https://img.shields.io/badge/Astro-4.16-FF5D01?style=flat-square&logo=astro&logoColor=white)](https://astro.build)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Catppuccin Mocha](https://img.shields.io/badge/Palette-Catppuccin_Mocha-CBA6F7?style=flat-square)](https://github.com/catppuccin/catppuccin)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

> A retro 8-bit pixel-art themed personal portfolio website built with **Astro 4**, **Tailwind CSS**, and **TypeScript**. Features custom sound effects, interactive widgets, and responsive design.

**🌐 Live Website:** [https://patelravip1.github.io/website/](https://patelravip1.github.io/website/)

---

## ✨ Features

- **Retro 8-Bit Pixel Aesthetic**: Styled with the official Catppuccin Mocha palette, dotted grid background, and custom pixel-art borders & cursors.
- **Interactive Analog Clock**: Custom SVG clock component featuring real-time hour/minute/second hands, date, month, AM/PM indicator, and day/night cycle symbol.
- **8-Bit Chiptune Sound Engine**: Built with the Web Audio API (synthesizing retro square and triangle waves), toggleable via a floating pixel audio control bar.
- **Responsive Layout**: Fluid container sizing optimized for widescreen desktops, laptops, tablets, and mobile devices.
- **Project Showcase**: Retro card grid highlighting personal coding projects and GitHub repositories.
- **Tech Stack & Tools**: Curated list of programming languages, CLI tools, editor configurations, and fonts.

---

## 🧭 Pages & Structure

| Route | Page | Description |
|---|---|---|
| `/` | **Home** | Hero section with interactive clock, personal bio, social links, and navigation. |
| `/about/` | **About** | Background story, education, and programming journey with photo display. |
| `/projects/` | **Projects** | Grid of personal software projects with direct GitHub links. |
| `/tools/` | **Tools** | Development setup: shell, fonts, VS Code extensions, and operating systems. |
| `/contact/` | **Contact** | Contact info and freelance inquiry details. |

---

## 🛠️ Tech Stack

- **Framework**: [Astro 4](https://astro.build)
- **Styling**: [Tailwind CSS](https://tailwindcss.com) & Scoped CSS
- **Language**: [TypeScript](https://www.typescriptlang.org)
- **Design Palette**: [Catppuccin Mocha](https://github.com/catppuccin/catppuccin)
- **Audio Engine**: Web Audio API (Chiptune synthesizer)
- **Typography**: JetBrains Mono & Writer TTF fonts
- **Deployment**: GitHub Pages via GitHub Actions

---

## 🚀 Getting Started

### Prerequisites

Ensure you have **Node.js** (v18.14.1 or higher) and **npm** installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PatelRavip1/website.git
   cd website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Start the local Astro development server:

```bash
npm run dev
```

Open [http://localhost:4321/website/](http://localhost:4321/website/) in your browser.

---

## 📦 Build & Deployment

To type-check and generate the static production build:

```bash
npm run build
```

To preview the built production output locally:

```bash
npm run preview
```

The repository includes a GitHub Actions workflow (`.github/workflows/astro.yml`) that automatically builds and deploys changes pushed to `master` directly to GitHub Pages.

---

## 👤 Author

**Ravi Patel**
- GitHub: [@PatelRavip1](https://github.com/PatelRavip1)
- LinkedIn: [Ravi Patel](https://www.linkedin.com/in/ravi-047/)
- Instagram: [@rv.047](https://www.instagram.com/rv.047/)
