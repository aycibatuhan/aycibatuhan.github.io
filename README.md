# aycibatuhan.github.io

Personal academic website for **Batuhan Ayci, MD** — postdoctoral fellow in the
Department of Neurology (neuroimmunology / advanced MRI) at the Icahn School of
Medicine at Mount Sinai.

Static single-page site (plain HTML + CSS), adapted from
[Jon Barron's academic template](https://github.com/jonbarron/jonbarron.github.io).

## Structure

- `index.html` — the page
- `stylesheet.css` — styles; Lato is self-hosted from `assets/fonts/`
- `assets/` — images, institution logos, favicon, and CV
- `assets/originals/` — full-resolution source images (git-ignored local backups;
  the site serves the down-sized copies in `assets/`)

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy (GitHub Pages — user site)

1. Create a GitHub repository named **`aycibatuhan.github.io`**.
2. Push this folder to it (`main` branch).
3. In the repo: **Settings → Pages → Deploy from branch → `main` / `root`**.

The site will be live at **https://aycibatuhan.github.io**. No build step is needed.

## Notes

- To add a Google Scholar link, uncomment the placeholder in the links row of
  `index.html` and drop in your profile URL.
- To use a real profile photo, replace `assets/profile-placeholder.svg` (and point
  the `og:image` / `twitter:image` tags at a real headshot for nicer link previews).
