# alaskariannet

A faithful copy of https://asskaarian.netlify.app/ with the original layout, Arabic and English text, background, logo, fonts, icons, animations, and all seven social links.

## Preview

Run `npm run dev`, then visit http://localhost:3000.

No dependencies or build step are required. The complete site is in `dist/`; you can also open `dist/index.html` directly in a browser. All visual assets are stored locally, so the page itself does not require third-party asset requests. Social links open their original destinations in a new tab.

## Edit and deploy

- Edit `dist/index.html` for the layout, styles, text, and links.
- Images, fonts, and icon styles are in `dist/assets/`.
- Upload `dist/` to any static host. `netlify.toml` is included for Netlify.
- `npm run download-assets` refreshes the original public image and font assets.

The original design and branding belong to their respective owners. Font Awesome includes its license notice in `dist/assets/fontawesome.css`.
