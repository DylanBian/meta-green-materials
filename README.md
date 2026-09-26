# Meta Green Materials Ltd.

Static, single-page corporate website for GitHub Pages. It uses semantic HTML, responsive CSS and a small amount of vanilla JavaScript; no build step or backend is required.

Published site: https://dylanbian.github.io/meta-green-materials/

## Preview locally

Open `index.html` directly in a browser, or serve this folder with any static file server. All local asset paths are relative so the site also works from a GitHub Pages repository subdirectory.

## Editing notes

- `styles.css` is organized by page section (Tokens, Base, Header, Hero, About, Technologies, …, Responsive). Text colours use the `--text-2` / `--text-3` tokens, which are checked for WCAG AA contrast on every light background. Reuse them rather than adding new greys.
- Fonts are loaded from `index.html` (DM Sans, DM Mono and Manrope via Google Fonts), not from the stylesheet.

## Before public launch

- **Remove the `noindex` meta tag** in `index.html`. It keeps search engines out while the site is a draft.
- The Contact section shows the confirmed email (junweixie16@gmail.com), telephone and registered office address. If a company-domain email is set up later, replace the address in both the "Email us" button and the EMAIL row.
- The footer carries the UK trading disclosure (registered name, company no. 16574446, registered office) taken from Companies House. Update it if the registered office changes.
- The Leadership section uses the supplied portrait of Dr. Junwei Xie (`assets/junwei-xie.webp`).
- Licensed manufacturing partners are intentionally not named on the site for now. The Collaboration section describes the licensing model generically.
- Technical copy is based on the supplied CV and product brochures. Product claims are kept qualitative unless a brochure gives a figure.

## Brand assets

`assets/` holds the crest logo derived from the supplied JPG (white background removed): `crest.webp` (full crest), `crest-shield.webp` (shield only, for small sizes where the arched name is unreadable), favicons, and `og-image.jpg` (1200×630 share preview). MetaGreenMaterials® is a registered trademark of the company.

No personal contact details from the CV are included. No analytics, cookies, backend or tracking are used.

Original source PDFs (`source files/`) are git-ignored so they are not served as site assets.
