# majidaloraidi.com

Live executive portfolio for Eng. Majid Mohammed Aloraidi — General Manager
of SHA'S Co. (Nestlé Waters JV) and Executive Director of Tahaluf Co. (NWC
Official Contractor).

This repository is the **GitHub Pages deployment** for majidaloraidi.com. It
contains only the built, self-contained site — not the editable source
project.

## What's in this repo

- `index.html` — the entire site (HTML, CSS, JavaScript, and all photos)
  bundled into a single file. No build step or dependencies required to
  serve it.
- `favicon.svg` — browser tab icon.
- `CNAME` — tells GitHub Pages to serve this repo at the custom domain
  `majidaloraidi.com` instead of the default `*.github.io` address. Do not
  remove this file, or the custom domain will stop working.

## Updating the live site

This repo is generated output. To make content or design changes:

1. Edit the source project (the full React/TypeScript/Vite codebase — ask
   for it if you don't have it on hand).
2. Rebuild it to produce a fresh single-file `index.html`.
3. Replace `index.html` in this repo with the new build and push.

Editing `index.html` directly in this repo works too for small text fixes,
but any structural change should go through the source project so it isn't
lost on the next rebuild.

## Language

The site loads in **English by default**, with a language switcher (EN/AR)
for full Arabic + RTL support.

## Domain / DNS

`CNAME` must contain exactly: `majidaloraidi.com`. DNS for the domain
should point to GitHub Pages per
[GitHub's custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

---
© 2026 Majid Mohammed Aloraidi. All rights reserved.
