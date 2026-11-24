# Dresden-Chicago

Das Kampagnen-Wiki wird mit dem World Building Framework (WBF) verwaltet.
WBF erzeugt zwei getrennte Wiki-Varianten:

- `player-wiki` enthält ausschließlich Seiten aus dem Spielerwissen.
- `gm-wiki` enthält alle migrierten Seiten.

## Lokal bauen

```sh
npm ci
npx wbf setup-quartz
npx wbf publish --output site
```

GitHub Actions veröffentlicht beide Varianten nach Änderungen auf `main` über
GitHub Pages.
