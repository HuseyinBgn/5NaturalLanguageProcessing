Name des Projekts:	NLP Projekt

Link zum MyBinder: 	[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/HuseyinBgn/5NaturalLanguageProcessing/HEAD)

Doku:	

Die Beispiele der Übungsaufgabe befinden sich in der NLP.ipynb Datei.
Die erwarteten Ergebnisse sind unterhalb der jeweiligen Befehle dargestellt. 

Hinweis: Um das erwartete Ergebnis nicht zu verlieren wird empfohlen eine Zwischenzeile zw. dem Befehl 
und dem bereits stehendem Ergebnis hinzufügen bevor das Befehl ausgeführt wird!

Zum Ausführen der einzelnen Code-Zeilen "STRG" + "Enter" Tasten drücken.
Beachten Sie keine der Zeilen zu überspringen, denn sonst kann es zu Fehlerhaften Ausführung führen.

1. Libraries installieren & importieren: 
- Librairies für die Datenverarbeitung und -visualisierung werden installiert und anschließend importiert.

2. Die Daten:
- "Yelp.csv" Datei wird gelesen.
- Mit head(), info() und describe() Methoden wird auf die Korrektheit und Darstellung der Tabelle überprüft.

3. Explorative Datenanalyse:
- Facet Grid von Seaborn fuer 5 Histogramme der 5 Sterne.
- Box Plot der 5 Sterne.
- Countplot der 5 Sterne.
- Tabelle nach Sterne gruppieren und die Durchschnittswerte pro Spalte anzeigen.
- Korrelationstabelle der Sterne.
- Heatmap der obigen Korrelation.

4. NLP Klassifizierungsaufgabe:
- Nutzung des CountVectorizer Objekts und Überschreibung der X. 

5. Train Test Split:
- 30% der Daten zufällig für den Test trennen.

6. Das Modell trainieren:
- NLP-Modell mit Hilfe der Trainingsdaten trainieren.

7. Vorhersagen und Auswerten:
- Vorhersage mit predict() Methode
- Ausgabe der Ergebnisse und der Konfusionsmatrix von NLP-Modell.

8. Text Processing verwenden:
- Nutzung der Pipeline für die Text Processing.

9. Train Test Split
- 30% der Daten zufällig für den Test trennen.

10. Vorhersagen und Auswerten:
- Vorhersage mit predict() Methode mit Pipeline.
- Ausgabe der Ergebnisse und der Konfusionsmatrix von NLP-Modell.
