# Juvant — Landing Page

Coming soon landing page for [Juvant](https://www.juvant.io), an AI venture studio building intelligence tools for education and beyond.

## Overview

A single-page static site with an email contact form. Visitors can enter their email to open a pre-filled `mailto:` link directed to `hello@juvant.io`.

## Stack

- Pure HTML/CSS/JS — no build step, no dependencies
- Fonts: [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- Hosted on GitHub Pages with a custom domain (`www.juvant.io`)

## Structure

```
.
├── index.html                          # Main page
├── assets/
│   └── images/
│       └── juvant-logo-transparent.png
└── CNAME                               # Custom domain config for GitHub Pages
```

## Local Development

No build step required. Open `index.html` directly in a browser or serve it with any static file server:

```bash
npx serve .
# or
python3 -m http.server
```

## Deployment

Deployed automatically via GitHub Pages on push to `main`. The `CNAME` file routes `www.juvant.io` to the GitHub Pages URL.
