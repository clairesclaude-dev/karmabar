# Karma Bar + Kitchen — Website (Client Review Build)

Static single-page site for **Karma Bar + Kitchen**, North Knoxville.
Built by **Thirty3 Project** (Brooke Carper). Client: Karma and the Chameleon LLC.

## What this is
A self-contained `index.html` containing all four pages (Home, Menu, Calendar,
Contact) with client-side hash routing. No build step required.

- **Live review link:** GitHub Pages (see repo Settings → Pages)
- **Status:** Client review build. `noindex` + `robots.txt Disallow` are set so the
  review site does not appear in search engines before launch.
- **Fonts:** Google Fonts CDN (Cinzel, Monoton, Bebas Neue, Inter).
- **Production stack (downstream):** Astro + Sanity CMS + Cloudflare Pages.

## Local preview
Open `index.html` in any browser, or run `python3 -m http.server` in this folder.

## Pre-launch checklist (before going live on karmabarknox.com)
- [ ] Swap placeholder photos for final Drive images
- [ ] Replace Formspree endpoint placeholder on Contact form
- [ ] Flip `robots` meta back to `index, follow` and remove `robots.txt` block
- [ ] Confirm DoorDash store name + menu items
