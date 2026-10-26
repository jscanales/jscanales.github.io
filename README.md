# jscanales.github.io

Source of the personal website of **Jorge Sánchez Canales**, PhD student in Governance at the Hertie School (Berlin), working on electricity markets.

Live site: <https://jscanales.github.io>

## How it is built

- [Jekyll](https://jekyllrb.com/) with the [al-folio](https://github.com/alshedivat/al-folio) theme (MIT licence, see `LICENSE`), hosted on GitHub Pages.
- Publications come from `_bibliography/papers.bib`.
- The CV PDF is generated from `_data/cv.yml` by a GitHub workflow.

To preview locally: `docker compose up`, then open <http://localhost:8080>.
