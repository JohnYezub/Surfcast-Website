# Wavelet Surf — website

Static landing page for **Wavelet Surf Forecast** with **Privacy Policy** and **Terms of Use**, ready for [GitHub Pages](https://docs.github.com/en/pages).

## Local preview

Open `index.html` in a browser, or from this directory run:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080/

## Publish on GitHub Pages

1. Push this repository to GitHub (default branch e.g. `main`).
2. In the repo on GitHub: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** and folder **`/ (root)`**, then save.

After deployment, the site is available at:

`https://<username>.github.io/<repository>/`

All internal links use **relative** paths (`privacy.html`, `terms.html`, `styles.css`), so the same files work for both project sites and a custom domain pointed at the Pages root.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms of Use |
| `styles.css` | Shared styles |
| `.nojekyll` | Disables Jekyll processing (optional safety for static files) |

**Support:** [balitideforecast@gmail.com](mailto:balitideforecast@gmail.com)

Replace the App Store button on the landing page with a real App Store URL when the app is live. Review bracketed placeholders in `terms.html` (liability cap, governing law) with qualified counsel before relying on them legally.
