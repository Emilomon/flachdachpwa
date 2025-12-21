# Wir zwei – Check-in PWA

Eine minimalistische PWA für schnelle Paar-Check-ins: Stimmung teilen, Themen ablegen und kurze KI-Fragen erhalten, damit ihr verbunden bleibt, auch wenn wenig Zeit ist.

## Funktionen
- Stimmungs-Check-in mit Energie-Slider und Gesprächswunsch
- Offene Themen speichern und gefiltert anzeigen
- Kontextbezogene Fragen (lokal generiert) zur Reflexion
- Zusammenfassung für E kopieren
- PWA-ready: Manifest, Service Worker, Offline-Seite und Apple-Meta-Tags

## Nutzung
1. Namen eintragen, Stimmung wählen, Energie & Wunsch setzen.
2. Thema als kurze Notiz festhalten und speichern.
3. Fragen aktualisieren, wenn du neue Impulse brauchst.
4. Zusammenfassung kopieren und teilen.

## Dateien
- `index.html` – UI und lokale Logik für Check-ins, Fragen und Zusammenfassung
- `manifest.webmanifest` – PWA Manifest
- `sw.js` – Service Worker (Network-first für Navigation, SWR für Assets)
- `offline.html` – Offline-Fallback
- `icons/` – App-Icons

Lizenz: MIT
