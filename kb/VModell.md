---
title: VModell
tags: klassisch vmodell wasserfallmodell
author: fabriGH
anrechnung: k
---

---

# Was ist das V-Modell?

Das V-Modell ist ein V-förmiges lineares [Vorgehensmodell](https://de.wikipedia.org/wiki/Vorgehensmodell_zur_Softwareentwicklung) im Projektmanagement, das ein Projekt in fest definierte Phasen unterteilt, welches ursprünglich für die Softwareentwicklung konzipiert wurde. Es ähnelt dem ebenfalls [linearen Wasserfallmodell](https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Wasserfall_Modell.md), mit dem Unterschied, dass es zusätzlich Testphasen gibt, welche den jeweiligen Entwicklungsphasen gegenübergestellt sind. Dies soll beim Entwickeln eines Projekts helfen, die einzelnen Phasen sauber zu testen, zu integrieren und letztendlich als Ganzes zusammenzufügen. Erstmals vorgeschlagen wurde es durch den US-amerikanischen Softwareingenieur [Barry W. Boehm](https://de.wikipedia.org/wiki/Barry_W._Boehm) im Jahre 1979.[^1][^2] 

## Abbildung V-Modell

![v-modell](https://user-images.githubusercontent.com/92790072/142849508-172e4421-7a7d-435e-bc29-652fe4992df0.jpg)


1. Auf der linken Seite des V wird mit dem funktionalen/fachlichen Ausbau begonnen, welcher immer tiefer bis zur Komponentenspezifikation und [Implementierung](https://de.wikipedia.org/wiki/Implementierung) detailliert wird. Auf der untersten Ebene wird klar beschrieben, wie die Anforderungen technisch umgesetzt werden sollen.

2. Die untere Spitze des V ist die Implementierung, hier entsteht das eigentliche Produkt des Projekts.

3. Die rechte Seite des V ist die "Testseite" des V-Modells. Sie beschreibt, wie die einzelnen entwickelten Bausteine und Funktionen getestet und zu einem Gesamtsystem zusammengefasst werden.[^3]

# Die einzelnen Phasen des V-Modells
Zu 1: Die linke Seite des V wird auch "Entwurfsphase" genannt. Sie übersetzt Anforderungen in einen Systementwurf, der nach dem Top-Down-Prinzip immer weiter verfeinert wird. Wenn sich in einer darüberliegenden Ebene etwas verändert, müssen die darunterliegenden Ebenen angepasst werden, da diese aufeinander aufbauen.
  
     1.1 Anforderungsanalyse: Diese Ebene beschäftigt sich mit der Bestimmung der Anforderungen. Was soll das fertige Produkt können?
  
     1.2 Systementwurf: Hier wird ein Design für das Gesamtsystem erstellt, inklusive Organisation und grafischer Ausgestaltung. Wie können die Anforderungen umgesetzt werden?
 
     1.3 Architektur: Auf dieser Ebene wird das Gesamtsystem in einzelne Komponenten aufgeteilt und deren Schnittstelle und Abhängigkeit beschrieben.
  
     1.4 Komponentenspezifikation: Auf dieser letzten Ebene der Entwurfsphase wird spezifiziert, wie die Funktionen und Komponenten implementiert werden sollen.

Zu 2: Die Implementierungsphase variiert je nach Projekt, daher gibt es dazu im V-Modell keine Vorschriften für die Umsetzung.

zu 3: In der Test- und Validierungsphase steht jede Ebene der dazugehörigen Ebene in der Entwurfsphase gegenüber (Bottom-Up-Prinzip).[^2][^4]
     
     3.1 Komponententest: Funktionen einzelner Komponenten werden getestet.
     
     3.2 Integrationstest: Auf dieser Ebene wird getestet ob verschiedene Komponenten gemeinsam funktionieren und ihre Daten korrekt kommunizieren.
     
     3.3 Systemtest: Hier kommt spätestens der Kunde ins Spiel, welcher das System als Ganzes intensiven Testläufen unterzieht.
     
     3.4 Abnahmetest: Dies ist der Finale Test des Projekts. Dieser sollte in einer Umgebung stattfinden, die der späteren Produktivumgebung möglichst ähnlich ist. Auch die Nutzer sollten den Endnutzern Entsprechen, um ein möglichst aussagekräftiges Testergebnis zu ermitteln.

# Vor und Nachteile des V-Modells
|Vorteile|Nachteile|
|---|---|
|Umsetzbarkeit und Probleme werden früh erkannt|sehr ausführliche Dokumentationen nötig|
|einfacher Aufbau|starr und wenig flexibel|
|geringe Kommunikation mit Kunden nötig|Kann falsche Sicherheit gewähren|
|Testabdeckung einzelner Komponenten als auch des gesamten Systems sehr hoch||

#### Anwendungsbereiche
- Softwareentwicklung 
- Medizintechnik
- Automobilindustrie
- Militär
- Luft- und Raumfahrt
  und viele mehr...

#### Weiterentwicklung
Neben dem klassischen V-Modell exsistieren mittlerweile auch angepasste Versionen des Modells, wie dem V-Modell XT, welches als Standard für viele Projekte der Bundesregierung genutz wird. Auch für agile Projekte und Prozesse wurde das V-Modell zum [W-Modell](https://www.industrie-digitalisierung.com/das-w-modell-systems-engineering-in-der-entwicklung-aktiver-systeme/) weiterentwickelt, um komplizierte schwer zu handhabende Systeme besser koordinieren zu können.[^4][^5]

# Weiterführende Literatur

* Youtube-Video: https://www.youtube.com/watch?v=FxS9LFzpM-o
* Youtube-Video: https://www.youtube.com/watch?v=P0TgRjj8hQg
* V-Modell XT der Bundesregierung genauer erklärt: https://www.microtool.de/wissen-online/wie-funktioniert-v-modell-xt-tailoring/
#### Ähnliche Beiträge
* Wasserfallmodell: https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Wasserfall_Modell.md
* Vorgehensmodelle: https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Vorgehensmodelle.md
# Quellen

[^1]: https://de.wikipedia.org/wiki/V-Modell
[^2]: https://projekte-leicht-gemacht.de/blog/projektmanagement/klassisch/v-modell/
[^3]: https://projekte-leicht-gemacht.de/wp-content/uploads/2021/08/v-modell.jpg
[^4]: https://t2informatik.de/wissen-kompakt/v-modell/
[^5]: https://www.industrie-digitalisierung.com/das-w-modell-systems-engineering-in-der-entwicklung-aktiver-systeme/

