# prantardutta.github.io

Personal website of Prantar Dutta, built with plain Jekyll and served by GitHub Pages. There is no theme, so nothing needs to be updated upstream.

## Where things live

| To change | Edit |
|---|---|
| Name, emails, profile links, CV path | `_config.yml` (the `author:` block) |
| About text, page sections | `index.html` |
| Positions, education, methods | `_data/cv.yml` |
| Research projects (titles, text, figures, linked papers) | `_data/projects.yml` |
| Publications | `_data/publications.yml` |
| Conference talks and posters | `_data/conferences.yml` |
| Colours and typography | `assets/css/main.css` (variables at the top) |
| Photo | `images/prantar.jpg` |
| CV | `files/Prantar_CV.pdf` |

## Common tasks

**Add a publication.** Copy an entry in `_data/publications.yml`, put it at the top, and fill in the fields. Your name is bolded wherever it appears as `P. Dutta`. Years are grouped automatically.

**Add a research figure.** Save the image (PNG or JPG, about 1600 px wide, 4:3) in `images/research/`, then set `image:` and `image_credit:` for that project in `_data/projects.yml`.

**Add GitHub.** Set `github:` in `_config.yml` to your profile URL; the link appears on the home page.

**Change the university email.** Edit the second entry under `emails:` in `_config.yml`, or delete it.

## Preview locally

```
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
