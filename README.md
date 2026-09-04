# Banqiao758

An independent, primary-source research archive on the August 1975 Banqiao
Dam disaster in Henan, China, published as a companion to an academic
monograph in progress. Live at https://hzhang4.github.io/Banqiao758/

Built with Jekyll (built in to GitHub Pages, no local install required to
publish). Content pages live at the repo root as `.md` files with front
matter; shared chrome is in `_layouts/` and `_includes/`; styling is in
`assets/css/style.css`.

## Site structure

- `index.md` — home
- `methodology.md` — sources & evidentiary standard for the whole site
- `archive.md` — primary document catalog
- `interviews.md` — oral history
- `photographs.md` — photo catalog
- `data.md` — rainfall, engineering, and casualty-estimate data
- `maps.md` — maps and engineering models
- `book.md` — status of the companion book
- `contact.md` — corrections and source contributions

## Editing

Each page is Markdown with YAML front matter (`layout`, `title`, `permalink`).
Edit the `.md` files directly — no build step is needed locally; GitHub Pages
builds the site automatically on push to `main`.

To preview locally (optional), with Ruby and Bundler installed:

```
bundle exec jekyll serve
```

## Content policy

This site does not publish claims — especially casualty figures or timeline
specifics — that can't be traced to a primary source or a clearly attributed,
corroborated secondary source. See `methodology.md` before adding content.
