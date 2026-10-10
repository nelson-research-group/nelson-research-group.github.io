# Taylor F. Nelson – personal website


Built with the free [Academic Pages](https://github.com/academicpages/academicpages.github.io) template and hosted on GitHub Pages.
Live at: https://nelson-research-group.github.io

## Where to edit things

You can edit any file directly on github.com: open it, click the pencil icon, make your change, then click **Commit changes**. The site updates by itself 1–2 minutes later.

| To change...                         | Edit this file                                  |
|--------------------------------------|-------------------------------------------------|
| Home page text                       | `_pages/about.md`                               |
| Research page                        | `_pages/research.md`                            |
| CV page                              | `_pages/cv.md`                                  |
| Sidebar (bio, email, links)          | `_config.yml` (the `author:` section)           |
| Top menu                             | `_data/navigation.yml`                          |
| Profile photo                        | Replace `images/profile.png` (keep the same name) |
| Supervision list (Teaching page)     | `_pages/teaching.html`                          |

## Adding a new publication

1. Open the `_publications` folder and click **Add file → Create new file**.
2. Name it like `2027-01-01-shortname.md` (the date controls the order; newest appears first).
3. Paste this in and fill it out:

```
---
title: 'Paper title'
collection: publications
category: manuscripts
permalink: /publication/shortname
date: 2027-01-01
venue: 'Journal Name'
citation: 'Author, A.; <b>Nelson, T. F.</b> Paper title. <i>Journal Name</i> <b>2027</b>, 1, 1–10.'
---

[Read the paper](https://doi.org/...)
```

## Adding a course or a talk

Copy an existing file in `_teaching` and change the details. For talks, add files to `_talks` (see the Academic Pages guide), then uncomment the "Talks" lines in `_data/navigation.yml`.

## Formatting notes

- Text formatting uses Markdown: `**bold**`, `*italic*`, `[link text](https://...)`.
- In `.yml` files, indentation matters. Keep the spacing exactly as it is.
