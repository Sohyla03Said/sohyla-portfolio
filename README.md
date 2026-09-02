# Sohyla Said — Portfolio

A personal portfolio site for **Sohyla Said**, Computer Engineering graduate (E‑JUST), showcasing work across AI & Machine Learning, Web & Enterprise Systems, Mobile Development, and Teaching & Mentorship.

**Live demo:** _add your link here once deployed (e.g. GitHub Pages)_

![Preview](assets/portrait.png)

## About

This is a static, multi-page portfolio built from scratch with plain HTML, CSS, and JavaScript — no framework, no build step. The color palette is drawn directly from a portrait photo (charcoal blazer, ivory headscarf, deep wine-red accent), and the layout is organized into four "tracks" that mirror how the work actually breaks down:

- **AI & Machine Learning** — quantized on-device LLMs, RAG, CNN/GAN projects
- **Web & Enterprise Systems** — full-stack apps and enterprise content-management (IBM FileNet, OpenText)
- **Mobile Development** — native Android and cross-platform Flutter apps
- **Teaching & Mentorship** — curriculum design and live instruction for 100+ students

## Features

- Responsive, single-theme design across all pages (desktop + mobile nav)
- Scroll-reveal animations and an animated hero section
- CV embedded directly in the page as a data URI, so **View CV** and **Download CV** work reliably with no server required
- Contact form wired to [FormSubmit](https://formsubmit.co) — messages are emailed directly, no backend needed
- Four dedicated project/experience track pages, cross-linked from the homepage

## Tech stack

- HTML5 / CSS3 (custom properties, CSS Grid & Flexbox)
- Vanilla JavaScript (no dependencies)
- Google Fonts: Fraunces, IBM Plex Sans, IBM Plex Mono

## Project structure

```
portfolio/
├── index.html          # Homepage — hero, about, work grid, experience, contact
├── script.js         # Nav, scroll-reveal, contact form, CV buttons
├── pages/
|   ├── teaching.html         # Teaching & Mentorship track
|   ├── ai.html              # AI & Machine Learning track
|   ├── web.html             # Web & Enterprise Systems track
│   └── mobile.html           # Mobile Development trac
└── assets/
    ├── profile.svg
    ├── sohyla.pdf   # CV, used as a fallback link
    └── style.css  
```

## License

© 2026 Sohyla Said. All rights reserved — this code is shared for personal portfolio use.
