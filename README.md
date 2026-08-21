# Rameez Karamat Bhatti — Portfolio

A fast, responsive, single-page portfolio for **rameezmeans.github.io**. It uses plain HTML, CSS, and JavaScript, so there is no framework, package installation, or build step.

## Preview locally

You can open `index.html` directly in a browser. For the most accurate local preview, run a simple web server from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Copy these files into the root of the `rameezmeans.github.io` repository.
2. Commit and push them to the repository's default branch (normally `main`).
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

GitHub will publish the site at [https://rameezmeans.github.io](https://rameezmeans.github.io). Future pushes to `main` will update it automatically.

## Personalize

- Update project descriptions and metrics in `index.html` whenever work changes.
- Replace `assets/rameez-karamat-bhatti-resume.pdf` with a newer résumé using the same filename.
- Contact and social links are near the end of `index.html`.
- Theme, layout, and responsive rules live in `styles.css`.

## Files

```text
.
├── index.html
├── styles.css
├── script.js
├── .nojekyll
├── robots.txt
├── sitemap.xml
├── assets/
│   └── rameez-karamat-bhatti-resume.pdf
└── README.md
```

## Notes

- The site is mobile-friendly and keyboard accessible.
- Motion respects the visitor's reduced-motion setting.
- Google Fonts are the only external resource. The site still works if they are unavailable.
