# Financial Wellbeing Dashboard - HoFT

Ein interaktives Dashboard zur Analyse der persönlichen finanziellen Situation, entwickelt vom House of Finance & Tech Berlin.

![HoFT Logo](https://hoft.berlin/logo.png)

## Über das Projekt

Das Financial Wellbeing Dashboard ermöglicht es Nutzern, ihre finanzielle Situation in drei Hauptbereichen zu analysieren und zu visualisieren:
- Finanzielle Basis
- Anlage & Vermögensbasis
- Risikoabsicherung

## Technologien

- HTML5
- JavaScript (Vanilla)
- Tailwind CSS für das Styling
- Chart.js für die Visualisierung der Daten

## Funktionen

- Eingabe und Berechnung von Finanzdaten in Echtzeit
- Automatische Scoring-Berechnung für jeden Finanzbereich
- Visualisierung der Vermögensaufteilung
- Personalisierte Handlungsempfehlungen
- Responsive Design für alle Bildschirmgrößen

## Verwendung

1. Einfach die Datei `financial-wellbeing-dashboard.html` in einem Webbrowser öffnen
2. Keine Installation oder zusätzliche Abhängigkeiten erforderlich
3. Eigene Finanzdaten eingeben, um eine personalisierte Analyse zu erhalten

## Anpassung

Das Dashboard kann leicht angepasst werden:

- Farben: CSS-Variablen im `<style>`-Bereich ändern
```css
:root {
    --hoft-blue: #001E62;    /* Hauptfarbe */
    --hoft-orange: #FF5C39;  /* Akzentfarbe */
    --hoft-light-blue: #345082;  /* Sekundärfarbe */
}
```

- Berechnungslogik: In den JavaScript-Funktionen `updateFinanzielleBasis()`, `updateAnlageVermoegen()` und `updateRisikoabsicherung()` anpassen

- Empfehlungen: In der Funktion `updateEmpfehlungen()` bearbeiten

## Dateien

- `financial-wellbeing-dashboard.html` - Komplette Anwendung (HTML, CSS und JavaScript)
- `screenshot.png` - Screenshot des Dashboards

## Browser-Kompatibilität

Getestet und funktioniert in allen modernen Browsern:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Lizenz

Eigenentwicklung des House of Finance & Tech Berlin (HoFT)

## Kontakt

House of Finance & Tech Berlin  
E-Mail: finwell@hoft.berlin  
Website: [hoft.berlin](https://hoft.berlin)
