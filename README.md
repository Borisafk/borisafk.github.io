# Bona Lingua — Microsite

Eine schlanke, statische Microsite für GitHub Pages, gestaltet im CI von [hannover-logopaedie.de](https://hannover-logopaedie.de).

## Veröffentlichen auf GitHub Pages

1. Repository erstellen: `borisafk.github.io` (genau dieser Name → User-Site)
2. Dateien dieses Ordners pushen
3. Unter **Settings → Pages**: Source = `Deploy from branch`, Branch = `main`, Folder = `/ (root)`
4. Erreichbar unter: `https://borisafk.github.io/`

## Struktur

| Datei | Zweck |
|---|---|
| `index.html` | Komplette Microsite (HTML + inline CSS + JS) |
| `.nojekyll` | Verhindert Jekyll-Verarbeitung |
| `README.md` | Diese Datei |

## Design

- **Typografie:** Fraunces (Display, Variable Font mit `opsz` & `SOFT` Achsen) + Manrope (Body)
- **Farben:** Cream `#fbf6ee`, Tinte `#221608`, Brand-Orange `#ef9d32`, dunkles Akzent-Orange `#b35c00`
- **Aesthetik:** Editoriell, asymmetrisch, mit ruhigem Magazin-Layout und subtilen Mikro-Interaktionen

## Inhalt

Die Microsite bewirbt die Bona Lingua GmbH und alle 7 Standorte in Hannover & Region. Alle CTAs verlinken auf die Hauptseite oder direkte Telefon-/E-Mail-Verbindungen.

## Anpassungen

- Telefonnummer und E-Mail in `index.html` zentral pflegen
- Standort-Adressen aus `D:\BonaLingua\locations.md` übernommen
- Bei Änderungen am CI: CSS-Variablen in `:root` (oben in `<style>`) anpassen
