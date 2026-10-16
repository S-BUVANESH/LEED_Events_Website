# LEED Events — Static Landing Page

A responsive, single-page event website for the two supplied LEED / Kumaraguru events:

- **The Gandhi Paradox** — 22 October 2026, 5:00 PM, LH 21; Roland Ed Lamuel, Cambridge Entrepreneurship Partner.
- **Strategic Thinking, Networking & Entrepreneurial Growth** — 12 November 2026, 10:00 AM–4:00 PM, LH 24; Mr. Prasanth Jeyakumar.

## What's included

- `index.html` — semantic page structure and event content.
- `styles.css` — responsive layouts, mobile navigation, motion, and visual styling.
- `script.js` — mobile navigation, poster preview/lightbox, and scroll reveal.
- `assets/` — optimized WebP copies of both supplied posters and the site favicon.
- `posters/` — full-resolution PNG poster files for sharing or printing.

## Run locally

No package manager or build step is needed. Open `index.html` in a browser, or from this directory run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before public launch

1. **Add verified registration URLs.** The supplied poster images did not provide a QR code destination that could be verified. The current registration button directs visitors to LEED's published Linktree for updates. Replace that destination in `index.html` with the confirmed registration form URL(s) when provided by the organizers.
2. Confirm speaker details, room numbers, timings, and event dates with the event organizers before publication.
3. The site links to LEED's published website, Linktree, LinkedIn company page, and Kumaraguru Institutions' Linktree. Update these if the organization shares preferred links.

## Deploy

This is a static website and can be deployed by uploading the folder to any static host. For GitHub Pages, commit the contents of this folder to a repository and enable Pages for the branch/folder containing `index.html`. Vercel and Netlify can deploy the same folder without a build command.

## Design notes

The design uses a navy, cobalt, cyan, cream, and yellow palette inspired by the supplied posters. It includes event overview cards, speaker information, gallery/lightbox, poster downloads, registration/update CTA, LEED information, and official community links. No Reel or backend was added.
