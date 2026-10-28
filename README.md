# iHRIS 4.3 Documentation

Source for the iHRIS 4.3 documentation site: <https://ihris.github.io/ihris-4-documentation/>

The pages are Markdown files in `docs/`, built with [MkDocs](https://www.mkdocs.org/) and the [Material](https://squidfunk.github.io/mkdocs-material/) theme. The menu is set in `mkdocs.yml`.

## Publishing

Every push to `main` builds the site and publishes it to the `gh-pages` branch (`.github/workflows/main.yml`). GitHub Pages serves that branch.

## Previewing locally

```bash
pip install -r requirements.txt
mkdocs serve
```

Then open <http://127.0.0.1:8000>.

## Adding a page

1. Add a Markdown file under `docs/`.
2. Add it to `nav` in `mkdocs.yml`.

iHRIS 5 documentation is in a separate repository: [iHRIS/ihris-documentation](https://github.com/iHRIS/ihris-documentation).
