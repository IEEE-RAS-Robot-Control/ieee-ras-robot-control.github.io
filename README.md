# IEEE RAS Technical Committee on Robot Control — website

Source of <https://ieee-ras-robot-control.github.io>, built with [Jekyll](https://jekyllrb.com)
and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme. The theme is
vendored into this repository (`_includes/`, `_layouts/`, `_sass/minimal-mistakes/`, `assets/js/`)
so that GitHub Pages can build the site without extra plugins.

## Layout

| Path | Purpose |
| --- | --- |
| `_config.yml` | Site settings (title, logo, permalinks, plugins) |
| `_data/navigation.yml` | Top navigation menu |
| `_data/members.yml` | Co-chairs and student representatives shown on `/contact/` |
| `_data/awards.yml` | Best Paper Award winners, finalists and juries shown on `/awards/` and `/awards/<year>/` |
| `_pages/` | Static pages (`/awards/`, `/contact/`, `/events/`, `/spotlights/`, `/categories/`) |
| `_posts/` | Announcements and researcher spotlights |
| `_posts/award_winner/` | Best Paper Award interviews (hidden from lists, explicit permalinks) |
| `_layouts/events.html`, `_layouts/spotlights.html` | Site-specific archive layouts |
| `_layouts/award-year.html`, `_includes/award-paper.html` | Per-year award page and paper card |
| `_sass/custom/custom.scss` | All site-specific styling |
| `assets/images/` | Logos, member photos, spotlight and award images |

Everything else under `_includes/`, `_layouts/` and `_sass/minimal-mistakes/` is the theme.
Site-specific edits to theme files are kept small: `_includes/footer.html`, `_includes/head.html`
(favicon), `_layouts/categories.html`, `_layouts/single.html` (`hide_title`), and a few SCSS
partials (full-width layout, logo sizes).

## Adding content

Posts live in `_posts/` and are named `YYYY-MM-DD-slug.md`. The URL is
`/<category>/<slug>/`, so keep the category and file name stable once published.

```yaml
---
title: "Post title"
categories:
  - Announcements      # or Spotlights
tags:
  - Event              # posts tagged "Event" appear on /events/
---
```

- **Announcements** → `categories: [Announcements]`, listed on `/categories/`.
- **Researcher spotlights** → `categories: [Spotlights]`, listed on `/spotlights/`. Put the photo
  under `assets/images/researcher_spotlight/YYYY-MM/`.
- **Events** → add the `Event` tag; they are listed on `/events/`.
- **Best Paper Award results** → add a block for the year to `_data/awards.yml` and copy
  `_pages/awards/2025.md` to `_pages/awards/<year>.md` (change `title`, `permalink`, `year`).
  The overview at `/awards/` and the year page are generated from the data. Set `open_call`
  in the same file while a call for nominations is open.
- **Award winner interviews** → put the file in `_posts/award_winner/`, set `hidden: true` and an
  explicit `permalink:`, then reference it as `interview:` in `_data/awards.yml`.
- **Members** → edit `_data/members.yml` and add the photo under `assets/images/members/`.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.
