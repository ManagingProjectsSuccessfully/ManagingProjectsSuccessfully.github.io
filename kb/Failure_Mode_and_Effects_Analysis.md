---
title: Failure_Mode_and_Effects_Analysis.md 
tags: klassisch
author: Creed229
anrechnung: k 
---

## Definition

> Failure mode and effects analysis [(FMEA)](https://de.wikipedia.org/wiki/FMEA) is a structured approach for discovering possible failures that may occur in the design of a product or process.[^1] 

Es handelt sich also um eine Schritt für Schritt Analyse bei der alle Bereiche eines Projekts auf mögliche Fehlerstellen überprüft werden. Besonders zu Beginn eines Projekts ist eine solches Risikoeinschätzung enorm wichtig, um später kostenintensive Fehlerbehebungen vermeiden zu können. Die Analyse produziert mehrere Kennzahlen mit denen das Fehlerpotential des Prozesses oder Produkts eingeschätzt wird.[^1][^2]

## Anwendungsbereiche 


[FMEA](https://de.wikipedia.org/wiki/FMEA) Ansätze lassen sich nach den Bereichen differenzieren in dem sie eingesetzt werden. Dies sind weit verbreitetsten Arten:
#### **Prozess-FMEA**
Die Prozess-FMEA befasst sich mit den Schwachstellen in einem Prozess, um dessen Effizienz und  Qualität zu steigern. Wird häufig bei der Einführung angewandt, um den potentiellen Erfolg der Neuerung abzubilden.[^3] 
#### **Design-FMEA**
Design-FMEA wird insbesondere in der Entwicklung eingesetzt, um die Komponenten eines Produkts auf die Fertigungseignung zu überprüfen.
#### **System-FMEA**
Wenn mehrere Teilsysteme zu einem komplexen System führen, nutzt man die System-FMEA, um die globale Funktion des Systems zu testen. Dafür werden auch die Komponenten der Teilsysteme und deren Zusammenwirken analysiert.
#### **Software-FMEA & Hardware-FMEA**
Fehleranalyse im Bereich Hardware oder Software. Auch hier werden die einzelnen Komponenten auf ihre Funktionalität geprüft.
#### **Präventive und korrektive FMEA**
*Präventive FMEA* dient der frühestmöglichen Erkennung und Vermeidung von Fehlern. Dafür wird das Produkt oder der Prozess von Beginn der Entwicklungsphase an begleitet und fortlaufend evaluiert. So wird sichergestellt, dass Hindernisse und Probleme frühzeitig erkannt und beseitigt werden können. Denn je später im Entwicklungsprozess Fehler auftreten, desto kostenintensiver ist die Behebung.[^4]

*Korrektive FMEA* ist eine Art rückwärts gerichtete Betrachtung des Produkts/Prozesses. Hierbei wird die Analyse erst in einer späteren Lebensphase hinzugezogen, um eine konstant höhere Qualität zu gewährleisten. Bereits entdeckte Fehler werden analysiert, um ähnliche Komplikationen vorzubeugen. Dies erfordert deutlich höheren Aufwand als die *präventive FMEA* und ist daher nur in Ausnahmefällen ratsam.[^4]

## Wichtige Kennzahlen 
Der Aufbau und das Ergebnis einer "Failure Mode and Effects Analysis" beinhaltet mehrere Kennzahlen[^5]: 

* **Failure Mode** gibt an, auf welche Art und Weise der Fehler eintritt. Dafür wird jeder Bestandteil des untersuchten Objekts einzeln betrachtet.
* **Effect** gibt an, welche potentiellen Effekte der Fehler haben kann. Dabei kann noch zwischem den Effekt auf das Objekt selber und dem Effekt auf das gesamte System unterschieden werden.
* **Probability (P)** gibt an, mit welcher Wahrscheinlichkeit der Fehler eintritt. 
* **Severity (S)** gibt an, wie schwerwiegend die Folgen sind. Dabei wird immer von einem "worst-case scenario" ausgegangen.
* **Detection (D)** gibt an, mit welcher Sicherheit der Fehler von der Analyse erfasst und entdeckt wird.
* **Risk Priority Number (RPN)** ist das Produkt aus **S**, **P** und **D** und bringt die einzelnen Failure Modes in eine geordnete Reihenfolge. 
* **Proposed Actions** gibt an, was getan werden muss um die erkannten Risiken der Failure Modes zu minimieren.


![FMEA Basic Sheet](http://pdcahome.com/english/wp-content/uploads/2013/06/fmea.jpeg)
[Simples FMEA Spreadsheet](http://pdcahome.com/english/wp-content/uploads/2013/06/fmea.jpeg)[^6]

## Aufbau und Ablauf
FMEA wird meist in mehreren "Brainstorming" Sitzungen eines Teams durchgeführt. Dabei werden die genannten Kennzahlen gemeinsam festgelegt. Die Bewertung der Kriterien erfolgt dabei von 1 bis 10. Dadurch wird sich bereits ein erster Überblick verschafft und die Fehlerdaten von mehreren Parteien gesammelt. 

Anschließend wird durch die Berechnung und Bewertung der **RPN** eine Fazit gebildet, bei welchen Prozessen es das größte Verbesserungspotential gibt. Es werden Vorschläge gesammelt und es wird evaluiert was genau angepasst werden muss. Durch die Wiederholung dieses Prozesses soll über lange Sicht eine Eliminierung aller Fehler im System erzielt werden.[^6][^7]



# Siehe auch

* [FMEA_Methode](kb/FMEA_Methode.md)
* [Link auf diese Seite](Failure_Mode_and_Effects_Analysis.md)

# Weiterführende Literatur

* [FMEA Wikipedia](https://de.wikipedia.org/wiki/FMEA)
* [FMEA Google Scholar](https://scholar.google.de/scholar?hl=de&as_sdt=0%2C5&q=failure+modes+effects+analysis&oq=failure+modes)
# Quellen

[^1]: Haktanir et al. (2020), "Interval-valued neutrosophic failure mode and effect analysis."

[^2]: Project Management Institute (2013), "Project Management Body of Knowledge", 5th edition

[^3]: [Prozess-FMEA ](https://mi-nautics.com/prozess-fmea-anwendung-und-durchfuehrung/)

[^4]: [Fehlermöglichkeits- und -Einflussanalyse (FMEA)](https://www.iph-hannover.de/de/dienstleistungen/fertigungsverfahren/fmea/#arten)

[^5]: Langford, J. W. (1995), "Logistics: Principles and Applications." McGraw Hill. p. 488

[^6]: [FMEA Spreadsheet](http://pdcahome.com/english/wp-content/uploads/2013/06/fmea.jpeg)

[^7]: [Project Management 101 — What is Failure Mode and Effects Analysis (FMEA)?](https://www.copperproject.com/2018/01/project-management-101-failure-mode-effects-analysis-fmea/)
[^8]: D. H Stamatis (2003), 2. Edition, "Failure Mode and Effect Analysis – FMEA from theory to execution", ASQ Quality Press
