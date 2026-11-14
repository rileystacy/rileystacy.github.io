# rileystacy.github.io

My academic website: a plain Jekyll site that GitHub Pages builds automatically. No theme or plugins are needed.

## Where to edit things

| What | File |
|---|---|
| Name, role, email, profile links, CV | `_config.yml` |
| Bio and Research paragraphs | `index.md` |
| Publications | `_data/publications.yml` |
| Photo | put it in `assets/img/` and set `author.photo` in `_config.yml` |
| CV | put the PDF in `assets/pdf/` and set `author.cv` |
| Colors and fonts | `assets/css/style.css` (change `--accent`) |

Push to `main`. The site updates at https://rileystacy.github.io in about a minute.

## Adding a page (e.g. Teaching)

Create `teaching.md`:

```markdown
---
layout: page
title: Teaching
permalink: /teaching/
---

Your content in Markdown.
```

Then add it to `nav:` in `_config.yml`:

```yaml
  - title: Teaching
    url: /teaching/
```
