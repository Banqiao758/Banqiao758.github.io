# Banqiao758

An independent, primary-source research archive on the August 1975 Banqiao
Dam disaster in Henan, China, published as a companion to an academic
monograph in progress. Live at https://Banqiao758.github.io/

Built with Jekyll (built in to GitHub Pages, no local install required to
publish). The site is bilingual: **Chinese is the default language**, served
from the repo root; English lives under `/en/`. Shared chrome is in
`_layouts/` and `_includes/`; styling is in `assets/css/style.css`. This
README and all repo-level metadata stay in English by convention — only the
site content itself is bilingual.

## Site structure

Each page exists twice — once in Chinese at the repo root, once in English
under `en/` — linked to each other via `alt_url` front matter and a language
switcher in the header.

| Chinese (default) | English | Page |
|---|---|---|
| `index.md` (`/`) | `en/index.md` (`/en/`) | Home, incl. Sources & Methodology (evidentiary standard) |
| `archive.md` | `en/archive.md` | Primary document catalog |
| `interviews.md` | `en/interviews.md` | Oral history |
| `photographs.md` | `en/photographs.md` | Photo catalog |
| `data.md` | `en/data.md` | Rainfall, engineering, casualty-estimate data |
| `maps.md` | `en/maps.md` | Maps and engineering models |
| `book.md` | `en/book.md` | Status of the companion book |
| `contact.md` | `en/contact.md` | Corrections and source contributions |

## Editing

Each page is Markdown with YAML front matter (`layout`, `title`, `permalink`,
`lang`, `alt_url`). Edit the `.md` files directly — no build step is needed
locally; GitHub Pages builds the site automatically on push to `main`. When
you add or change a page, keep its Chinese/English counterpart and `alt_url`
in sync so the language switcher keeps working.

To preview locally (optional), with Ruby and Bundler installed:

```
bundle exec jekyll serve
```

## Content policy

This site does not publish claims — especially casualty figures or timeline
specifics — that can't be traced to a primary source or a clearly attributed,
corroborated secondary source. See the Sources & Methodology section of
`index.md` (`en/index.md`) before adding content.
