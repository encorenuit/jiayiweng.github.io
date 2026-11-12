# Jiayi Weng Academic Website

A multilingual static website for GitHub Pages. It uses plain HTML, CSS, and JavaScript, so no build step is required.

## Pages

- `index.html` — home and selected work
- `research.html` — publications, working papers, work in progress, and conference records
- `experience.html` — education, work experience, honours, and capabilities
- `gallery.html` — personal photography archive

## Local preview

Run a static server from this directory:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173`.

## Add gallery photographs

Place optimized `.jpg`, `.webp`, or `.avif` files in `assets/gallery/`. Replace each `.photo-placeholder` block in `gallery.html` with a semantic `<figure>` containing the image and a `<figcaption>` for title, place, year, and optional camera notes.

Recommended image size: 1800–2400 px on the long edge, under 700 KB per file.

## Privacy

The site intentionally excludes phone numbers, home addresses, identity numbers, family details, and the private résumé source file. The published contact method is the academic email address only.
