# Restaurant.de Web-App

Eine mobile Web-App zum Durchstöbern und Bestellen von Gerichten nach Küche und Gang.

## Features

- 10 Küchen-Kategorien (Pizza, Burger, Sushi, Döner, ...)
- Filterung nach Gang (Vorspeisen, Hauptgerichte, Desserts, Getränke, Extras)
- Warenkorb mit Küchen-Sperre
- PWA-fähig: Zum Homebildschirm hinzufügen für App-Erlebnis

## Deployment

Gehostet auf [Vercel](https://vercel.com).

### Lokal testen

Einfach `index.html` im Browser öffnen oder einen lokalen Server starten:

```bash
npx serve .
```

## Dateistruktur

```
restaurant-app/
├── index.html        # Haupt-App
├── manifest.json     # PWA Manifest
├── vercel.json       # Vercel Konfiguration
├── icons/
│   ├── icon-192x192.png
│   ├── icon-512x512.png
│   ├── apple-touch-icon.png
│   ├── apple-touch-icon-152.png
│   ├── apple-touch-icon-167.png
│   ├── favicon-32.png
│   └── favicon-16.png
└── README.md
```

## Version

V. 1.0
