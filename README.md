# FP — Palermo Driver
### Mobile Landing Page · Bilingual IT/EN · GitHub Pages

> A lightweight, mobile-first landing page for a private chauffeur service based in Palermo, Sicily. Built as a digital evolution of a printed flyer — interactive, bilingual, and deployable via QR code.

---

## 🌐 Live Site

**[claudiowebdesigner.github.io/palermo-driver](https://claudiowebdesigner.github.io/palermo-driver/)**

Short URL: [bit.ly/4cPgDZL](https://bit.ly/4cPgDZL)

---

## Overview

**FP Palermo Driver** offers private chauffeur services in and around Palermo, Sicily — including airport transfers, beach day trips to Mondello, and full-day tours to Monreale and Cefalù.

This project replaces a static printed flyer with an interactive mobile web experience, accessible instantly via QR code scan. The page is designed to load fast, look great on any smartphone, and convert visitors into WhatsApp bookings with a single tap.

---

## Features

- **Bilingual** — Italian / English toggle with automatic browser language detection
- **Mobile-first** — optimized for vertical smartphone screens (max-width: 430px)
- **Zero dependencies** — pure HTML/CSS/JS, no frameworks, no build tools
- **Fast loading** — images served in WebP format, lazy loaded
- **One-tap booking** — direct WhatsApp CTA linked to the driver's number
- **QR-ready** — designed to be the destination of a printed QR code

---

## Pages & Sections

| Section | Content |
|---|---|
| Hero | Brand identity, tagline, service tags |
| Tariffe / Pricing | 5 service cards with icons and prices |
| Destinazioni / Destinations | 4-photo grid (Mondello, Cefalù, Monreale, Airport) |
| Veicolo / Vehicle | Ford Kuga 2019 specs |
| CTA | WhatsApp button + phone number |

---

## Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, flexbox, grid) |
| Interactivity | Vanilla JavaScript |
| Typography | Google Fonts — Playfair Display + Inter |
| Images | WebP (converted from JPG for performance) |
| Hosting | GitHub Pages (free) |
| Short URL | bit.ly |

---

## File Structure

```
palermo-driver/
├── index.html        # Main page (bilingual, self-contained)
├── mondello.webp     # Mondello Beach photo
├── cefalu.webp       # Cefalù fishing village photo
├── monreale.webp     # Monreale Cathedral photo
├── aeroporto.webp    # Palermo Airport photo
└── README.md         # This file
```

---

## Services & Pricing

| Service | Price |
|---|---|
| Airport Transfer (PMO) — daytime | €35 |
| Airport Transfer (PMO) — night/holiday | €50 |
| Palermo → Mondello (one way) | €25 |
| Mondello Round Trip (max 4h) | €65 |
| Monreale Round Trip (1h wait) | €65 |
| Monreale + Cefalù Full Day Tour ⭐ | €300 |

---

## Contact

📞 +39 347 11 13 067
💬 [WhatsApp](https://wa.me/393471113067)

---

## Deployment

Hosted on **GitHub Pages** from the `main` branch root.
Any push to `main` automatically updates the live site within ~60 seconds.

To update prices or content: edit `index.html` directly on GitHub via the web editor, then commit. No build step required.

---

*Developed as a digital product design project — transforming a static printed flyer into a fast, accessible, multilingual mobile experience.*
