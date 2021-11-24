---
title: Vom_Mythos_des_Mann_Monats
tags: agil klassisch
author: nrivo
anrechnung: k
---


„Vom Mythos des Mann-Monats“ ist ein Essay des amerikanischen Informatikers Fred Brooks aus dem gleichnamigen Buch „The Mythical Man-Month: Essays on Software Engineering“ (deutsch: Vom Mythos des Mann-Monats: Essays über Software-Engineering). In seinen Essays befasst er sich mit seinen Eindrücken und Erfahrungen in Bezug auf Software-Engineering und [Projektmanagement](Projektmanagement.md), die er als ehemaliger Leiter des Projekts [OS/360](https://de.wikipedia.org/wiki/OS/360) bei [IBM](https://de.wikipedia.org/wiki/IBM) gesammelt hat, und den daraus geschlossenen Erkenntnissen. Aus diesen leitete Brooks das [Brook'sche Gesetz](https://de.wikipedia.org/wiki/Anti-Pattern#Brooks.E2.80.99sches_Gesetz) ab, wonach der Einsatz zusätzlicher Arbeitskräfte bei bereits verzögerten Software-Projekten diese nur noch mehr verzögert[^1].



# Der Mythos Mann-Monat
Zeitnot stellt die häufigste Ursache für das Scheitern von Software-Projekten dar und entsteht laut Brooks aus folgenden Gründen:[^1]
* Optimismus
* Der Mann-Monat
* System-Prüfung
* Schätzen ohne Risikobereitschaft
* Rückkopplung

## Optimismus
Brooks sieht in dem bei allen Programmierern aufgrund ihrer eigenen Arbeitsweise verankerten Gedankengang, alles werde schon gutgehen, einen der Gründe für das Entstehen von Zeitnot. Aus der Annahme eines reinen Gedankengebäudes mit Konzepten und deren formbarer Repräsentation schlussfolgern Programmierer eine problemlose Umsetzung ihrer Gedanken. Sie verkennen, dass auch ihre Ideen durchaus mangelhaft sein können, wodurch auch ihre Implementierung fehlerbehaftet ist. Durch diesen Irrtum gehen Programmierer daher übereilt davon aus, dass schon alles klappen wird.[^1] Dieser Optimismus führt regelmäßig dazu, dass der für die Umsetzung benötigte Zeitaufwand unterschätzt wird.[^2]

## Der Mann-Monat
Weitere Ursache für den Zeitverzug ist der Mann-Monat als Schätzeinheit. Der Mann-Monat ist eine Einheit, die als Maßstab von Schätzungen und Zeitvorgaben zugrunde gelegt wird. Der Mann-Monat stellt eine Maßeinheit für die Menge an Arbeit, die eine Person durchschnittlich in einem Monat schafft, dar und ist somit das Produkt von Zeit und Personal.[^3] 

Diese zugrunde gelegte Einheit führt jedoch zu einem Trugschluss, da irrtümlich angenommen wird, dass die Faktoren Mann und Monat, also Arbeitskraft und Arbeitszeit, austauschbar sind. Das Verhältnis zwischen Aufwand und Zeit ist jedoch nicht linear, sodass ein höherer Aufwand nicht zu einer verkürzten Zeit führt, was eine Austauschbarkeit ausschließt. 
Ausnahmsweise liegt eine tatsächliche Austauschbarkeit bei denjenigen Aufgaben vor, die so gestellt und aufgeteilt sind, dass viele Arbeitskräfte sie bewältigen können, ohne dass hierfür ein Informationsaustausch notwendig ist. 
Bild 2.1.

In der Regel wird jedoch bei der Annahme der Austauschbarkeit von Mann und Monat nach Brooks das Ausmaß der Anstrengung mit Fortschritt verwechselt. Denn wenn eine Aufgabe in einer bestimmten Reihenfolge erfolgt und aus diesem Grund nicht aufteilbar ist, dann ist jede hinzugefügte Anstrengung ohne Auswirkung und hat somit keinen Einfluss auf die Zeit (siehe Bild 2.2.). [hier Bild 2.2]

Bei aufteilbaren Aufgaben hingegen ist jedoch ein Informationsaustausch notwendig, der als gewisser Aufwand der zu leistenden Arbeit angerechnet werden muss (Bild 2.3), sodass es sich verlängernd auf die Projektzeit auswirkt.

Wenn n Personen Informationen untereinander austauschen müssen, sinkt ihr Output mit wachsendem n. Sobald dieser negativ wird, verzögert sich das Projekt mit jeder zusätzlich eingesetzten Person (Bild).

Anzahl der Kommunikationsbeziehungen: n(n − 1) / 2

Mit mehr Kommunikationsbeziehungen erhöht sich auch der Aufwand für eine Aufgabe zusätzlich zu dem ohnehin hinzuzurechnenden Aufwand des Informationsaustausches als zu leistende Arbeit.


## Systemprüfung

Die Dauer der Systemprüfung wird regelmäßig unterschätzt, da sie bei der Zeitplanung wenig Berücksichtigung findet beziehungsweise zu wenig Zeit für diese ….

## Schätzen ohne Risikobereitschaft

Ein Projekt erfordert eine gewisse Dauer, worauf auch der ausgeübte Zeitdruck von Kunden keinen Einfluss hat. Durch eine Anpassung an Kundenwünsche erfolgt jedoch eine falsche Arbeitsplanung, die wiederum zu Zeitverzug führt.
## Rückkopplung 
Gerät ein Projekt in Zeitverzug, so wird zur Problemlösung angewandt

 stellt man mehr Arbeitskräfte ein. Das verzögert aber das Projekt noch mehr durch Hinzukommen der Einarbeitungsdauer und der erhöhten Kommunikation für den Informationsaustausch.

Durch Optimismus hat man die Zeit eh zu knapp bemessen 

## Mythos als Schlussfolgerung
Es ist laut Brooks daher ein Mythos, dass durch eine Erhöhung der Arbeitskraft die Dauer des Projekts verkürzt werden kann, erst recht nicht kürzer sein kann als die Dauer, die ein Projekt an sich erfordert.


# Aspekt 1


![Beispielabbildung](Vom_Mythos_des_Mann_Monats/test-file.jpg)

*lustiges Testbild*

# Aspekt 2

* das
* hier 
* ist
* eine 
* Punkteliste
  - mit unterpunkt

## Hier eine Ebene-2-Überschrift unter Aspekt 2

So kann man eine Tabelle erstellen:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

## Hier gleich noch eine Ebene-2-Überschrift :-)

Wenn man hier noch ein bisschen untergliedern will kann man noch eine Ebene einfügen.

# Aspekt n

1. das
2. hier 
4. ist 
4. eine
7. nummerierte liste
   1. und hier eine Ebene tiefer

# Siehe auch

* Verlinkungen zu angrenzenden Themen
* [Zeitplanung](Zeitplanung.md)
* [Link auf diese Seite](Vom_Mythos_des_Mann_Monats.md)

# Weiterführende Literatur

* Weiterfuehrende Literatur zum Thema z.B. Bücher, Webseiten, Blogs, Videos, Wissenschaftliche Literatur, ...

# Quellen

[^1]: Brooks, Frederick P.: [Vom Mythos des Mann-Monats. Essays über Software-Engineering.](https://books.google.de/books?hl=de&lr=&id=-dSU0IxvfzMC&oi=fnd&pg=PA3&dq=mythos+von+mann+monats&ots=ekrC7IHjO5&sig=I7Jhh12LZFxYNlzPyxFBclx86Y8&redir_esc=y#v=onepage&q&f=false) mitp Verlags GmbH & Co. KG, 2003, S. 13-27.

[^2]: Demant, Christian. [Software Due Diligence: Softwareentwicklung als Asset bewertet.](https://link.springer.com/book/10.1007/978-3-662-53062-7)Springer-Verlag, 2017, S. 97f.

[^3]: [Mannjahr](https://wirtschaftslexikon.gabler.de/definition/mannjahr-39390/version-262799), 19.02.2018, abgerufen am 23.11.2021.

[^4]: [Basic Formatting Syntax for GitHub flavored Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[^5]: [Advanced Formatting Syntax for GitHub flavored Markdown](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)



