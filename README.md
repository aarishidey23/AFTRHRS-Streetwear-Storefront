# AFTRHRS — Streetwear Storefront

A responsive, dark editorial streetwear storefront built from the supplied Stitch HTML and design system.

## Features

- Cyber-editorial design with black surfaces, acid-lime highlights, and bold typography
- Responsive storefront layout and product collection grid
- Product category filtering and sorting
- Product quick-preview modal
- Size selection, wishlist toggles, and shopping bag drawer
- Quantity updates, item removal, subtotal, and free-shipping progress
- VIP email signup interaction

## Run locally

No build step is required. Open `index.html` in a browser, or run a local static server from this folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Publish with GitHub Pages

1. Create a new **public** repository on GitHub, for example `aftrhrs-streetwear-storefront`. Do not initialize it with a README if you plan to upload these files as the first commit (if you do, you can still upload and commit normally).
2. On the repository page, choose **Add file → Upload files**.
3. Extract this ZIP on your computer, then drag the *contents* of this folder into GitHub's upload area. Ensure `index.html` is at the repository root, not nested inside another folder.
4. Enter a commit message such as `Add AFTRHRS storefront` and click **Commit changes**.
5. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then click **Save**.
6. Wait for GitHub Pages to finish publishing. The site URL will appear in **Settings → Pages**, typically `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Notes

- This is a front-end demo. Checkout is simulated and does not take real payments or create real orders.
- The HTML uses external CDN/font/image URLs, so those resources require an internet connection and may change or become unavailable.
- Do not collect real customer information until a secure backend, privacy policy, and appropriate integrations are implemented.
