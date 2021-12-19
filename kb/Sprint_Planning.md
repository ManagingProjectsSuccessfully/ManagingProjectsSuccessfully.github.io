---
title: Sprint_Planning
tags: agil
author: faucahvd
anrechnung: a
---

*Sprint Planung* (Von englischem Sprint-Planing) ist eine von allen fünf "Events" des agilen Tools Scrum.
# Inhalt
1. [Sprint-Planung](#sprint-planung)
2. [Das Meeting](#das-meeting)
3. [Sprint-Planing erklärt anhand eines Beispiels](#sprint-planing-erklärt-anhand-eines-beispiels)
4. [Auch interessant](#auch-interessant)
5. [Quellen](#quellen)

# Sprint-Planung

Zwischen der `Product Planung` und dem tatsächlichen [Sprint](#sprint), befindet sich die `Sprint-Planung`.
*Diese* ist ein Meeting, um den eigentlichen Sprint zu planen. Die Funktion des Meetings ist, zu definieren, welche Anforderugen also `was` und `wie` sie umgesetzt werden sollen. Das Ziel vom Sprint-Planungsmeeting ist es, vom gesamten [Produkt-Backlog](Product_Backlog.md) einen Teil, also das Sprint-Backlog[^8] zu erstellen.[^1]

In [SCRUM](SCRUM.md) gibt es 5 verschiedene Events(Ereignisse). Sprint-Planung ist nur ein Vorgang ("EVENT") davon.
Die anderen Events teilen sich auf in: 
+ [Sprint](Sprint.md)
+ [Daily Scrum](Daily_Scrum.md)
+ [Sprint Review](Sprint_Review.md)
+ [Retrospektive](Retrospective.md) 

Events sind zentrale und strukturelle Elemente von [Scrum](SCRUM.md). Sie habe nach Scrum-Definition, eine ganz spezielle Charakteristika[^2]. Sie müssen regelmäßig stattfinden. Diese Regelmäßigkeit sorgt dafür, den interaktiven Charakter von Scrum sicherzustellen. Die Vorgehensweise ist in der Regel, dass für jedes Ereignis, ein fester Zeitintervall vorgegeben ist. Zum Beispiel Daily Scrum ist jeden Tag 15 min[^4].
   
#### *__Sprint__*  
Ein [Sprint](Sprint.md) ist ein festgelegter Zeitraum, in dem man die zuvor geplante Arbeit erldigt. Deshalb benötigt man `Sprint-Planing`. Während Sprint-Planing legt das gesamte Scrum-Team ([Product-Owner](Product_Owner.md), [Scrum-Master](Rollen_Scrum.md), [Entwicklerteam](Rollen_Scrum.md)) das Ziel und das Sprint-Backlog fest. Das Sprint-Planungsmeeting umfasst, wie oben genannt, zwei Teile:[^6]
- was? - Der erste fokusiert sich auf das *WAS* und klärt, welche Anforderungen im Laufe des Sprints umgesetz werden sollen.[^6]
- wie? - Der zweite fokusiert sich auf das *WIE*. 'Wie sollen die Anforderugen (Ziele) erreicht werden?' Das Entwlicklerteam plant die Aufgaben, um das Ziel des Sptrints zu erreichen.[^6]


![SCRUM](Sprint_Planning//sprint-planungsmeeting.png)
*Die Vorgehensweise nach Scrum-Definition*[^3]

# Das Meeting
Der Vorgang von `Sprint-Planing` steht am Anfang eines Sprints. Bei dem Sprint-Planungsmeeting ist das [Entwicklerteam](Rollen_Scrum.md) und der [Product-Owner](Product_Owner.md) dabei. Beide zusammen planen den nächsten [Sprint](#sprint). Der Blick wird gerichtet auf die nächsten 2 oder 3 Wochen (unterschiedlich je nachdem wie lange der Sprint dauert). Der Sprint-Planing dient dazu die Anforderungen, die in [Product-Backlog](Product_Backlog.md) vorhanden sind, mit dem Team durchzusprechen. Und zwar nur die wichtigsten Requirements, um daraus das sogenanten Sprint-Backlog zu formen. Also das Ziel des Events ist aus dem [Product-Backlog](Product_Backlog.md), die wichtigsten Anforderungen in den Sprint-Backlog zu überführen. Deswegen wird die Sprint-Planing im Allgemeinen in zwei Teile geteilt.[^3]

### - TEIL 1: WAS?
Im ersten Teil spielt der [Product-Owner](Product_Owner.md) eine sehr wichtige Rolle – hier wird besprochen und geklärt, WAS an Anforderungen umzusetzen ist. Hier muss das [Entwicklerteam](Rollen_Scrum.md) verstanden haben, um was es geht. Was die Anforderungen sind? Was Fachlich hinter den Anforderungen steckt.[^4]

### - TEIL 2: WIE?
Der zweite Teil findet ohne [Product-Owner](Product_Owner.md) statt, da das Team die Anforderungen diskutiert, die das Developerteam in dem [Sprint](Sprint.md) abarbeiten möchte oder kann. Das Kriterium ist hier WIE? Also von den User-Storys vom [Product-Backlog](Product_Backlog.md) bildet das Team die Tasks, das sogenannte `'Sprint-Backlog'`. Somit weiß das Team, was zu tun ist. Hier im Sprint-Backlog befinden sich die User-Storys und daneben die einzelnen Tasks, die abzuarbeiten sind.[^4]

### *Definition of Done DoD*
Im Sprint-Planing Event ist die ``'Definition of Done'`` (DoD), eine sehr wichtige Sache. Es bedeutet, dass der [Product-Owner](Product_Owner.md) eine Art Vertrag mit dem [Entwicklerteam](Rollen_Scrum.md) schließt, in dem festgehalten wird, welche Anforderung die User-Storys haben müssen, damit sie in den [Sprint](Sprint.md) aufgenommen werden. Das Team muss verstanden haben, um was es geht.[^5]

# Sprint-Planing erklärt anhand eines Beispiels #

Nehmen wir an, unser Kunde will eine statische [HTML-Webseite](https://stadtprofil-fuerth.de/#contact) für sein Portfolio bauen lassen. Der [Product-Owner](Product_Owner.md) hat schon mit ihm abgestimmt, welche Anforderungen er haben möchte. Im [Product-Backlog](Product_Backlog.md) stehen schon die auflisteten User-Storys priosiert. Der P.O. wählt die wichtigsten Anforderungen für den folgenden [Sprint](Sprint.md) aus. Folgendes Szenario (User-Story) sei gegeben: 
```
"Als Nutzer der Webseite will ich ein Kontakt-Formular, um Fragen an die Firma zu stellen."
```
Der [Product-Owner](Product_Owner.md) trifft sich mit dem [Entwicklerteam](Rollen_Scrum.md) (Sprint-Planing). Er stellt die Wünsche des Kunden und die User-Story vor. Dann diskutiert das [Developerteam](Rollen_Scrum.md)unter sich, ob es möglich ist, die Anforderung umzusetzen und wie sie umgesetzt werden soll. Das Team entscheidet sich, zuerst um Frontend zu kümmern. Von der User-Story werden die Tasks gebildet und in Sprint-Backlog hineingenommen. 
Mögliche Aufgaben (Tasks): 
```
* `<button>, <input>, <form> an Designvorgaben anpassen` 
* `Layout aufsetzen` 
* `Schriftart anbinden` 
* usw. 
```
Und so fängt der [Sprint](Sprint.md) an. 

# Auch interessant
+ [SCRUM](SCRUM.md)
+ [Produkt-Backlog](Product_Backlog.md)
+ [Sprint-Backlog](sorry-keon-lint)
+ [Sprint](Sprint.md)
+ [Product-Owner](Product_Owner.md)
+ [Entwicklerteam](Rollen_Scrum.md)
+ [Daily Scrum](Daily_Scrum.md)
+ [Sprint Review](Sprint_Review.md)
+ [Retrospektive](Retrospective.md)
 
# Quellen
[^1]: [Sprint Planing| Projektmagzin](https://www.projektmagazin.de/methoden/sprint-planning)
[^2]: [Die Events in SCRUM](https://www.agile-heroes.de/magazine/scrum-events)
[^3]: [Die fünf formellen Scrum Events im Projektmanagement](https://projektmanagement-zentrum.ch/2019/03/04/scrum-events/)
[^4]: [Timeboxing ](https://projektmanagement-zentrum.ch/2019/03/04/scrum-events/)
[^5]: [Sprint-Planungsmeeting ](https://projektmanagement-zentrum.ch/2019/03/04/scrum-events/)
[^6]: [Sprint-Planung ](https://www.atlassian.com/de/agile/scrum/sprint-planning)
[^7]: [Product Backlog ](https://www.projektmagazin.de/glossarterm/product-backlog)
[^8]: [Sprint Backlog ](https://www.projektmagazin.de/glossarterm/sprint-backlog)