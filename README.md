# Produktionsprozess-Analyse mit Pandas

In diesem Projekt wird ein realistischer Produktionsdatensatz analysiert.
Ziel ist die strukturierte Datenaufbereitung sowie die Berechnung zentraler
Produktionskennzahlen (KPIs) mit Python und pandas.

---

## Projektstruktur

data/
- produktionsdaten_premium_5Jahre.csv

notebooks/
- 01_data_overview_and_cleaning.ipynb
- 02_kpis_production.ipynb

---

## Schritt 1: Datenübersicht & Datenbereinigung

In diesem Schritt wurden folgende Aufgaben durchgeführt:

- Laden und erste Analyse des Datensatzes
- Prüfung der Datenstruktur und Datentypen
- Umwandlung von Datentypen (numerisch & kategorisch)
- Analyse und Behandlung fehlender Werte
- Prüfung auf Duplikate
- Fachliche Plausibilitätsprüfungen  
  (z. B. Stillstandszeiten, Temperaturen, Ausschuss)

**Ergebnis:**  
Ein konsistenter und auswertbarer Datensatz als Grundlage für weitere Analysen.

---

## Schritt 2: Produktions-KPIs

Berechnung zentraler Produktionskennzahlen, u. a.:

- Ausschussquote (%)
- Energieverbrauch pro Stück
- Stillstandsanteil (%)
- Gesamt- und durchschnittliche Produktionsmenge

Zusätzlich:
- Vergleich der KPIs nach Produktionslinie
- Vergleich der KPIs nach Schicht

Diese Kennzahlen dienen als Basis für Prozessanalysen und Optimierungsansätze.

---

## Verwendete Technologien

- Python
- pandas
- Jupyter Notebook
- Git & GitHub

---

## Nächste Schritte

- Visualisierung der KPIs (Diagramme)
- Zeitliche Analysen (Trends)
- Ableitung von Optimierungspotenzialen
