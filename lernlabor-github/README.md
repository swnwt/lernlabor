# Lernlabor – GitHub Pages

Dieses Paket enthält die neue fachübergreifende Lernlabor-Website.

## Veröffentlichung
1. ZIP entpacken.
2. **Den Inhalt** des Ordners `lernlabor-github` in das Hauptverzeichnis des GitHub-Repositories hochladen (nicht den Ordner selbst).
3. Repository → Settings → Pages → Deploy from a branch → `main` → `/(root)`.
4. Einige Minuten warten und die GitHub-Pages-Adresse öffnen.

## Struktur
- Startseite `index.html`
- Fachseiten, z. B. `nwt/index.html`
- Klassenübersichten, z. B. `nwt/9/index.html`
- Eingebundene Lernumgebung: `nwt/9/seifenblasenmaschine/index.html`
- Symbole/Design: `assets/`

Die Regelungstechnik-Lernumgebung ist als geplantes Thema eingetragen, aber nicht eingebunden, weil ihre HTML-Datei hier nicht vorliegt.

Um Inhalte zu ändern, bearbeite die Angaben in `assets/data.js`. Zusätzlich bitte auch `assets/catalog.json` konsistent halten, sofern du diese Metadaten-Datei verwendest.

GitHub Pages benötigt keinen Server und keine Datenbank.
