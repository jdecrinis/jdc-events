# jdc-events.at

Website von JDC Events (Johannes de Crinis, Graz). Statische Seite, gehostet über GitHub Pages.

## Aufbau

- `index.html` – Startseite (Leistungen, So arbeiten wir, Über mich, Referenzen, Kontakt)
- `impressum.html`, `datenschutz.html` – Rechtliches
- `img/` – Fotos (JPG, max. 1800 px lange Kante, Qualität ~80)
- `fonts/` – Schrift Inter, lokal eingebunden (keine Verbindung zu Google)
- `CNAME` – eigene Domain für GitHub Pages (`jdc-events.at`)

## Änderungen

Jede Änderung, die in den Branch `main` gespeichert wird, ist nach ca. einer Minute live.

- Neues Foto: Datei nach `img/` legen und in `index.html` an der passenden Stelle als `<img loading="lazy" ...>` einfügen.
- Neue Referenz: Eine bestehende Referenz-Karte (`<article>` im Abschnitt `#referenzen`) kopieren und anpassen.
- Farben und Schrift stehen oben in `index.html` im `<style>`-Block.
