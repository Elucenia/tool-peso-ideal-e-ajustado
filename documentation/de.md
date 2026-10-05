<!-- ELUCENIA technical documentation · peso-ideal-e-ajustado · de · no clinical/professional/rights approval -->

# Idealgewicht und angepasstes Gewicht

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/peso-ideal-e-ajustado)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Geschlecht

`sexo`

- `F` — Weiblich
- `M` — Männlich

### Körpergröße

`altura`

cm · Bereich: 120–230

### Tatsächliches Gewicht (für angepasstes Gewicht)

`peso`

kg · optional · Bereich: 25–350

## Fassung der Methode

Devine 1974/Robinson 1983/Miller 1983; Pai–Paloucek-Review 2000; lokaler Faktor 0,4 für angepasstes Gewicht

## Dokumentierte Formel

Idealgewicht (Devine): Männer 50 kg + 2,3 kg je Zoll über 5 Fuß; Frauen 45,5 kg + 2,3 kg je Zoll über 5 Fuß. In Zentimetern: 50 (45,5) + 2,3 × (Größe − 152,4) ÷ 2,54.

Angepasstes Gewicht = Idealgewicht + 0,4 × (tatsächliches Gewicht − Idealgewicht).

## Grenzen und Population

Idealgewicht ist eine Schätzung aus Größen-Gewichtstabellen, keine Messung der fettfreien Masse. Die pharmakokinetische Beziehung variiert je Arzneimittel; dieses Abstract bestätigt keinen universellen Anpassungsfaktor 0,4. Die Gewichtsauswahl für Dosierungen muss Arzneimittelquelle und entsprechende Population berücksichtigen.

## Referenzen

- [Pai MP, Paloucek FP. The origin of the "ideal" body weight equations. Ann Pharmacother, 2000.](https://doi.org/10.1345/aph.19381)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
