<!-- ELUCENIA technical documentation · perc · de · no clinical/professional/rights approval -->

# PERC-Kriterien

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/perc)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Alter ≥ 50 Jahre

`idade`

### Herzfrequenz ≥ 100 bpm

`fc`

### O₂-Sättigung \< 95 % unter Raumluft

`sat`

### Einseitige Schwellung der unteren Extremität

`edema`

### Hämoptyse

`hemoptise`

### Operation oder Trauma mit Krankenhausaufenthalt in den letzten 4 Wochen

`cirurgia`

### Frühere TVT oder Lungenembolie

`tev`

### Östrogeneinnahme (Verhütung oder Hormonersatztherapie)

`hormonio`

## Fassung der Methode

PERC/Kline 2004: 8 negative Kriterien bei niedrigem Anfangsverdacht; keine automatische Entscheidung

## Dokumentierte Formel

Acht Ja/Nein-Fragen. PERC ist negativ nur bei ausschließlich „Nein“. Nur anwenden, wenn ärztlich bereits eine niedrige Wahrscheinlichkeit klinisch vorliegt (Gestalt \< 15%).

## Grenzen und Population

PERC 2004 wurde bei Notfallpatienten entwickelt, die auf Lungenembolie untersucht wurden, und in Gruppen mit geringem und sehr geringem Risiko getestet. Alle acht Kriterien müssen gleichzeitig negativ sein, einschließlich Alter \< 50 Jahre, Puls \< 100/min und Sättigung \> 94% in der Originalstudie. Die Regel bestimmt kein Nullrisiko; ihre Anwendbarkeit hängt von der vorherigen Populationsauswahl ab. Zeitdefinitionen und Einschlusskriterien müssen in der verwendeten Version geprüft werden.

## Referenzen

- [Kline JA et al. Clinical criteria to prevent unnecessary diagnostic testing in emergency department patients with suspected pulmonary embolism. J Thromb Haemost, 2004.](https://doi.org/10.1111/j.1538-7836.2004.00790.x)

- [Freund Y et al. Effect of the Pulmonary Embolism Rule-Out Criteria on subsequent thromboembolic events among low-risk emergency department patients: the PROPER randomized clinical trial. JAMA, 2018.](https://doi.org/10.1001/jama.2017.21904)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

PERC negativ: LE ohne D-Dimer ausgeschlossen, wenn die Vortestwahrscheinlichkeit niedrig ist (< 15%)

In diesem Kontext ist keine weitere Abklärung auf LE erforderlich.


### 2

PERC positiv: schließt LE nicht aus

Mit D-Dimer fortfahren (oder mit dem Wells-/Genf-Algorithmus).


### 3

PERC positiv: schließt LE nicht aus

Mit D-Dimer fortfahren (oder mit dem Wells-/Genf-Algorithmus).

