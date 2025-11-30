# Rammsondierung – PWA

Kompakte Web-App zur schnellen Auswertung einer leichten Rammsondierung (DPL) bis 3,0 m Tiefe.

## Funktionen
- Eingabe der Schlagzahlen pro 10 cm als Tabelle oder Freitext
- Automatisches SVG-Diagramm mit Tiefenskala und Schlägen (N10)
- Kennzahlen (maximaler Wert, Durchschnitt, letzter Messpunkt)
- PWA-ready: Manifest, Service Worker, Offline-Seite und Apple-Meta-Tags

## Nutzung
1. Zahlen pro 10 cm eingeben oder Beispieldaten laden.
2. Diagramm wird direkt aktualisiert; fehlende Werte bleiben leer.
3. App lässt sich als PWA installieren (Homescreen, offline-fähig).

## Dateien
- `index.html` – UI und Diagramm-Logik
- `manifest.webmanifest` – PWA Manifest
- `sw.js` – Service Worker (Network-first für Navigation, SWR für Assets)
- `offline.html` – Offline-Fallback
- `icons/` – App-Icons

Lizenz: MIT
