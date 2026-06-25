# Jessy's

Small-batch food brand website — raw sea moss gel and live-cultured sauerkraut, hand-made in small batches in Mombasa, Kenya.

🔗 **Live site:** https://okeroofficial-coder.github.io/Jessy-s/

---

## About

Jessy's makes:
- Raw sea moss gel
- Live-cultured sauerkraut

This repo holds the single-page website used to showcase the brand and take orders directly via WhatsApp.

## Features

- Single-page responsive design (mobile-first)
- WhatsApp-integrated ordering (orders go straight to the brand's WhatsApp number)
- M-Pesa payment info for easy local checkout
- Custom color palette (charcoal, alabaster, navy, seafoam, sandgold, sage, ochre)
- Custom type system: Fraunces, Plus Jakarta Sans, Jost, Space Mono (Google Fonts)
- SEO/social meta tags (title, description, Open Graph) already set up

## Tech Stack

- HTML5
- CSS3 (all styles inline in `<style>`, custom properties for the palette)
- Vanilla JavaScript (inline `<script>`)
- No frameworks, no build step, no dependencies — one file does everything

## File Structure

```
jessys/
├── index.html      # entire site — markup, styles, and script all in one file
└── README.md       # this file
```

> Everything (CSS, JS, fonts via Google Fonts link) lives inside `index.html`. There are no separate asset files to manage or break.

## Running Locally

No build tools needed. Just clone and open:

```bash
git clone https://github.com/okeroofficial-coder/Jessy-s.git
cd Jessy-s
open index.html   # or double-click the file
```

## Deployment

Hosted via **GitHub Pages** directly from this repo.

To update the live site:
```bash
git add .
git commit -m "describe what changed"
git push
```

GitHub Pages will rebuild automatically — usually live within a minute or two.

## Ordering Flow

1. Customer browses products on the site
2. Taps "Order on WhatsApp" → opens a chat with a pre-filled message to wa.me/254756786886
3. Payment confirmed via M-Pesa
4. Order fulfilled

## Roadmap / Ideas

- [ ] Add customer testimonials section
- [ ] Add simple product gallery / lightbox
- [ ] Connect custom domain
- [ ] Add basic analytics (page views, WhatsApp click tracking)

## Author

Built by okeroofficial.
