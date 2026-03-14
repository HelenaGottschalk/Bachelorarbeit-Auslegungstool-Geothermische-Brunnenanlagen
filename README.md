# Auslegungstool für geothermische Brunnenanlagen
Mit Python und Jupyter Notebook

In Bearbeitung seit Dezember 2025 (Abgabe 15.03.2026)
## Kurzbeschreibung:
Das Jupyter Notebook ist ein strukturiertes Auslegungswerkzeug zur Planung oberflächennaher geothermischer Brunnenanlagen. 

Es hat 4 Abschnitte: 
1. Berechnung der Wärmeleistung der Anlage
2. Hydrogeologische Berechnungen
3. Brunnendimensionierung
4. Auswertung/Zusammenfassung der Ergebnisse

## Installation:
Neben den in Python enthaltenen Standardbibliotheken werden folgende externe Bibliotheken benötigt:
- numpy
- pandas
- matplotlib
- IPython.display
- ipywidgets
- sklearn.linear_model
- sklearn.metrics
- sympy
- math
  
Zur Installation folgende Zeile für Projektordner im Command Prompt ausführen: pip install -r requirements.txt

## Nutzung des Notebook:
Das Jupyter Notebook kann u.a. im Webbrowser mit Anaconda Navigator oder in Visual Studio Code geöffnet und ausgeführt werden.
Es wird nicht empfohlen das Notebook von oben bis unten in Einem durchlaufen zu lassen ("Run all cells"), sondern sich stattdessen zellenweise vorzuarbeiten, um Eingabefelder auszufüllen.
Werden alle benötigten Eingabedaten im Vorfeld gesammelt, kann das Notebook innerhalb weniger Minuten durchgearbeitet werden.

Die benötigten Eingabedaten sind:
1. Abschnitt:
   - Gewählter Standort
   - URL für Standort auf klimadiagramme.de
   - Gebäudetyp (Auswahl)
   - Gebäudefläche
   - Betriebsart (Auswahl)
   - Spezifische Heizlast/ Kühllast (Richtwerte gegeben)
   - COP Heizen/Kühlen der Wärmepumpe
   - Gewünschte Temperaturspreizung
2. Abschnitt:
   - Brunnendurchmesser
   - kf-Wert
   - Filterlänge
   - Hydraulischer Gradient

