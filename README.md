# App Website (GitHub Pages Ready)

This folder contains a simple static website for App Store metadata:

- `index.html` - main app landing page
- `privacy.html` - privacy policy page
- `support.html` - support/contact page
- `styles.css` - shared styles

## Before Publishing

1. Update placeholder email values in:
   - `privacy.html`
   - `support.html`
2. Branding is currently set to "WLED - AI SmartDesign". Update it here later if the final App Store name changes.
3. Recheck the "Last updated" date in `privacy.html`.

## Free Hosting on GitHub Pages

1. Create a public GitHub repo (example: `wled-app-site`).
2. Upload all files from this folder to the repo root.
3. Go to repo `Settings` -> `Pages`.
4. Set source to `Deploy from a branch`.
5. Select `main` branch and `/ (root)` folder.
6. Save and wait for deployment.
7. Use the generated URL in App Store Connect:
   - Privacy Policy URL -> `.../privacy.html`
   - Support URL -> `.../support.html`

## Optional

If you want cleaner URLs like `/privacy/` and `/support/`, we can convert this
into folder-based routes in a follow-up pass.
