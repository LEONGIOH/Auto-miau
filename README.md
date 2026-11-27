# Auto-miau – Neon Drift City

Ein eigenständiges 2D-Open-World-Driftspiel für GitHub Pages – ohne Build-Schritt.

## Features
- Freie Fahrt durch eine große Stadt
- Drift-/Handbremsen-Mechanik mit Punktesystem
- Polizei-Verfolgung mit Heat-/Wanted-System (bis 3 Sterne)
- Tastatur- und Touch-Steuerung
- PWA-Service-Worker mit Offline-Cache
- Statische Dateien, kein Backend nötig

## GitHub Pages
Settings → Pages → Deploy from a branch → main → /(root).
Beim ersten HTTPS-Aufruf werden die Spieldateien gecacht; danach ist das Spiel offline verfügbar.

## Steuerung
- W / ↑: Gas
- S / ↓: Bremsen / rückwärts
- A / ←, D / →: Lenken
- Space: Handbremse / Drift
- P oder Esc: Pause
- R: Fahrzeug zurücksetzen

Service Worker benötigen HTTPS oder localhost. GitHub Pages liefert HTTPS. Die Schrift wird optional online geladen; lokale Fallbacks halten das Spiel offline spielbar.
