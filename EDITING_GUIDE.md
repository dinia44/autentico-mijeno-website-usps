# Editing Guide For A Friend

This is a static website. The main files are:
- `index.html` for page sections and image references.
- `styles.css` for colours, spacing, mobile layout, and visual styling.
- `app.js` for the Spanish/English switch and contact-form email text.
- `assets/` for the social preview and property images.

To replace the sample property photos:
1. Add the real photos to `assets/`.
2. In `index.html`, replace these image filenames:
   - `property-terrace.jpg`
   - `property-interior.jpg`
   - `property-townhouse.jpg`
3. Update each `alt` description so it describes the real photo.

To edit the Spanish or English wording:
1. Open `app.js`.
2. Change the text inside the `translations` object.
3. Keep the same quote marks and commas.

To preview locally:
1. Open the project folder in a terminal.
2. Run `python3 -m http.server 4173`.
3. Visit `http://localhost:4173/`.

To make a public editable version:
- GitHub is best if your friend is comfortable editing website files.
- Canva is best if your friend wants visual design editing, but the language switch will not behave like a live website there.
- Vercel or Netlify is best for a public preview link once the files are ready.
