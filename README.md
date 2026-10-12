# jystatistics.github.io

Personal academic website of Jongyun Jung, built with [al-folio](https://github.com/alshedivat/al-folio) (v1) and deployed to GitHub Pages by GitHub Actions.

## Where to edit

| What | File |
| --- | --- |
| Home page bio, title, address | `_pages/about.md` |
| Name, site description, analytics | `_config.yml` |
| Email, Scholar, ORCID, GitHub, LinkedIn links | `_data/socials.yml` |
| Publications (published and preprints) | `_bibliography/papers.bib` (add `selected = {true}` to show on the home page; `status = {preprint}` for under review) |
| Research project cards | `_projects/*.md` |
| News items | `_news/*.md` (one short file per item) |
| CV page | `_data/cv.yml`; PDF at `assets/pdf/CV_Jongyun_Jung.pdf` |
| Teaching | `_pages/teaching.md` |
| Photo and figures | `assets/img/` |

## Preview locally

```bash
bundle install
bundle exec jekyll serve   # then open http://localhost:4000
```

## Publishing

Push to `master`. The **Deploy site** action builds the site and pushes it to the `gh-pages` branch. In repository Settings → Pages, the source must be the `gh-pages` branch, and Settings → Actions → General → Workflow permissions must be "Read and write". Do not edit `gh-pages` by hand.

Full al-folio docs: https://github.com/alshedivat/al-folio/tree/main/docs
