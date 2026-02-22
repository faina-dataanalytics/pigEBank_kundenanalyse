# Projektbeschreibung – Analyse von Bankkundendaten (PigEBank)

## Ziel des Projekts
Ziel des Projekts ist die Analyse eines Bankkundendatensatzes, um Muster im Kundenverhalten zu identifizieren und potenzielle Risikofaktoren für Kundenabwanderung (Churn) zu erkennen.<br>
Das Projekt umfasst die Datenbereinigung, explorative Analyse sowie die Entwicklung eines einfachen Entscheidungsbaummodells, das die wichtigsten Einflussgrößen auf die Abwanderung visualisiert.

## Ausgangssituation & Erwartungen des Auftraggebers
Die Compliance Abteilung der Bank benötigt eine erste analytische Einschätzung zu folgenden Punkten:<br>
•	Welche Kundengruppen weisen ein erhöhtes Abwanderungsrisiko auf?<br>
•	Welche Variablen (z. B. Alter, Kontostand, Aktivitätsstatus) beeinflussen die Abwanderung am stärksten?<br>
•	Wie kann ein einfaches, transparentes Modell (Decision Tree) zur internen Kommunikation genutzt werden?<br>
•	Welche Datenqualitätsprobleme bestehen und wie wurden sie behoben?<br>
Die Analyse wurde ausschließlich mit Excel durchgeführt (Aufgaben 5.1–5.4 des Achievements).

## Datenschutz & Datenethik
Da der Datensatz personenbezogene Informationen enthielt, wurden folgende Maßnahmen umgesetzt:<br>
•	Entfernung der Spalte „Last_Name“ zur Wahrung der Vertraulichkeit<br>
•	Prüfung auf fehlende Werte, Inkonsistenzen und unplausible Einträge<br>
•	Keine Speicherung oder Weitergabe personenbezogener Daten außerhalb der Analyseumgebung<br>
•	Dokumentation aller Bereinigungsschritte im Sinne der Datenethik

## Projektumfang & Aufgaben
### 1. Datenbereinigung
•	Prüfung auf fehlende Werte, Dubletten und Ausreißer<br>
•	Bereinigung der Variablen „Country“ (FR/ES/DE → harmonisiert)<br>
•	Entfernung der Spalte „Last_Name“<br>
•	Typprüfung numerischer Variablen (Alter, Kontostand, Gehalt etc.)<br>
### 2. Explorative Datenanalyse
•	Analyse der Altersverteilung<br>
•	Analyse der Produktnutzung (NumOfProducts)<br>
•	Untersuchung des Zusammenhangs zwischen Aktivitätsstatus und Abwanderung<br>
•	Identifikation potenzieller Risikogruppen<br>
### 3. Feature Engineering
•	Erstellung zusätzlicher Kategorien (z. B. Altersgruppen, Balance Cluster)<br>
•	Vorbereitung der Daten für den Entscheidungsbaum<br>
•	Prüfung der Variablenrelevanz<br>
### 4. Entscheidungsbaum
•	Entwicklung eines einfachen Decision Trees in Excel<br>
•	Visualisierung der wichtigsten Einflussfaktoren auf „ExitedFromBank?“<br>
•	Ableitung erster Hypothesen für das Compliance Team<br>

## Ergebnisse (Kurzfassung)
•	Höheres Abwanderungsrisiko bei bestimmten Altersgruppen und bei Kunden mit mittlerem Kontostand<br>
•	Aktivitätsstatus und Produktanzahl sind starke Prädiktoren<br>
•	Der Entscheidungsbaum bietet eine klare, leicht verständliche Struktur für interne Stakeholder<br>

## Verwendete Methoden & Tools
•	Excel (Pivot, Diagramme, Entscheidungsbaum Logik)<br>
•	Deskriptive Statistik<br>
•	Datenbereinigung & Harmonisierung<br>
•	Entscheidungsbaum (manuell modelliert)<br>


