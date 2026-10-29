# Power BI und Excel – Analyse und Visualisierung

Dieses Repository enthält Übungsdateien zum Kurs **„Power BI und Excel – Analyse und Visualisierung von Daten“** der ppedv AG. Die Power-BI-Dateien behandeln das Laden und Transformieren von Daten, Measures, Kalender und Visualisierungen. Im Ordner `Datenquellen` liegen die dazugehörigen Beispieldaten.

## Inhalt

### Power-BI-Übungen

| Datei | Thema |
|---|---|
| `Lab1_Datenladen und transformieren.pbix` | Daten laden und transformieren |
| `Lab2_maneulle Daten.pbix` | Manuelle Dateneingabe |
| `Lab3_DatenausURL.pbix` | Daten aus einer URL laden |
| `Lab4_Measures und Kalender.pbix` | Measures und Kalender |
| `Lab5_Visuals.pbix` | Visualisierungen |
| `Lab6_Visuals2.pbix` | Weitere Visualisierungen |
| `Lab_Datenladen und transformieren.pbix` | Ebenfalls Daten laden und transformieren; inhaltlich identisch mit Lab 1 |

Die Dateien mit der Endung `.pbix` lassen sich mit Power BI Desktop öffnen.

### Beispieldaten (`Datenquellen/`)

| Datei | Inhalt |
|---|---|
| `Adventure Works Sales Data.xlsx` | Adventure-Works-Verkaufsmodell mit Kunden, Produkten, Datum, Währung, Promotion, Vertriebsgebieten und Internetverkäufen |
| `Financial Sample.xlsx` | Finanz-Beispieldaten |
| `Kundendaten.xlsx` | Kundendaten |
| `Produktionsdaten.xlsx` | Maschinen, Produkte, Produktionsprozesse und Qualitätskontrolle |
| `Verkäufe.xlsx` | Verkäufe, Produkte und Kunden |
| `Zeitdimension.xlsx` | Zeitdimension |
| `instnwnd.sql` | SQL-Server-Skript zum Erstellen und Befüllen der Northwind-Beispieldatenbank |

## Verwendung

Öffne eine `.pbix`-Datei in Power BI Desktop und verwende bei Bedarf die Beispieldateien aus `Datenquellen` als Datenquelle. Je nach Übung müssen die Datenquellen in Power BI gegebenenfalls auf den lokalen Speicherort angepasst werden.

> **Achtung:** `Datenquellen/instnwnd.sql` löscht eine bereits vorhandene Datenbank namens `Northwind`, bevor es sie neu erstellt. Führe das Skript daher nur aus, wenn das beabsichtigt ist.
