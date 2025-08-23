## Road Trip — Static Website (TR default, EN available)

This repository hosts a bilingual static site for the Road Trip app, suitable for App Store/Play Store support and policy URLs and for GitHub Pages hosting.

### Pages (default Turkish)

- `index.html` — Ana sayfa
- `support.html` — Destek ve SSS
- `privacy.html` — Gizlilik Politikası
- `terms.html` — Şartlar ve Koşullar

### English pages

- `en/index.html`
- `en/support.html`
- `en/privacy.html`
- `en/terms.html`

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
   - TR (default): `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/`
   - EN: `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/en/`

If you use a repo named `YOUR_GITHUB_USERNAME.github.io`, the site root will be `https://YOUR_GITHUB_USERNAME.github.io/` and you don’t need the subpath.

### App Store submission

- Support URL (TR): `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/support.html`
- Marketing URL (TR): `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/`
- Privacy Policy URL (TR): `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/privacy.html`
- Terms URL (TR): `https://YOUR_GITHUB_USERNAME.github.io/road_trip_web/terms.html`
- Optionally provide EN equivalents under `/en/` if requested by the store.

### Customization

- Replace `YOUR_GITHUB_USERNAME` in meta/README links.
- Contact email is set to `roadtripdestek@gmail.com` across pages — change if needed.
- Optionally replace the favicon and adjust colors in `assets/styles.css`.
