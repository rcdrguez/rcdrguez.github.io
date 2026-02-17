# rcdrguez.github.io

Personal website and professional portfolio of Ricardo Rodríguez.

This repository contains a static website built with HTML, TailwindCSS (CDN) and vanilla JavaScript.  
It is deployed using GitHub Pages.

---

## Live Site

 https://rcdrguez.github.io/

---

## Overview

This site represents my professional profile as a Senior Software Engineer / Solution Architect, focused on:

- Enterprise Integration
- Middleware modernization
- Backend architecture
- Distributed systems
- Critical 24/7 operations
- Regulated environments (Banking, Government, Airports)

The goal is clarity, simplicity, and technical positioning.

---

## Tech Stack

- HTML5
- TailwindCSS (via CDN)
- Vanilla JavaScript
- GitHub Pages
- GitHub Actions (static deployment)

No frameworks. No build pipeline.  
Intentionally lightweight and dependency-minimal.

---

## Features

- Dark / Light theme toggle
- ES / EN language toggle
- Smooth scrolling navigation
- Responsive layout
- Minimal and performance-focused
- CV downloadable
- Toast feedback interactions
- No external backend dependency

---

## Project Structure
```
rcdrguez.github.io/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── static.yml
```

- `index.html` → Full site (layout + styles + scripts)
- `static.yml` → GitHub Actions workflow for deployment

---

## Deployment

This site is deployed automatically using GitHub Actions.

The workflow:
- Runs on push to `main`
- Uploads the repository as artifact
- Deploys to GitHub Pages

## Customization

Main editable areas:

- Content sections → inside `index.html`
- Internationalization dictionary → `I18N` object in JS
- Theme variables → CSS `:root` section
- Tech icons → Devicon CDN links

---

## Notes

- Tailwind is currently loaded via CDN for simplicity.
- For production hardening, Tailwind can be compiled locally.
- The site is designed to be portable and easily clonable.

---

## Author

Ricardo Rodríguez  
Senior Software Engineer / Solution Architect  

LinkedIn: https://www.linkedin.com/in/rcdrguez  
Email: r.rodriguezreyes@outlook.com

---

© 2026 Ricardo Rodríguez
