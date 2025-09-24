# Flachdach – PWA (iOS/Apple ready)

Interaktive 2D-App zur Visualisierung (Draufsicht, Vorder- & Seitansicht).
- Feste SVG-ViewBox (20 m Referenz), Haus skaliert innerhalb des Rahmens
- DG in allen Ansichten verschiebbar (Clamping)
- „Vollgeschoss“-Overlay in fixer Bildschirmgröße
- PWA: Manifest + Service Worker, Apple-Meta-Tags, Apple Touch Icon

## Dateien
- `index.html` – App inkl. SW-Registrierung und Apple Meta
- `manifest.webmanifest` – PWA Manifest
- `sw.js` – Service Worker (Network-first für Navigation, SWR für Assets)
- `offline.html` – Offline-Fallback
- `icons/` – 192, 512, maskable 512, Apple Touch 180

## iOS Installationshinweis
1. Seite im Safari öffnen
2. Share-Button → „Zum Home-Bildschirm“

## GitHub Pages
- Repo → Settings → Pages → Branch `main`, Ordner `/` (root)
- App-URL: `https://<username>.github.io/<repo>/`

Lizenz: MIT
