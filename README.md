# Qaiser — Personal Academic Portfolio

A responsive, single-page academic portfolio built with plain HTML, CSS, and JavaScript. No build step or backend is required.

## Run locally

1. Extract the ZIP.
2. Open the `academic_portfolio` folder in VS Code.
3. Open `index.html` in your browser. For a better local workflow, install the VS Code extension **Live Server**, right-click `index.html`, and choose **Open with Live Server**.

## Before publishing

Search `index.html` for `TODO` and `PLACEHOLDER`, then update:
- Your full public-facing name and preferred professional title.
- Institutional affiliation and education details.
- Email address (`YOUR.EMAIL@EXAMPLE.COM`).
- Google Scholar and ORCID links.
- CV link and verified publication / DOI URLs.
- Publication status and author information.
- Add a real portrait if you want one; the hero currently uses a CSS illustration and needs no image file.

The FedSemGNN GitHub URL is prefilled from the known public repository. Check all publication metadata and status labels before publishing. The site intentionally distinguishes published work from research in progress.

## Publish

This is a static site. You can deploy the folder with GitHub Pages, Netlify, Cloudflare Pages, or another static host. Upload the contents of this folder, not the ZIP itself, to the host's site root.

## Files

- `index.html` — page content and sections
- `styles.css` — design system, layout, responsive styles
- `script.js` — mobile navigation, current year, and scroll reveal effects

## Customization

Colors and fonts are defined at the top of `styles.css` in `:root`. Change the CSS variables there to re-theme the site.
