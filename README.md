# ANVERTRAUT Begleiter

Mobile-first PWA für Pflegeeltern. Version 0.1.

## Funktionen
- Dashboard
- Unverbindlicher Rechner für einen bereits bestätigten monatlichen Zuschuss
- Checkliste und lokale Notizen
- Allgemeine FAQ
- Link zur ANVERTRAUT-Website
- Offline-Caching nach erstem Besuch

## Datenschutz
Keine Konten, kein Backend, keine Analytics, keine Speicherung auf einem Server. Checklisten und Notizen liegen ausschließlich im localStorage des jeweiligen Browsers. Keine personenbezogenen Daten von Pflegekindern eingeben. Bei Löschung der Browserdaten gehen Einträge verloren.

## Veröffentlichung
GitHub Pages: Settings > Pages > Deploy from a branch > main > / (root).

## Entwicklung
HTML/CSS/JS ohne externe Laufzeit-Abhängigkeiten. Automatisierte Smoke-Checks in GitHub Actions. Vor produktivem Einsatz sind fachliche und rechtliche Prüfungen der Inhalte und Datenschutzhinweise erforderlich.
