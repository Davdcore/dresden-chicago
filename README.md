# Dresden-Chicago

Das Kampagnen-Wiki liegt als Markdown in `docs/`. Die Inhalte sind nach
Einleitung, Geschichte, Geografie, Kreaturen, Fraktionen und
Nicht-Spieler-Charakteren sortiert und werden von MkDocs Material als
Wiki mit automatischer Navigation veröffentlicht.

## Lokal anzeigen

```sh
pip install -r requirements-docs.txt
mkdocs serve
```

GitHub Actions prüft den Wiki-Build bei Pull Requests und veröffentlicht die
Seite nach Änderungen auf `main` über GitHub Pages.
