---
title: Wasserfall_Modell
tags: klassisch
author: ga88maby
anrechnung: k
---
Das [Wasserfallmodell](Wasserfallmodell.md) ist ein [lineares_Modell](lineares_Modell.md), das das Projekt Schritt für Schritt nach einem klar definierten Prozess abarbeitet. Der Prozess gliedert sich in aufeinanderfolgende Phasen, deren Ergebnis zu einem definitiven Endergebnis führen soll.[^1] Dieses Modell wird hauptsächlich für die Softwareentwicklung verwendet. Das Modell wurde von Royce im Jahr 1970 entwickelt und enthlält fünf bis zu Sieben Phasen.[^2]

![Beispielabbildung](Wasserfall_Modell/Wasserfall_Modell.PNG)

Abbildung Wasserfall. [^3]

# Grundkonzepte und Phasen: 

Jede dieser Phasen endet mit einem Meilenstein, für den eine definierte Ergebnismenge bereitgestellt werden muss. Jede Phase ist mit verschiedenen Aktivitäten gebündelt, die vollständig in der richtigen Reihenfolge ausgeführt werden müssen. Am Ende jeder Aktivität steht ein fertiges Ergebnis.[^4] Tritt in einer abgeschlossenen Stufe ein Fehler auf, kann zur letzten Stufe zurückgekehrt werden, dieser Vorgang wird als [Feedback-Looping](Feedback-Looping.md) bezeichnet. [^5]

![Beispielabbildung](Wasserfall_Modell/Phasen.jpg)

* Die 5 Phasen des Wasserfallmodells [^6]


##  1. Anforderung:
In der ersten Phase werden Anforderungen an das neue Projekt festgelegt. Sie beinhaltet eine [Ist-Analyse](Ist-Analyse.md) und ein [Soll-Konzept](Soll-Konzept.md). Während Ist-Analysen den Problembereich skizzieren, wird im Soll-Konzept definiert, welche Funktionen und Eigenschaften das Software-Produkt bieten muss, um den Anforderungen gerecht zu werden. Zu den Ergebnissen der Anforderungsdefinition gehören beispielsweise ein Pflichtenheft, eine detaillierte Beschreibung, wie die Anforderungen an das Projekt zu erfüllen sind, sowie ein Plan für Akzeptanztest.[^7]

Abschließend sieht die erste Phase des Wasserfallmodells eine Analyse der Anforderungsdefinition vor, in der komplexe Probleme in kleine Teilaufgaben zerlegt und entsprechende Lösungsstrategien erarbeitet werden.[^8]

##  2. Design/ Entwurf:
In der Designphase wird ein konkretes Lösungskonzept basierend auf vordefinierten Anforderungen, Aufgaben und Strategien entwickelt. In dieser Phase entwickeln Entwickler die Softwarearchitektur und den detaillierten Plan für den Aufbau der Software. Das Ergebnis der Designphase ist ein Designdokument mit einem Softwareentwicklungsplan und Testplänen für die einzelnen Komponenten.[^9]

##  3. Implementierung:
Da wird die Softwarearchitektur, die in der Design-Phase erarbeitet wurde, in der Implementierungsphase realisiert.
 Zumeist kristallisieren sich in der Implementierungsphase jedoch Fehler oder nicht realisierbare Teilaufgaben heraus, die in der Entwurfsphase entstanden sind. Daher erfolgen im Regelfall häufig Rückkopplungen zwischen Entwurfs- und Implementierungsphase. Das Ergebnis der Implementierungsphase ist ein Software-Produkt, das in der Folgephase erstmals als Komplettprodukt getestet wird.[^10]
##  4. Überprüfung:
In der Überprüfungsphase werden Designtests und die Integration auf verschiedenen Betriebssystemen bereitgestellt.[^11]  Die nun gefundenen Fehler müssen umgehend behoben werden. Dies ist in der Regel sehr aufwendig, da die Fehler meist auf frühere Phasen zurückzuführen sind.

##  5. Wartung und Einführung: 
Nach Abschluss aller Tests wird das fertige Produkt in Betrieb genommen und schließlich an den Kunden ausgeliefert. In dieser letzten Phase kann das Produkt immer wieder optimiert und aktualisiert werden.[^12] 

# Eigenschaften der Wasserfall-Modell:

* Einfach und leicht verständlich
* Der Entwicklungsprozess ist sequentiell, d.h. Jede Stufe muss abgeschlossen sein, bevor die Nächste beginnt
* Am Ende jeder Phase gibt es ein vollständiges Dokument, d.h. das Wasserfallmodell ist ein "dokumentengesteuertes" Modell
* Die Tätigkeiten sollten vollständig in der vorgeschriebenen Reihenfolge durchgeführt werden.[^13]
 


# Vorteile der Wasserfall-Modell:

1. Der größte Vorteil des Wasserfallmodells ist eine hohe [Planungssicherheit](Planungssicherheit.md). Dank der geordneten Struktur lassen sich auch große Projekte exakt planen und zuverlässig ausführen. [^14]
2. Durch klar definierte Projektphasen, ist der Aufbau einfach
3.  Klar getrennte Stufen, jede Stufe hat ein bestimmtes Ziel. [^15]
4.  Die Abschätzung von Kosten und Dauer jeder Phase ist möglich
 


# Nachteile der Wasserfall-Modell:
Das Modell bringt auch paar kritische Punkte mit wie:
1.  Abfolgeproblem: Theoretisch läuft jede Stufe nacheinander ab, aber in der Praxis sind  Rückschritte häufig unvermeidlich. [^16]
2. Aufgrund veränderter Anforderungen, besteht wenig Spielraum für Anpassungen im Projektablauf
3. Es ist kaum möglich, die Entwicklungsphasen nacheinander reibungslos zu bearbeiten
4. Die Fehlern werden erst am Ende der Entwicklungsprozess erkennt
5. Kaum flexibel gegenüber Änderungen


# Andere Vorgehensmodelle:
  Wegen der einigen gravierenden Nachteilen, die die wirtschaftliche Lage beschädigen, wird viele alternative von der IT-Industrie vorgeschlagen, wie z.b.:
*	[Spiralmodell](Spiralmodell.md): ist ein Prozessmodell in der Softwareentwicklung, das 1986 von Barry W. Boehm beschrieben wurde. Es ist ein allgemeines Prozessmodell, also offen für bestehende Prozessmodelle.[^17]
*	[Rational_Unified_Process](Rational_Unified_Process.md):  ist ein kommerzielles Produkt von der Firma Rational Software.  Es enthält das Vorgehensmodell der Softwareentwicklung und zugehörige Softwareentwicklungsverfahren.[^18]
*	[V-Modell](V-Modell.md): ist ein Prozessmodell, das ursprünglich für die Softwareentwicklung entwickelt wurde. Ähnlich dem Wasserfallmodell organisiert es den Softwareentwicklungsprozess in Phasen. Neben diesen Entwicklungsphasen definiert das V-Modell auch Verfahren zur Qualitätssicherung (Testing), indem es jede Entwicklungsphase mit der Testphase vergleicht.[^19]



# Siehe auch:

* Der Unterschied zwischen klassisches Wasserfall_Modell und das agile Modell:
  https://www.wegewerk.com/de/blog/wasserfall-vs-agile-umsetzung/

# Quellen:

[^1]: https://www.teamazing.de/was-ist-das-wasserfallmodell/
[^2]: https://www.enzyklopaedie-der-wirtschaftsinformatik.de/lexikon/is-management/Systementwicklung/Vorgehensmodell/Wasserfallmodell/index.html
[^3]: https://res.cloudinary.com/travelio/image/fetch/c_fill,f_auto,g_center/https://images.ctfassets.net/t13sz4t8kyqs/2hshC9HOYVFJCLoiv5ig8E/4d7df484dbdd1848c9432816152e4aee/TH.Huay_Mae_Khamin_Wasserfall.jpg
[^4]: https://www.enzyklopaedie-der-wirtschaftsinformatik.de/lexikon/is-management/Systementwicklung/Vorgehensmodell/Wasserfallmodell/index.html
[^5]: https://www.youtube.com/watch?v=8MEacBXP6zg&t=41s 
[^6]: https://www.netzsieger.de/ratgeber/methoden-des-traditionellen-projektmanagements#pid=1
[^7]: https://www.ionos.de/digitalguide/websites/web-entwicklung/wasserfallmodell/
[^8]: https://www.factro.de/blog/wasserfallmodell/
[^9]: https://www.ionos.de/digitalguide/websites/web-entwicklung/wasserfallmodell/
[^10]: https://www.ionos.de/digitalguide/websites/web-entwicklung/wasserfallmodell/
[^11]: https://www.factro.de/blog/wasserfallmodell/
[^12]: https://www.factro.de/blog/wasserfallmodell/ 
[^13]: https://www.quality.de/lexikon/wasserfallmodell/
[^14]: https://www.pinuts.de/projektmanagement-wasserfall-modell-gegen-agiles-arbeiten
[^15]: https://www.factro.de/blog/wasserfallmodell/
[^16]: https://www.quality.de/lexikon/wasserfallmodell/
[^17]: https://de.wikipedia.org/wiki/Spiralmodell
[^18]: https://de.wikipedia.org/wiki/Rational_Unified_Process
[^19]: https://de.wikipedia.org/wiki/V-Modell
