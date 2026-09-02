# Personlig affärsplan - AI-effekt och kostnadshemtagning

Det här repot innehåller en statisk HTML-presentation för Eriks personliga affärsplan.

## Öppna lokalt

Öppna `index.html` direkt i webbläsaren.

## Publicering

Sidan publiceras via GitHub Pages varje gång kod pushas till `main`.

Första gången behöver GitHub Pages aktiveras i repot:

1. Gå till `Settings` i GitHub-repot.
2. Välj `Pages`.
3. Under `Build and deployment`, välj `GitHub Actions`.
4. Spara.

Efter det räcker det att checka in och pusha:

```bash
git add .
git commit -m "Uppdatera sidan"
git push
```

GitHub Actions publicerar då innehållet automatiskt.

## Filstruktur

- `index.html` - startsidan som GitHub Pages publicerar.
- `personlig-affarsplan-ai.html` - samma presentation med ursprungligt filnamn.
