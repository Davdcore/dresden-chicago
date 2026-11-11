# Überschrift
## Unterschrift
- Punkt
Text.
hoffentlich

## Wiki

The Markdown wiki lives in `test/` and is rendered with MkDocs Material.
Install the documentation dependencies and build it locally with:

The [Supernatural Chicago structure](Supernatural%20Chicago/README.md) provides
a local navigation outline with links to the original wiki.

```sh
pip install -r requirements-docs.txt
mkdocs serve
```

GitHub Actions builds the site for pull requests and publishes it to GitHub Pages
when changes reach `main`.
