# Produktionsprozess-Analyse mit Pandas

In diesem Projekt wird ein realistischer Produktionsdatensatz analysiert.
Ziel ist die strukturierte Datenaufbereitung sowie die Berechnung und
Auswertung zentraler Produktionskennzahlen (KPIs) mit Python, pandas und matplotlib.

---

## Projektstruktur

data/
- produktionsdaten_premium_5Jahre.csv

notebooks/
- 01_data_overview_and_cleaning.ipynb
- 02_kpis_production.ipynb
- 03_visualization.ipynb

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

### KPI-Interpretation

Die berechneten Produktionskennzahlen zeigen Unterschiede zwischen
Produktionslinien und Schichten und liefern konkrete Ansatzpunkte
für Prozessoptimierungen.

---

## Schritt 3: Visualisierung & fachliche Interpretation

Die berechneten KPIs wurden mithilfe von Diagrammen visualisiert,
um Unterschiede und Zusammenhänge übersichtlich darzustellen.

Visualisiert wurden unter anderem:
- Ausschussquote nach Produktionslinie
- Stillstandsanteil nach Schicht
- Energieverbrauch pro Stück nach Produktionslinie
- (optional) zeitliche Trends ausgewählter KPIs

Die Visualisierungen ermöglichen eine schnelle Einordnung der
Produktionsleistung und unterstützen die fachliche Interpretation
der Ergebnisse.

---

## Verwendete Technologien

- Python  
- pandas  
- matplotlib  
- Jupyter Notebook  
- Git & GitHub  

---

## Fazit

Das Projekt zeigt, wie Produktionsdaten strukturiert aufbereitet,
analysiert und verständlich visualisiert werden können.
Die Ergebnisse liefern eine fundierte Grundlage zur Identifikation
von Optimierungspotenzialen in Qualität, Effizienz und Prozessstabilität.
