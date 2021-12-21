---
title: Methode_des_kritischen_Pfades
tags:  klassisch
author: ChristinaHartung
anrechnung: k 
---

Die Methode des kritischen Pfades (engl. Critical Path Method CPM) ist ein Projektmanagementtool, welches in den späten 1950er Jahren entwickelt wurde um durch ineffiziente Terminplanung verursachte Kostensteigerungen zu verhindern. Sie ist dem klassischen Projektmanagement zuzuordnen und wird genutzt um zentrale Aufgaben zu ermitteln, die minimale Projektdauer zu determinieren und eine gewisse Planungsflexibilität zu bestimmen.[^1]


## 1. Der kritische Pfad
### 1.1 Was ist der kritische Pfad

“The sequence of activities that represents the longest path through a project with determines the shortest possible duration”[^2]. Vereinfacht gesagt ist der kritische Pfad (engl. Critical Path CP) die längste Zeit, die für den Abschluss eines Projektes benötigt wird.


### 1.2 Zentrale Schritte auf dem Weg zur Identifizierung des kritischen Pfades 

**1.	Bestimmung und Auflistung aller Vorgänge**

Als Grundlage für das weitere Vorgehen wird zunächst ein sogenannter [Projekt-Struktur-Plan](https://de.wikipedia.org/wiki/Projektstrukturplan) (PSP, engl. Work Breakdown Structure WBS) erstellt, welcher nur übergeordnete         Vorgänge enthält. Der Verzicht auf detaillierte Abläufe sorgt dafür, dass der kritische Pfad am Ende nicht zu komplex und unübersichtlich gestaltet ist. [^3]

**2.	Ermittlung aller Abfolgen und Abhängigkeiten**

Im zweiten Schritt stellt sich die Frage, wann welche Aufgaben erledigt werden können und sollen. Hierbei gibt es solche, die parallel zueinander abgeschlossen werden           können, aber auch jene, welche voneinander abhängig sind. Ein Vorgang kann in diesem Fall erst begonnen werden nachdem ein anderer abgeschlossen wurde.[^4]

**3.	Erstellung eines Netzplans**

Im Anschluss folgt die visuelle Darstellung. Hierfür wird ein [Netzplan](https://de.wikipedia.org/wiki/Netzplantechnik) (engl. Critical Path Analysis Chart CPA) entweder per Hand oder mit Hilfe eines Softwareprogramms         gezeichnet.

![Netzplan](/kb/Methode_des_kritischen_Pfades/CriticalPath-DrawNetworkDiagram.png)

*Entwurf eines Netzplans* [^3]

**4.	Abschätzung des Zeitbedarfs aller Aufgaben**

Im nächsten Schritt wird der Zeitaufwand der einzelnen Aufgaben geschätzt. Nützlich kann dabei die Drei-Zeiten-Methode sein, wobei der Zeitbedarf mit         folgenden Werten geschätzt wird:


   *a = Minimalschätzung (Best Case)*
    
   *m = Wahrscheinlichste Schätzung (Most Likely Case)*
    
   *b = Maximalschätzung (Worst Case)*
    
Es ergeben sich schließlich zwei zur Berechnung anwendbare Formeln, E steht dabei für die Schätzung (engl. Estimate):

*I.    E = (a + 4m + b) / 6*

*II.   E = (a + m + b) / 3*
 
 Der Unterschied zwischen I und II besteht lediglich in der Gewichtung der Werte. Während bei der I. gängigeren Methode die wahrscheinlichste Schätzung am stärksten gewichtet     wird, besteht bei II kein Unterschied in der Gewichtung der Werte. 
 Je nach Aufgabe kann es auch sinnvoll sein Pufferzeiten einzuplanen. [^3]
   
**5.	Identifizierung des kritischen Pfades**

Der kritische Pfad wird entweder anhand des Netzplanes per Augenmaß gefunden oder es werden die frühesten Anfangs- und Endzeitpunkte, sowie die spätesten Anfangs- und           Endzeitpunkt jedes Vorgangs festgestellt. Als Resultat ergibt sich ein oder auch mehrere kritische Pfad. Mit jedem weiteren steigt das Risiko für ungeplante             Verzögerungen im Zeitplan.

![Netzplan](/kb/Methode_des_kritischen_Pfades/IdentifyCriticalPath.png)
*Identifizierung des kritischen Pfades* [^3]
    
**6.	Aktualisieren des Netzplans**
    
 Der letzte Schritt beinhaltet die Aktualisierung des Netzplans auf Basis der während des Projekts gesammelten Erfahrungen, die Dauer bestimmter Aufgaben betreffend. Dies        hilft vor allem dabei, den Fortschritt innerhalb des Zeitplans zu beurteilen. 




## 2. Vor- und Nachteile der Methode [^5]

| Vorteile      | Nachteile     |
| ------------- | ------------- |
|Minimierung der Projektdauer| bei Verzögerung eines Vorgangs des CP Verzögerung des ganzen Projekts|
|Einfache Bestimmung besonders wichtiger Aufgaben und Hervorhebung von Projektengpässen|Unterschiedliche subjektive Wahrnehmung der Projektteilnehmer über Relevanz|
|Übersichtliche Darstellung|wenige Möglichkeiten komplexe Abhängigkeiten einfach zu beschreiben|
|Möglichkeit eines Vergleichs des geplanten Fortschritts mit aktuellem Stand und somit frühzeitige Reaktion|Schneller Verbrauch von Pufferzeiten|


# Siehe auch

* [Projektstrukturplan](/kb/Projektstrukturplan.md)
* [Netzplantechnik](/kb/Netzplantechnik.md)

# Weiterführende Literatur

* [The critical path method in estimating project duration](https://www.infona.pl/resource/bwmeta1.element.baztech-c3d822db-42f7-4ad8-8b40-25acdb0518f9)
* [CPM, PERT and Project Management with Fuzzy Logic Technique and Implementation on a Business](https://www.sciencedirect.com/science/article/pii/S1877042815057250)

# Quellen

[^1]: [Critical-Path-Methode: So verwenden Sie die CMP für das Projektmanagement](https://asana.com/de/resources/critical-path-method)
[^2]: [A Guide to the Project Management Body of Knowledge (PMBOK® Guide)](https://www.pmi.org/pmbok-guide-standards/foundational/PMBOK)
[^3]: [Die ultimative Anleitung für den "kritischen Pfad"](https://de.smartsheet.com/critical-path-method)
[^4]: [Was ist die Methode des kritischen Pfades im Projektmanagement?](https://blog.hubspot.de/marketing/kritischer-pfad)
[^5]: [Methode des kritischen Pfades (Wikipedia)](https://de.wikipedia.org/wiki/Methode_des_kritischen_Pfades)


