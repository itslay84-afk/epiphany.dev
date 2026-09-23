# epiphany.dev

A premium, conversion-focused landing page for a digital design and growth studio.

## Overview

This repository contains a polished static marketing site built to position the business around revenue, leads, and premium conversion design.

## Included sections

- Clear value proposition and CTA
- Service offering focused on business growth
- Proof section and testimonial
- Conversion-oriented pricing cards
- Process and FAQ sections
- Contact form ready for Netlify form handling
- Responsive design for mobile and desktop

## Run locally

Open `index.html` directly in a browser, or serve it locally:

```bash
cd epiphany.dev
python3 -m http.server 3000
```

Then visit http://localhost:3000

## Files

- `index.html` – marketing page structure
- `styles.css` – premium visual design and responsive layout
- `script.js` – mobile menu, FAQ accordion, reveal animations
- `assets/favicon.svg` – brand icon

## Netlify deployment

This repo is configured for a static site deploy on Netlify.

1. Push this repo to GitHub.
2. Sign in to Netlify.
3. Click “Add new site” → “Import an existing project”.
4. Select this repository.
5. Keep the build command blank and publish directory as `.`.
6. Deploy the site.
7. After deployment, open Site settings → Forms and enable email notifications.

## Contact form setup

The form is configured for Netlify Forms using:

```html
<form class="contact-form" name="contact" method="POST" data-netlify="true">
  <input type="hidden" name="form-name" value="contact" />
```

This means Netlify will capture submissions automatically when the site is live on Netlify.

## Recommended next step

Deploy to Netlify and connect the live form to your inbox or Formspree.
