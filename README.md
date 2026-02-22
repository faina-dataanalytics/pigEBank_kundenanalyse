# Projektbeschreibung – Analyse von Bankkundendaten (PigEBank)

## Ziel des Projekts
Ziel des Projekts ist die Analyse eines Bankkundendatensatzes, um Muster im Kundenverhalten zu identifizieren und potenzielle Risikofaktoren für Kundenabwanderung (Churn) zu erkennen.
Das Projekt umfasst die Datenbereinigung, explorative Analyse sowie die Entwicklung eines einfachen Entscheidungsbaummodells, das die wichtigsten Einflussgrößen auf die Abwanderung visualisiert.

## Ausgangssituation & Erwartungen des Auftraggebers
Die Compliance Abteilung der Bank benötigt eine erste analytische Einschätzung zu folgenden Punkten:<br><br>
•	Welche Kundengruppen weisen ein erhöhtes Abwanderungsrisiko auf?<br><br>
•	Welche Variablen (z. B. Alter, Kontostand, Aktivitätsstatus) beeinflussen die Abwanderung am stärksten?<br><br>
•	Wie kann ein einfaches, transparentes Modell (Decision Tree) zur internen Kommunikation genutzt werden?<br><br>
•	Welche Datenqualitätsprobleme bestehen und wie wurden sie behoben?<br><br>
Die Analyse wurde ausschließlich mit Excel durchgeführt (Aufgaben 5.1–5.4 des Achievements).

## Datenschutz & Datenethik
Da der Datensatz personenbezogene Informationen enthielt, wurden folgende Maßnahmen umgesetzt:<br><br>
•	Entfernung der Spalte „Last_Name“ zur Wahrung der Vertraulichkeit<br><br>
•	Prüfung auf fehlende Werte, Inkonsistenzen und unplausible Einträge<br><br>
•	Keine Speicherung oder Weitergabe personenbezogener Daten außerhalb der Analyseumgebung<br><br>
•	Dokumentation aller Bereinigungsschritte im Sinne der Datenethik

## Projektumfang & Aufgaben
### 1. Datenbereinigung <br><br>
•	Prüfung auf fehlende Werte, Dubletten und Ausreißer<br><br>
•	Bereinigung der Variablen „Country“ (FR/ES/DE → harmonisiert)<br><br>
•	Entfernung der Spalte „Last_Name“<br><br>
•	Typprüfung numerischer Variablen (Alter, Kontostand, Gehalt etc.)<br><br>
### 2. Explorative Datenanalyse<br><br>
•	Analyse der Altersverteilung<br><br>
•	Analyse der Produktnutzung (NumOfProducts)<br><br>
•	Untersuchung des Zusammenhangs zwischen Aktivitätsstatus und Abwanderung<br><br>
•	Identifikation potenzieller Risikogruppen<br><br>
### 3. Feature Engineering<br><br>
•	Erstellung zusätzlicher Kategorien (z. B. Altersgruppen, Balance Cluster)<br><br>
•	Vorbereitung der Daten für den Entscheidungsbaum<br><br>
•	Prüfung der Variablenrelevanz<br><br>
### 4. Entscheidungsbaum<br><br>
•	Entwicklung eines einfachen Decision Trees in Excel<br><br>
•	Visualisierung der wichtigsten Einflussfaktoren auf „ExitedFromBank?“<br><br>
•	Ableitung erster Hypothesen für das Compliance Team<br><br>

## Ergebnisse (Kurzfassung)
•	Höheres Abwanderungsrisiko bei bestimmten Altersgruppen und bei Kunden mit mittlerem Kontostand<br><br>
•	Aktivitätsstatus und Produktanzahl sind starke Prädiktoren<br><br>
•	Der Entscheidungsbaum bietet eine klare, leicht verständliche Struktur für interne Stakeholder<br><br>

## Verwendete Methoden & Tools
•	Excel (Pivot, Diagramme, Entscheidungsbaum Logik)<br><br>
•	Deskriptive Statistik<br><br>
•	Datenbereinigung & Harmonisierung<br><br>
•	Entscheidungsbaum (manuell modelliert)<br><br>


