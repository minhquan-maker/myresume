# Quan Minh Nguyen — Resume

> A clean, editorial single-page HTML resume with a typographic design — built to look great on screen and print.

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](resume.html)
[![Format](https://img.shields.io/badge/Format-HTML%20%2B%20CSS-green?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](#)

---

## Quick View

```
Quan Minh Nguyen
├── 🎓 AI Research Student — University of Technology Sydney
├── 🔬 Focus — Artificial Intelligence & Environmental Technology
├── 📍 Based — Ho Chi Minh City, Vietnam / Sydney, Australia
└── 📄 Format — Editorial website-style resume
```

---

## What's Inside

This resume is designed to stand out from the typical template — using a magazine/newspaper aesthetic with:

- **Cormorant Garamond** — Elegant serif for headings and names
- **Syne** — Modern geometric sans for body text
- **IBM Plex Mono** — Monospace for labels, dates, and technical details
- **Gold accent** (`#D4AF37`) — Adds warmth and distinction

All styles are **inline within the HTML** — no external CSS files, no build step.

---

## Tech Stack

```
Layout       HTML5 (semantic, accessible)
Styling      Inline CSS with CSS custom properties
Fonts        Google Fonts (Cormorant Garamond, Syne, IBM Plex Mono)
Print        Optimized for @media print — clean single-page output
```

---

## Files

| File | Description |
|------|-------------|
| `resume.html` | Main resume — open in browser or print |
| `resume.pdf` | PDF version (print-ready) |
| `README.md` | This file |

---

## How to Use

### View in browser

```bash
open resume.html
# or
python3 -m http.server 8080  # then visit http://localhost:8080/resume.html
```

### Print to PDF

1. Open `resume.html` in browser (Chrome recommended)
2. `Cmd/Ctrl + P` → Save as PDF
3. Use the `@media print` styles already in the file for clean output

---

## Updating Content

All resume content is directly in `resume.html`. Search for these sections to update:

```
Education    → <section id="education"> or look for university entries
Experience   → <section id="experience"> or work history entries
Skills       → Look for skills/tech lists
Projects     → Search for project entries
Awards       → Search for honors/awards section
Contact      → Footer or contact info block
```

---

## Design Customization

The design system lives in the `<style>` block at the top of `resume.html`. Key variables:

```css
:root {
  --gold:    #D4AF37;    /* Accent color */
  --dark:    #1a1a1a;    /* Text color */
  --offwhite:#fafaf8;    /* Background */
  --border:  #e0ddd8;    /* Dividers */
}
```

---

## Social Links

| Platform | Link |
|----------|------|
| GitHub | [minhquan-maker](https://github.com/minhquan-maker) |
| LinkedIn | [ngminhquan](https://www.linkedin.com/in/ngminhquan/) |
| Facebook | [mquan2512](https://www.facebook.com/mquan2512/) |
