## Road Trip — Static Website for App Store Support

This repository hosts a simple static site for the Road Trip app, suitable for App Store and Google Play support URLs and for GitHub Pages hosting.

### Pages

- `index.html` — Landing page
- `support.html` — Support and FAQ
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Use

### Local preview

Open `index.html` in your browser directly, or run a quick server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

### Publish to GitHub Pages

1. Create a new repo on GitHub (e.g., `road_trip_web`).
2. Push this folder as the repository root.
3. In GitHub → Settings → Pages:
   - Source: `Deploy from a branch`
   - Branch: `main` (or `master`) / folder: `/ (root)` → Save
4. Your site will be available at:
   - `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/`

If you use a repo named `YOUR_GITHUB_USERNAME.github.io`, the site root will be `https://YOUR_GITHUB_USERNAME.github.io/` and you don’t need the subpath.

### App Store submission

- Use the Support URL: point to `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/support.html`
- Use the Marketing URL: point to `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/`
- Use the Privacy Policy URL: point to `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/privacy.html`

### Customization

- Update contact email in `support.html`, `privacy.html`, and `terms.html`.
- Optionally replace the favicon and adjust colors in `assets/styles.css`.
