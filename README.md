# Rag Quilt Calculator

A simple, mobile-friendly rag quilt calculator for planning layouts, fabric shares, and yardage — built with love (and math) for my mom.

**Live site:** https://<your-username>.github.io/rag-quilt-calculator/

## Features
- Finished block math (cut size − 2× seam allowance)
- Auto grid: blocks across/down, total blocks, finished quilt size
- Any number of top/backing fabrics with percentage shares
- Squares-per-yard math with rounding to your chosen fraction
- Optional middle layer (batting/flannel), auto-sized to stay out of seams
- Print-friendly layout

## How to Use
1. Enter finished quilt width/height, cut-square size, seam allowance, and usable fabric width.
2. Add your top/backing fabrics and set each share (%). Totals don’t have to be perfect — the calculator uses your actual numbers.
3. (Optional) Check **Use a middle layer**. Leave its cut size blank to auto-size.
4. Click **Calculate**. Yardage is rounded up (default 1/8 yd).
5. Print for your cutting table.

> Reality check: prewash, shrinkage, directional prints, plaids, and fussy cutting can nudge yardage. Buy a little extra if your fabric has “main character energy.”

## Local Development
Just open `index.html` in a browser. No build tools.

## Deploying to GitHub Pages
- Settings → Pages → Source: **Deploy from a branch**
- Branch: **main**, Folder: **/** (root)

## Optional
- Add a favicon at `assets/favicon.ico`.
- Social preview image at `assets/cover.png` and OG meta tags in `<head>`.
- Custom domain: set a CNAME in DNS and in repo Settings → Pages.

## License
MIT. Quilt freely.
