# Sunrise Bakery — One-Page Website

A single-file website for Sunrise Bakery, Austin TX. Plain HTML and CSS, no
frameworks, no build step, no external requests.

## Files

- `index.html` — the entire website (HTML + CSS in one file)

## How to use it

Open `index.html` in any browser to view it. To put it online, upload that one
file to any web host. If it is the only page, name it `index.html` and it will
load as the homepage automatically.

Free hosts that work by drag-and-drop: Netlify Drop, Cloudflare Pages, GitHub Pages.

## Before going live

Replace the placeholder phone number `(512) 555-0142`. It appears twice in
`index.html`, in the Phone card — once in the `tel:` link and once as the
visible text:

```html
<p><a href="tel:+15125550142">(512) 555-0142</a></p>
```

## Editing

- **Hours** — in the `.hours` block in the hero
- **Menu items and prices** — the `<ul>` inside `<section class="menu">`
- **Colours** — the `:root` variables at the top of the `<style>` block
- **Address / phone** — the two `.card` blocks in the "Find Us" section

## Notes

- Responsive: verified at 320px, 390px and 1280px wide with no horizontal scroll
- The sun logo is inline SVG, so the page renders fully offline
- The address links to Google Maps; the phone number dials on mobile
