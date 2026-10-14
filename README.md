# bouda.life

Personal page of Ondřej Bouda — https://bouda.life

Plain HTML + [Skeleton](http://getskeleton.com) (from cdnjs), no build step. Served by GitHub Pages.

## ⚠️ This repo is public

Pages on a free account require a public repo. Everything here, including git history, is visible to anyone — commit only what's meant to be public.

## Maintenance

- Deploy: push to `master` → live in a minute or two. Preview locally: `open index.html`
- `CNAME` holds the custom domain — **don't delete**.
- Favicons are generated from the logo:
  ```
  magick assets/logo.jpg -define icon:auto-resize=48,32,16 favicon.ico
  magick assets/logo.jpg -resize 180x180 apple-touch-icon.png
  ```
- Pages settings: branch `master` / root, custom domain `bouda.life`, Enforce HTTPS on. Domain verified in account Settings → Pages.
- DNS (Namecheap): `@` → A records of GitHub Pages, `www` → CNAME `ondrejbouda.github.io.`, plus TXT `_github-pages-challenge-ondrejbouda` for domain verification (keep it).

## Next steps

- Review Skeleton, design and page basics overall (the page is ~10 years old): mobile-friendly layout, meta tags, accessibility.
