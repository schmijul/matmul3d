# 3D Matrix Multiplikation

Interaktive 3D-Visualisierung der Matrixmultiplikation im Browser mit Three.js.

![Three.js](https://img.shields.io/badge/Three.js-0.164-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

- **3D-Animation** — Matrix A (blau), Matrix B (lila) und Ergebnis C (gruen) als schwebende Wuerfel im Raum
- **Step-by-step Berechnung** — zeigt fuer jedes Element C[i][j], welche Zeile und Spalte multipliziert werden
- **Partikel & Beams** — leuchtende Verbindungslinien und fliegende Partikel visualisieren den Datenfluss
- **Frei drehbare Kamera** — Orbit Controls per Maus (ziehen, scrollen, rechtsklick)
- **Konfigurierbare Matrizen** — Dimensionen bis 5x5, alle Werte frei eingebbar
- **Tempo-Regler** — Animation stufenlos schneller oder langsamer
- **Zero Dependencies** — einzelne HTML-Datei, Three.js wird per CDN geladen

## Schnellstart

```bash
# Lokalen Server starten
python3 -m http.server 8080

# Browser oeffnen
open http://localhost:8080
```

Alternativ: `index.html` direkt mit einem modernen Browser oeffnen (erfordert Import Maps Support).

## Bedienung

1. **Dimensionen** festlegen (Matrix A: M x N, Matrix B: N x P)
2. **Werte eingeben** oder **Zufall** klicken
3. **Berechnen** starten — die Animation zeigt Schritt fuer Schritt die Multiplikation
4. **Kamera drehen** per Maus, **Tempo** per Slider anpassen
5. **Zuruecksetzen** um von vorne zu beginnen

## Technologie

- [Three.js](https://threejs.org/) — 3D-Rendering mit WebGL
- Vanilla JavaScript (ES Modules)
- Keine Build-Tools noetig

## Lizenz

MIT
