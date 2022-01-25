---
title: Java_PM_Tool
tags: agil Java OpenSource
author: AbderrahmaneBennani
anrechnung: a
---

Im Folgenden wird beschrieben, wie man Java Tools benutzt, um Projekte agile zu managen.
# Java Projektmanagement Tools

**Java** ist eine objektorientierte Programmiersprache und eine eingetragene Marke des Unternehmens
Sun Microsystems, welches 2010 von
Oracle aufgekauft wurde. Die Programmiersprache ist ein Bestandteil der 
Java-Technologie – diese besteht grundsätzlich aus dem Java-Entwicklungswerkzeug
(JDK) zum Erstellen von Java-Programmen und der
Java-Laufzeitumgebung (JRE) zu deren Ausführung.[^1]

Als [Projektmanagement](Projektmanagement.md) wird das Initiieren, Planen, Steuern, Kontrollieren und Abschließen von Projekten bezeichnet.
Viele Begriffe und Verfahrensweisen im Projektmanagement sind etabliert und standardisiert.[^2]

Durch [Open source](Open_Source_Projekte.md) Java [Projekte](Projekt.md) (Tools) kann man verschiedene Aspekte eines Projekts steuern, planen usw. In Diesem Artikel kann man ein paar Tools und deren Umsetzung kennenlernen.

![PMToolsabbildung](Java_PM_Tool/PMTools.png)

## Projektplanen & Verfolgung

**Xplanner**  ist ein webbasiertes Projektplanungs- und -verfolgungstool für eXtreme Programming (XP)-Teams. XPlanner ist mit Java, JSP und Struts, Hibernate und MySQL implementiert.

![Xplannerabbildung](Java_PM_Tool/Xplanner.jpg)

Das XP-Planungsprozess[^3] kann man in 3 Schritte zusammenfassen:

1.	Die Kunden wählen die hinzufügenden Funktionen (User Stories) für jede Entwicklungsiteration aus (in der Regel eine bis drei Wochen).
2.	Die Entwickler schätzen den Aufwand für die Fertigstellung der Storys, entweder auf der Ebene der Story oder durch Zerlegung der Story in Aufgaben und deren Schätzung.
3.	Informationen über die Entwicklungsgeschwindigkeit des Teams aus der vorherigen Iteration werden verwendet, um abzuschätzen, ob das Team die vom Kunden vorgeschlagenen Storys rechtzeitig fertigstellen kann.

Wenn das Team überfordert ist, wird die Menge der Storys mit dem Kunden neu verhandelt. Das XPlanner-Tool wurde zur Unterstützung dieses Prozesses entwickelt.

Projekte wie **XPlannerPlus** setzen dort an, wo das alte XPlanner-Projekt aufgehört hat. XPlannerPlus erweitert die Funktionen und macht die Benutzeroberfläche ein wenig schicker.

## Projektverwaltung

**Activity Manager** ist ein Werkzeug für die Projektverwaltung. Es hilft einem [Projektleiter](Projektleiter.md), die Aktivitäten seiner Mitarbeiter zu verwalten und zu überprüfen. Einfach zu bedienen, leichtgewichtig, aber sehr effizient und anpassbar.

![ActivityManagerabbildung](Java_PM_Tool/ActivityManager.png)

Die Merkmale des Tools sind:

* Repository-Verwaltung für Zeiträume
* Repository-Verwaltung für Projektbeteiligte (Collaborators)
* Repository-Verwaltung für Aufgaben (Tasks)
* Beiträge verwalten (Contributions)
* Erweiterbare Berichtsfunktion (mit eingebauten Vorlagen)
* XML-Datenbank Export/Import
* EXCEL-Export

Activity Manager ermöglicht den Aufbau und die Pflege eines hierarchischen Aufgabenbaums. Mit Hilfe eines sehr einfachen Datenbankmodells, ist es möglich, schnell benutzerdefinierte Berichte über die Berichtsfunktion oder über einfache SQL-Anfragen zu erstellen.[^4]
## Auswertung & Prognosen
**GanttProject** ist ein kostenloses und einfach zu bedienendes, auf Gantt-Diagrammen basierendes Werkzeug zur Projektplanung und -auswertung.

![GanttProjectabbildung](Java_PM_Tool/GanttProject.jpg)

Es kommt mit:

* Aufgabenhierarchie und Abhängigkeiten, Meilensteine, Baselines.
* [Gantt-Diagramm](Gantt_Diagramme.md) mit einer Option zur Erstellung eines PERT-Diagramms.
* Diagramm der Ressourcenauslastung.
* Berechnung der Aufgabenkosten.
* Exportieren in PDF, HTML, PNG.
* Interoperabilität mit [MS Project](Microsoft_Project_PM_Tool.md), Excel und anderen Tabellenkalkulationsprogrammen.
* Einfache WebDAV-basierte Zusammenarbeit.

Außerdem ist ein kommerzieller Kollaborationsdienst, GanttProject Cloud, in GanttProject integriert.[^5]

## Weitere Anwendungen
### Softwareentwicklungsprozess
Das **Plandora-Projekt** wurde als Werkzeug zur Unterstützung des **Softwareentwicklungsprozesses** von der Kundenanforderung bis zum Abschluss der Aufgabe und somit zur Erfassung der "Geschichte" eines Projekts entwickelt. Das Plandora-System kann für Teams nützlich sein, die Probleme mit Ressourcenengpässen, parallelen Projekten, kritischen Terminen, der Notwendigkeit der Dokumentation des Umfangs von Aufgaben und Anforderungen usw. haben.[^6]
### Zeitverfolgung
Mit **Baralga** können Sie den Überblick über die Zeit behalten, die Sie für verschiedene Projekte aufwenden. Sie können die Projekte, an denen Sie arbeiten, aufzeichnen, oder Sie können Projektaktivitäten manuell eingeben und bearbeiten. So können Sie sich leicht merken, wann und wie lange Sie an jedem Projekt gearbeitet haben.[^7]

# Fazit
Zusammenfassend lässt sich sagen, dass eine beliebige Kombination der oben genannten Tools für die Verwaltung eines Projekts verwendet werden kann, je nachdem, welche spezifischen Funktionen benötigt werden.

# Verlinkungen zu angrenzenden Themen
* [Projekt](Projekt.md)
* [Projektmanagement](Projektmanagement.md)
* [Open_Source_Projekte](Open_Source_Projekte.md)
* [Gantt_Diagramme](Gantt_Diagramme.md)
* [Microsoft_Project_PM_Tool](Microsoft_Project_PM_Tool.md)

# Weiterführende Literatur

* [Open Source Project Management Tools in Java](https://java-source.net/open-source/project-management)

# Quellen

[^1]: [Java (Programmiersprache) - Wikipedia](https://de.wikipedia.org/wiki/Java_(Programmiersprache))
[^2]: [Projektmanagement - Wikipedia](https://de.wikipedia.org/wiki/Projektmanagement)
[^3]: [Xplanner Synopsys - Openhub](https://www.openhub.net/p/xplanner)
[^4]: [Activity Manager - Sourceforge](http://activitymanager.sourceforge.net/overview.html)
[^5]: [Ganttproject - ReadMe](https://github.com/bardsoftware/ganttproject/blob/5fdedc22d8a6dbed68820d433e1cc51b0e77b2f4/README)
[^6]: [Plandora - Javasource](https://java-source.net/open-source/project-management/plandora)
[^7]: [Barlaga - JavaSource](https://java-source.net/open-source/project-management/baralga)
