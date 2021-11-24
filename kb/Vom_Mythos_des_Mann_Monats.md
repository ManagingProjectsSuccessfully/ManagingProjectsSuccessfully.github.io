---
title: Vom_Mythos_des_Mann_Monats
tags: agil klassisch
author: nrivo
anrechnung: k
---


*Vom Mythos des Mann-Monats* ist ein Essay des amerikanischen Informatikers Fred Brooks aus dem gleichnamigen Buch *The Mythical Man-Month: Essays on Software Engineering* (deutsch: Vom Mythos des Mann-Monats: Essays über Software-Engineering). Er befasst sich darin mit seinen Eindrücken und Erfahrungen in Bezug auf Software-Engineering und [Projektmanagement](Projektmanagement.md), die er als ehemaliger Leiter eines Projekts bei [IBM](https://de.wikipedia.org/wiki/IBM) gesammelt hat, und den daraus geschlossenen Erkenntnissen. Aus diesen leitete Brooks das [Brook'sche Gesetz](https://de.wikipedia.org/wiki/Anti-Pattern#Brooks.E2.80.99sches_Gesetz) ab, wonach der Einsatz zusätzlicher Arbeitskräfte bei bereits verzögerten Software-Projekten diese nur noch mehr verzögert[^1].



# Der Mythos Mann-Monat
Software-Projekte scheitern laut Brooks am häufigsten an Zeitnot, die auf der Annahme eines Mythos basiert. Gründe hierfür sind:[^1]
* Optimismus
* Der Mann-Monat
* System-Prüfung
* Schätzen ohne Risikobereitschaft
* Rückkopplung

## Optimismus
Einer der Gründe für das Entstehen von Zeitnot ist laut Brooks die bei allen Programmierer:innen verankerte Denkweise, alles werde schon gutgehen. Aufgrund ihrer eigenen Arbeitsweise nehmen sie an, dass die Repräsentation ihrer gedanklichen Konzepte frei formbar und flexibel ist und daher die Umsetzung ihrer Vorstellungen problemlos erfolgt. Sie verkennen, dass auch ihre Ideen mangelhaft sein können, wodurch auch ihre Implementierung fehlerbehaftet ist. Durch diesen Optimismus hinsichtlich der Umsetzung wird der für die Umsetzung benötigte Zeitaufwand regelmäßig unterschätzt.[^1][^2]

## Der Mann-Monat
Der Mann-Monat stellt eine Maßeinheit für die Menge an Arbeit dar, die eine Person durchschnittlich in einem Monat schafft, und ist das Produkt von Zeit und Personal. Er wird als Maßstab von Schätzungen und Zeitvorgaben zugrunde gelegt.[^3] 

Diese zugrunde gelegte Einheit führt jedoch zu einem Trugschluss, da irrtümlich angenommen wird, dass die Faktoren Mann und Monat, also Arbeitskraft und Arbeitszeit, austauschbar sind. Das Verhältnis zwischen Arbeitskraft und Zeit ist aber nicht linear, sodass mehr Arbeitskraft nicht zu einer verkürzten Zeit führt, was eine Austauschbarkeit ausschließt.[^1]

Eine tatsächliche Austauschbarkeit liegt ausnahmsweise bei denjenigen Aufgaben vor, die so gestellt und aufgeteilt sind, dass viele Arbeitskräfte sie bewältigen können, ohne dass hierfür ein Informationsaustausch notwendig ist (Abbildung 1). Solche Software-Projekte kommen in der Praxis jedoch kaum vor.[^1]

![Abbildung](Vom_Mythos_des_Mann_Monats/Arbeitszeit%20vs.%20Arbeitskräfte%20vollständig%20unterteilbar.JPG)

*Abbildung 1: Arbeitszeit und Arbeitskräfte aufteilbar*[^1]


Wenn aber eine Aufgabe in einer bestimmten Reihenfolge erfolgt und deshalb nicht aufteilbar ist, dann hat jede hinzugefügte Anstrengung keinen Einfluss auf die Zeit (Abbildung 2). (QUEEEEEEELLEEEE)

![Abbildung](Vom_Mythos_des_Mann_Monats/Arbeitszeit%20vs.%20Arbeitskräfte%20unteilbar.JPG)

*Abbildung 2: Arbeitszeit und Arbeitskräfte unteilbar*[^1]

Bei aufteilbaren Aufgaben ist hingegen ein Informationsaustausch notwendig, der als Aufwand der zu leistenden Arbeit angerechnet werden muss (Abbildung 3), was sich verlängernd auf die Projektzeit auswirkt. Mit mehr Kommunikationsbeziehungen erhöht sich auch der Aufwand für eine Aufgabe zusätzlich zu dem ohnehin hinzuzurechnenden Aufwand des Informationsaustausches als zu leistende Arbeit.[^1]

![Abbildung](Vom_Mythos_des_Mann_Monats/Aufgabe%20mit%20Kommunikation.JPG)

*Abbildung 3: Projekt mit Informationsaustausch*[^4]

Beim Informationsaustausch von n Personen sinkt ihr Output mit wachsendem n. Sobald dieser negativ wird, verzögert sich das Projekt mit jeder zusätzlich eingesetzten Person (Abbildung 3).Dabei ist die Anzahl der Kommunikationsbeziehungen definiert durch: n(n − 1) / 2 [^1][^5]


## Systemprüfung

Die Dauer der Systemprüfung wird regelmäßig unterschätzt, da sie bei der Zeitplanung wenig Berücksichtigung findet beziehungsweise zu wenig Zeit für diese ….

## Schätzen ohne Risikobereitschaft

Ein Projekt erfordert eine gewisse Dauer, worauf auch der ausgeübte Zeitdruck von Kunden keinen Einfluss hat. Durch eine Anpassung an Kundenwünsche erfolgt jedoch eine falsche Arbeitsplanung, die wiederum zu Zeitverzug führt.

## Rückkopplung 
Gerät ein Projekt in Zeitverzug, so wird zur Problemlösung angewandt

 stellt man mehr Arbeitskräfte ein. Das verzögert aber das Projekt noch mehr durch Hinzukommen der Einarbeitungsdauer und der erhöhten Kommunikation für den Informationsaustausch.

Durch Optimismus hat man die Zeit eh zu knapp bemessen 

## Mythos als Schlussfolgerung
Es ist laut Brooks daher ein Mythos, dass durch eine Erhöhung der Arbeitskraft die Dauer des Projekts verkürzt werden kann, erst recht nicht kürzer sein kann als die Dauer, die ein Projekt an sich erfordert.[^1]


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

[^4]: [Projektmanagement aus der Praxis der Softwareentwicklung](https://www-seal.cs.tu-dortmund.de/seal/downloads/teaching/pm1415/2b.%20Aufwandssch%C3%A4tzung%20V1.pdf), 27.10.2014, abgerufen am 23.11.2021

[^5]: [Vom Mythos des Mann-Monats](https://de.wikipedia.org/wiki/Vom_Mythos_des_Mann-Monats), abgerufen am 23.11.2021




