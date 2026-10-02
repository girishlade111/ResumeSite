# ResumeSite

A clean, professional, single-page personal resume / portfolio website built with plain HTML and CSS. Open it in any browser and you get a ready-to-use resume page — header with contact info, experience, skills, education, and projects sections, styled with a modern look and Font Awesome icons.

## Features

- Single-file resume page (`index.html`) — no build step, no dependencies to install
- Responsive layout that looks good on desktop and mobile
- Sectioned resume layout: summary, experience, skills, education, projects
- Font Awesome 6.4 icon set (loaded from CDN) for contact/skill icons
- Easy to customize — edit the HTML content and CSS variables to make it yours
- Print-friendly: open in a browser and print to PDF for a polished resume document

## Tech stack

- HTML5 + CSS3 (no JavaScript required)
- Font Awesome 6.4.0 (CDN) for icons
- Static hosting ready (GitHub Pages / any static host)

## Quick start

```bash
# Clone the repo
git clone https://github.com/girishlade111/ResumeSite.git
cd ResumeSite

# Option 1: open directly
# open index.html in your browser

# Option 2: serve locally (Python 3)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customizing

1. Open `index.html` and replace the placeholder name, contact details, experience, skills, and education with your own.
2. Adjust the color scheme by editing the `:root` CSS variables (`--primary-color`, `--secondary-color`).
3. To create a PDF: open the page in a browser and use Print → Save as PDF.

## Project structure

```
ResumeSite/
├── index.html   # The entire resume site (markup + styles)
└── README.md
```

## Deploy notes

No build step needed. The site deploys as-is to any static host. On GitHub Pages, enable Pages for the `main` branch root — the live site is served at `https://girishlade111.github.io/ResumeSite/`.

---

Built by Girish Lade — https://ladestack.in
