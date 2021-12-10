---
title: Failure_Mode_and_Effects_Analysis
tags: klassisch
author: Creed229
anrechnung: k 
---

[Failure Mode and Effects Analysis](Failure_Mode_and_Effects_Analysis.md) ist eine Schritt für Schritt Analyse, bei der alle Bereiche eines Projekts auf mögliche Fehlerstellen überprüft werden. Besonders zu Beginn eines Projekts ist eine solche Risikoeinschätzung enorm wichtig, um später kostenintensive Fehlerbehebungen vermeiden zu können. Die Analyse ergiebt mehrere Kennzahlen mit denen das Fehlerpotential des Prozesses oder des Produkts eingeschätzt wird.[^1][^2]

> Failure mode and effects analysis [(FMEA)](FMEA_Methode.md) is a structured approach for discovering possible failures that may occur in the design of a product or process.[^1] 

## Anwendungsbereiche 


[FMEA](https://de.wikipedia.org/wiki/FMEA) Ansätze lassen sich nach den Bereichen differenzieren in denen sie eingesetzt werden. Dies sind weit verbreitetsten Arten:
#### **Prozess-FMEA**
Die *Prozess-FMEA* befasst sich mit den Schwachstellen in einem Prozess, um die Effizienz und  Qualität zu steigern. Wird häufig bei der Einführung angewandt, um den potentiellen Erfolg einer Neuerung abzubilden.[^3] 
#### **Design-FMEA**
*Design-FMEA* wird insbesondere in der Entwicklung eingesetzt, um die Komponenten eines Produkts auf die Fertigungseignung zu überprüfen.
#### **System-FMEA**
Wenn mehrere Teilsysteme zu einem komplexen System führen, nutzt man die *System-FMEA*, um die globale Funktion des Systems zu testen. Dafür werden die Komponenten der Teilsysteme und deren Zusammenwirken analysiert.
#### **Software-FMEA & Hardware-FMEA**
Fehleranalyse im Bereich Hardware oder Software. Auch hier werden die einzelnen Komponenten auf ihre Funktionalität geprüft.
#### **Präventive und korrektive FMEA**
*Präventive FMEA* dient der frühestmöglichen Erkennung und Vermeidung von Fehlern. Dafür wird das Produkt oder der Prozess von Beginn der Entwicklungsphase an begleitet und fortlaufend evaluiert. So wird sichergestellt, dass Hindernisse und Probleme frühzeitig erkannt und beseitigt werden können. Denn je später im Entwicklungsprozess Fehler auftreten, desto kostenintensiver ist die Behebung.[^4]

*Korrektive FMEA* ist eine Art rückwärts gerichtete Betrachtung des Produkts/Prozesses. Hierbei wird die Analyse erst in einer späteren Lebensphase hinzugezogen, um eine konstant höhere Qualität zu gewährleisten. Die dabei entdeckten Fehler werden analysiert, um ähnliche Komplikationen vorzubeugen. Dies erfordert deutlich höheren Aufwand als die *präventive FMEA* und ist daher nur in Ausnahmefällen ratsam.[^4]

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

Anschließend wird durch die Berechnung und Bewertung der **RPN** ein Fazit gebildet, bei welchen Prozessen es das größte Verbesserungspotential gibt. Es werden Vorschläge gesammelt und es wird evaluiert was genau angepasst werden muss. Durch die Wiederholung dieses Prozesses soll über lange Sicht eine Eliminierung aller Fehler im System erzielt werden.[^6][^7]



# Siehe auch

* [FMEA_Methode](FMEA_Methode.md)
* [RPN Berechnung](https://youtu.be/cxHVnwIsaOU)
* [Reverse FMEA](https://www.fmea-kontor.de/leistungen/reverse-fmea.html#:~:text=Die%20Reverse%20FMEA%20wird%20als,gefordert%20(GM%20IATF%20CSR).)
* [Service FMEA](https://www.inf.uni-hamburg.de/de/inst/ab/itmc/research/completed/promidis/instrumente/service-fmea)

# Weiterführende Literatur

* [FMEA Wikipedia](https://de.wikipedia.org/wiki/FMEA)
* [FMEA Google Scholar](https://scholar.google.de/scholar?hl=de&as_sdt=0%2C5&q=failure+modes+effects+analysis&oq=failure+modes)
# Quellen

[^1]: [Haktanir et al. (2020), "Interval-valued neutrosophic failure mode and effect analysis."](http://openaccess.altinbas.edu.tr/xmlui/bitstream/handle/20.500.12939/257/elif.pdf?sequence=1&isAllowed=y)

[^2]: [Project Management Institute (2013), "A Guide to the Project Management Body of Knowledge", 5th edition](https://repository.dinus.ac.id/docs/ajar/PMBOKGuide_5th_Ed.pdf)

[^3]: [Prozess-FMEA ](https://mi-nautics.com/prozess-fmea-anwendung-und-durchfuehrung/)

[^4]: [Fehlermöglichkeits- und -Einflussanalyse (FMEA)](https://www.iph-hannover.de/de/dienstleistungen/fertigungsverfahren/fmea/#arten)

[^5]: Langford, J. W. (1995), "Logistics: Principles and Applications." McGraw Hill. p. 488

[^6]: [FMEA Spreadsheet](http://pdcahome.com/english/wp-content/uploads/2013/06/fmea.jpeg)

[^7]: [Project Management 101 — What is Failure Mode and Effects Analysis (FMEA)?](https://www.copperproject.com/2018/01/project-management-101-failure-mode-effects-analysis-fmea/)
[^8]: D. H Stamatis (2003), 2. Edition, "Failure Mode and Effect Analysis – FMEA from theory to execution", ASQ Quality Press
