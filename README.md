# Farmen in Angola – interaktive Karte

Statische Webseite (GitHub Pages) mit Farmen, Handelsplätzen und Orten in Angola.
Personen erscheinen **nur als Referenznummer**. Die Zuordnung Nummer → Name liegt
ausschließlich offline (PDF) und gehört **nicht** in dieses Repository.

## Inhalt
- `index.html` – Karte (Leaflet + MarkerCluster, Kartengrundlagen OpenTopoMap / OSM / Esri-Luftbild)
- `data.js` – anonymisierte Daten (Nr, Art, Farmname, Bewirtschaftung, Fläche, Höhe, Mitglied, Koordinaten)

## Funktionen
- Suche nach Referenznummer (auch per Link: `…/#137`)
- Filter: Art, Mitgliedschaft, Bewirtschaftung, Höhe, Fläche, Sammelpunkte
- Liste und Statistik zur aktuellen Auswahl
- Gestrichelte Nummern = genäherte Lage (Ortszentrum/Region)

## Veröffentlichen
Repository → Settings → Pages → Branch `main`, Ordner `/ (root)` → Save.
Alles kostenlos, kein Build-Schritt nötig.
