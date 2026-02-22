# Projektbeschreibung – Analyse von Bankkundendaten (PigEBank)

## Ziel des Projekts
Ziel des Projekts ist die Analyse eines Bankkundendatensatzes, um Muster im Kundenverhalten zu identifizieren und potenzielle Risikofaktoren für Kundenabwanderung (Churn) zu erkennen.
Das Projekt umfasst die Datenbereinigung, explorative Analyse sowie die Entwicklung eines einfachen Entscheidungsbaummodells, das die wichtigsten Einflussgrößen auf die Abwanderung visualisiert.

## Ausgangssituation & Erwartungen des Auftraggebers
Die Compliance Abteilung der Bank benötigt eine erste analytische Einschätzung zu folgenden Punkten:
•	Welche Kundengruppen weisen ein erhöhtes Abwanderungsrisiko auf?
•	Welche Variablen (z. B. Alter, Kontostand, Aktivitätsstatus) beeinflussen die Abwanderung am stärksten?
•	Wie kann ein einfaches, transparentes Modell (Decision Tree) zur internen Kommunikation genutzt werden?
•	Welche Datenqualitätsprobleme bestehen und wie wurden sie behoben?
Die Analyse wurde ausschließlich mit Excel durchgeführt (Aufgaben 5.1–5.4 des Achievements).

## Datenschutz & Datenethik
Da der Datensatz personenbezogene Informationen enthielt, wurden folgende Maßnahmen umgesetzt:
•	Entfernung der Spalte „Last_Name“ zur Wahrung der Vertraulichkeit
•	Prüfung auf fehlende Werte, Inkonsistenzen und unplausible Einträge
•	Keine Speicherung oder Weitergabe personenbezogener Daten außerhalb der Analyseumgebung
•	Dokumentation aller Bereinigungsschritte im Sinne der Datenethik

## Projektumfang & Aufgaben
### 1. Datenbereinigung 
•	Prüfung auf fehlende Werte, Dubletten und Ausreißer
•	Bereinigung der Variablen „Country“ (FR/ES/DE → harmonisiert)
•	Entfernung der Spalte „Last_Name“
•	Typprüfung numerischer Variablen (Alter, Kontostand, Gehalt etc.)
### 2. Explorative Datenanalyse
•	Analyse der Altersverteilung
•	Analyse der Produktnutzung (NumOfProducts)
•	Untersuchung des Zusammenhangs zwischen Aktivitätsstatus und Abwanderung
•	Identifikation potenzieller Risikogruppen
### 3. Feature Engineering
•	Erstellung zusätzlicher Kategorien (z. B. Altersgruppen, Balance Cluster)
•	Vorbereitung der Daten für den Entscheidungsbaum
•	Prüfung der Variablenrelevanz
### 4. Entscheidungsbaum
•	Entwicklung eines einfachen Decision Trees in Excel
•	Visualisierung der wichtigsten Einflussfaktoren auf „ExitedFromBank?“
•	Ableitung erster Hypothesen für das Compliance Team

## Ergebnisse (Kurzfassung)
•	Höheres Abwanderungsrisiko bei bestimmten Altersgruppen und bei Kunden mit mittlerem Kontostand
•	Aktivitätsstatus und Produktanzahl sind starke Prädiktoren
•	Der Entscheidungsbaum bietet eine klare, leicht verständliche Struktur für interne Stakeholder

## Verwendete Methoden & Tools
•	Excel (Pivot, Diagramme, Entscheidungsbaum Logik)
•	Deskriptive Statistik
•	Datenbereinigung & Harmonisierung
•	Entscheidungsbaum (manuell modelliert)


