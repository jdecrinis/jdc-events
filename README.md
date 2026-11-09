# jdc-events.at

Website von JDC Events (Johannes de Crinis, Graz). Statische Seite, gehostet über GitHub Pages.

## Aufbau

- `index.html` – Startseite (Leistungen, Über mich, Referenzen, Aktuelles, Ablauf, Kontakt, Häufige Fragen)
- `impressum.html`, `datenschutz.html` – Rechtliches
- `img/` – Fotos (JPG, max. 1800 px lange Kante, Qualität ~80)
- `fonts/` – Schrift Inter, lokal eingebunden (keine Verbindung zu Google)
- `CNAME` – eigene Domain für GitHub Pages (`jdc-events.at`)

## Änderungen

Jede Änderung, die in den Branch `main` gespeichert wird, ist nach ca. einer Minute live.

- Neues Foto: Datei nach `img/` legen und in `index.html` an der passenden Stelle als `<img loading="lazy" ...>` einfügen.
- Neue Referenz: Eine bestehende Referenz-Karte (`<article>` im Abschnitt `#referenzen`) kopieren und anpassen.
- Farben und Schrift stehen oben in `index.html` im `<style>`-Block.

## Aktuelles

Abschnitt `#aktuelles` in `index.html`, zwischen Referenzen und Kontakt. Die Vorlage für einen Beitrag steht im Kommentar direkt über dem Abschnitt.

- Fotos nach `img/aktuelles/` legen, Dateiname `JJJJ-MM-TT-kurzname.jpg`, als JPG mit max. 1800 px langer Kante und Qualität ~80.
- Neuen Beitrag direkt unter `<!-- BEITRÄGE START -->` einfügen (neueste zuerst).
- Text kurz halten: Titel plus ein bis drei Sätze, nur das, was Johannes selbst geschrieben hat.
- Beim allerersten Beitrag: `hidden` aus `<section id="aktuelles" ...>` entfernen und den auskommentierten Menülink `#aktuelles` aktivieren.
- Ab etwa 9 Beiträgen die ältesten entfernen, damit die Seite schlank bleibt.
