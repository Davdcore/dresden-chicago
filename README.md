# Dresden-Chicago

Das Kampagnen-Wiki wird mit dem World Building Framework (WBF) verwaltet.
WBF erzeugt zwei getrennte Wiki-Varianten:

- `player-wiki` enthält das Spielerwissen sowie ausdrücklich freigegebene
  Charaktere und Ereignisse.
- `gm-wiki` enthält alle migrierten Seiten.

## Lokal bauen

```sh
npm ci
npx wbf setup-quartz
npx wbf publish --output site
```

GitHub Actions veröffentlicht beide Varianten nach Änderungen auf `main` über
GitHub Pages.
