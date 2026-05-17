# EuroLense – Deutschland Portal 2026

Politisches Bildungsportal für Schüler und Lehrkräfte.

## 🚀 Live-URL
Nach dem ersten Deployment erreichbar unter:
`https://[dein-github-username].github.io/eurolense/`

## 📁 Struktur
```
├── index.html              ← Das Portal (wird als Website ausgespielt)
└── .github/
    └── workflows/
        └── deploy.yml      ← Automatisches Deployment täglich 06:00 Uhr
```

## ⚡ Live-Nachrichten aktivieren
1. Portal öffnen → Schüler-Ansicht
2. Beim ersten Bundesland: API-Key eingeben (von console.anthropic.com)
3. Key wird lokal im Browser gespeichert (localStorage)
4. Ab jetzt: jedes Bundesland lädt frische Nachrichten per KI

## 🔄 Automatisches Update
GitHub Actions deployed das Portal täglich neu (06:00 Uhr).
Für Datenaktualisierungen: neue `index.html` in den `main`-Branch pushen.

## 🔒 Sicherheit
- API-Key wird nur lokal im Browser gespeichert, nie an Server übermittelt
- Kein Backend, kein Server – reines Static Hosting
