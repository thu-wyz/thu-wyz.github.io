# thu-wyz.github.io

Personal homepage, served at **https://thu-wyz.github.io**.

Plain static HTML + CSS — no build step, no dependencies.

## Structure

```
index.html      # all content (intro, about, selected work, news)
style.css       # styling (light + dark mode, responsive)
assets/         # photo.jpg, paper1.png, paper2.png, ...
```

## Editing

Everything you need to fill in is marked with `<!-- TODO -->` in `index.html`:
- Intro / tagline / bio
- About paragraph
- Selected work (title, authors, venue, links)
- News items
- Social links (email, CV, Scholar, GitHub, Twitter)

Add your images to `assets/` (see `assets/README.md` for filenames).

## Preview locally

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Publishing

Push to `main`. GitHub Pages serves `index.html` from the repo root at
`https://thu-wyz.github.io` automatically (no extra config needed for a
`<user>.github.io` repo).
