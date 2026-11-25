---
name: kreativwerkstatt-ci
description: Corporate Identity der KreativWerkstatt (Alzey) – Logo, Hausfarben, Schrift und Gestaltungsregeln. Verwenden bei allem, was für die KreativWerkstatt selbst gestaltet wird – Website, Flyer, Plakate, Social-Media-Grafiken, Präsentationen, Angebote, Briefpapier, Canva- oder Moda-Designs, HTML-Seiten – sowie wenn der Nutzer "unsere CI", "unser Logo", "unsere Farben" oder "im KreativWerkstatt-Stil" sagt.
---

# KreativWerkstatt – Corporate Identity

Wende diese Vorgaben auf jedes Gestaltungsergebnis für die KreativWerkstatt an. Abschnitte mit **(festgelegt)** hat der Inhaber vorgegeben; Abschnitte mit **(Empfehlung)** sind abgeleitete Vorschläge, die noch nicht bestätigt sind – bei Zweifel nachfragen statt erfinden.

## Marke

- Name: **KreativWerkstatt** (ein Wort, großes K und großes W)
- Claim: **Ihr Partner in Sachen Werbung.** (mit Punkt)
- Standort: St.-Georgenstraße 9, 55232 Alzey · Website: www.kreatives-werben.de
- Leistungen: Design, Drucksachen, Digitaldruck, Beschriftungen, Schilder, Textildruck, Werbeartikel, Sportwerbung, Stempel, Videowall Alzey

## Logo (festgelegt)

- Datei: `assets/kreativwerkstatt-logo.png` – freigestellt (transparenter Hintergrund) mit leichter Schattierung. So und nicht anders verwenden.
- Aufbau: leicht gedrehte Cyan-Fläche, darauf ein leuchtend grünes und ein hellgelbes Quadrat, darunter Schriftzug „KreativWerkstatt“ und Claim in Weiß.
- Nicht verzerren, nicht umfärben, Schatten nicht entfernen oder verstärken, keine zusätzlichen Effekte.
- Auflösung der Datei: ca. 420 × 420 px. Reicht für Web und Social Media, **nicht** für Druck über ca. 3,5 cm Breite (300 dpi). Für Druck die Vektor-Originaldatei beim Inhaber anfordern.

**Anwendung (Empfehlung):** Schutzzone rundum mindestens 10 % der Logobreite. Bevorzugt auf Weiß oder ruhigen hellen Flächen; auf Cyan-Flächen nur mit deutlichem Abstand, damit das Logo nicht verschwimmt.

## Farben (festgelegt)

| Name | CMYK (Druck, verbindlich) | HEX (Bildschirm, Näherung) | Rolle |
|---|---|---|---|
| Cyan | C100 M0 Y0 K0 | `#009FE3` | Primärfarbe, Flächen, Hintergründe |
| Leuchtgrün | C40 M0 Y100 K0 | `#A8C81A` | Akzent, Hervorhebungen, Buttons |
| Hellgelb | C0 M0 Y40 K0 | `#FFF5B0` | Akzent-Flächen, Hinterlegungen |
| Weiß | C0 M0 Y0 K0 | `#FFFFFF` | Schrift auf Cyan, Freiraum |

- Im Druck gelten ausschließlich die CMYK-Werte. Die HEX-Werte sind aus dem Logo gemessene Bildschirm-Näherungen.
- **Textfarbe (Empfehlung):** Fließtext auf Weiß in dunklem Grau (`#1F2A30`) statt Schwarz. Weiß auf Cyan nur für Überschriften und große Schrift (Kontrast für kleinen Text zu gering). Text nie direkt auf Leuchtgrün oder Hellgelb in Weiß setzen – dort dunklen Text verwenden.

## Schrift

- **Hausschrift (festgelegt): Alternate Gothic No.2 BT** (Bitstream) – schmale, kräftige Grotesk, wie im Logo. Für Überschriften, Headlines, kurze Claims, Schilder- und Plakattexte; gern in Versalien.
- Für lange Fließtexte ist sie zu schmal. **Fließtext (Empfehlung, noch festzulegen):** eine gut lesbare Grotesk, z. B. Source Sans 3 oder Open Sans.
- **Web-Ersatz (Empfehlung):** Alternate Gothic No.2 BT ist kommerziell und nicht frei im Web nutzbar ohne Webfont-Lizenz. Ersatz: **League Gothic** (Google Fonts, Wiederbelebung der Alternate Gothic) oder **Oswald**.

```css
:root {
  --kw-cyan: #009FE3;
  --kw-gruen: #A8C81A;
  --kw-gelb: #FFF5B0;
  --kw-weiss: #FFFFFF;
  --kw-text: #1F2A30;
  --kw-font-headline: "Alternate Gothic No2 BT", "League Gothic", "Oswald", "Arial Narrow", sans-serif;
  --kw-font-text: "Source Sans 3", "Open Sans", Arial, sans-serif;
}
```

## Gestaltungsprinzipien (Empfehlung, aus dem Logo abgeleitet)

- Klare, flächige Farbfelder in den drei Hausfarben; leicht versetzte oder gedrehte Rechtecke mit abgerundeten Ecken greifen das Logo-Motiv auf.
- Cyan dominiert, Grün und Gelb sind Akzente (grobe Gewichtung 60 / 25 / 15).
- Viel Weißraum, wenige Elemente, große Headlines.
- Keine weiteren Markenfarben einführen; Fotos dürfen bunt sein.

## Tonalität (Empfehlung, aus der Website abgeleitet)

- Kunden siezen. Direkt, bodenständig, hilfsbereit, regional (Alzey/Rheinhessen).
- Konkret statt Werbefloskeln: was gemacht wird, aus welchem Material, wie schnell.

## Druckdaten (Empfehlung, Branchenstandard)

- CMYK, 300 dpi, 3 mm Beschnitt, Schrift in Pfade oder eingebettet, PDF/X-4 bzw. nach Vorgabe der Druckerei.
- Aus Claude erzeugte PDFs und Bilder sind RGB – als Entwurf/Vorschau verwenden, finale Druckdaten in InDesign, Affinity oder Canva (CMYK-Export) erstellen.
