---
title: Jira_PM_Tool
tags: klassisch
author: MKFAUGithub
anrechnung: k
---

Kurzbeschreibung zu Jira_PM_Tool um ein erstes Verständnis dafür zu schaffen um was es hier geht.

Hier ganz am Anfang keine Überschrift einfügen - das passiert automatisch basierend auf dem `title`-Attribut
oben im Front-Matter (Bereich zwischen den `---`).

# 1. JIRA als PM Tool

Jira ist eine von der Firma Atlassian entwickelte Software, die Ursprünglich für die agile Softwareentwicklung erstellt wurde. Mittlerweile haben sich aber aus dem Ursprünglichen Programm die Unterprodukte Jira Software, Jira Service Management, Jira Work Management und Jira Align entwickelt. [QUELLE]
Für den Themenbereich des Projektmanagements ist das Produkt Jira Software relevant. Hier können Workflows definiert, Aufgaben erstellt und zugewiesen, sowie Fortschritt und Produktivität verfolgt werden. [QUELLE EINFÜGEN]. Neben den Grundfunktionen die Atlassian in Jira selbst anbieten, hat man als Nutzer die Möglichkeit mit Hilfe des Marketplace Applikationen von Drittanbietern zu installieren und somit noch mehr Funktionen zur Verfügung zu haben.


##2. Hosting
Jira kann sowohl als Cloud-Hosting oder als selbstverwaltetes Hosting betrieben werden. Beim Cloud-Hosting wird der Service von Atlassian selber zur Verfügung gestellt und der Nutzer hat lediglich einen finanziellen Aufwand. [QUELLE] Beim selbstständigen Hosten kann mittels Jira Software Data Center die Umgebung auf der eigenen Serverlandschaft oder bei Infrastructure-as-a-Service-Anbietern (IaaS), wie bei Amazon Web Services, Microsoft, Google oder diversen Anbietern verwalten. 

## 3. Preisliste
Bei Atlassian gibt es sehr viele Preismodelle [Quelle]. Hier wird zwischen Cloud- und selbstverwaltetem Hosting unterschieden, aber auch die Nutzerzahl spielt eine Rolle. Ausgehend von 500 Benutzern ergeben sich bei jährlichem Zahlungsturnus folgende Preise: 
ier eine Ebene-2-Überschrift unter Aspekt 2

| Cloud-Hosting | Cloud-Hosting | Selbstverwaltetes Hosting |
| ------------- | ------------- | -------------|
| Standard  | Premium  | Data Center |
| $30.000 pro Jahr  | $48.500 pro Jahr  | $42.000 pro Jahr |

## 4. Funktionsweise
In Jira muss zunächst ein Projekt angelegt werden. Im Anschluss kann eine Vorlage für das Projekt ausgewählt werden, was die Darstellung der Aufgaben beeinflusst. Man kann sich bei Jira-Software zwischen Scrum- und Kanbanboards entscheiden. Im Jira-Projekt können sogenannte Vorgänge erstellt werden, die als Aufgaben, Risiken, Bugs aber auch diverse andere Typen gekennzeichnet werden. Diese Vorgänge müssen während ihrer Bearbeitung einen Workflow durchlaufen, der in den Projekteinstellungen definiert werden kann und für jede Aufgabe gilt. Auf den Projektboards oder extra erstellen Dashboards können die Vorgänge nach bestimmten Kriterien gefiltert dargestellt werden.

## 5. Berechtigungen 
In Jira können vom Administrator diverse Rollen konfiguriert werden, wodurch sichergestellt werden kann, dass nur berechtigte Personen innerhalb eines Projektes die Vorgänge bearbeiten und mitarbeiten können.

## 6. Vorgänge
Aufgaben oder Tickets werden in Jira als Vorgang angelegt. Hierbei kann je nach Bedarf entschieden werden, um welche Art es sich dabei Handeln soll und aus verschiedenen Formaten wie „Aufgabe“, „Unteraufgabe“, „Themes“ eine passende Vorlage auswählen. Beim Erstellen muss ein Titel, sowie eine Beschreibung der Aufgabe hinzugefügt werden bevor diese angelegt werden kann.

## 7. Filter
Mit Hilfe von Filtern kann nach bestimmten Vorgängen gesucht werden. Zum einen kann man als Benutzer direkt auf dem Projektboard mit hinzugefügten Schnell-Filtern per Auswahlliste oder Suchfeld die Ergebnisse einschränken, andererseits hat man die Möglichkeit über Jira-Query-Language (JQL) erweiterte suchen auszuführen. [QUELLE] Diese erweiterten Suchen können auch getrennt von dem Projektboard als eigene Filter abgespeichert werden und so an verschiedenen Stellen wiederverwendet werden.

## 8. Dashboards
Neben den Projektboards gibt es noch Dashboards, die unabhängig davon befüllbar sind. Hier können mit sogenannten Gadgets verschiedene Ergebnisse visualisiert werden. Neben Filterergebnissen, die mit JQL Erstellt worden sind, können hier auch Grafiken und Reports eingebunden werden um einen schnellen Überblick über ein bestimmtes Thema innerhalb eines Projekts zu gewinnen.

## 9. Herausforderungen
Jira kann durch die Menge an Funktionalitäten sehr unübersichtlich wirken. Als Unternehmen muss hier eine klare Vorgehensweise beim Anlegen und Arbeiten mit den Vorgängen gesetzt werden, da sonst unter anpassungsbedarf und Mehraufwand entstehen kann. 

# Siehe auch

* Verlinkungen zu angrenzenden Themen
* [Link auf diese Seite](Jira_PM_Tool.md)

# Weiterführende Literatur

* Weiterfuehrende Literatur zum Thema z.B. Bücher, Webseiten, Blogs, Videos, Wissenschaftliche Literatur, ...

# Quellen

[^1]: Quellen die ihr im Text verwendet habt z.B. Bücher, Webseiten, Blogs, Videos, Wissenschaftliche Literatur, ... (eine Quelle in eine Zeile, keine Zeilenumbrüche machen)
[^2]: [A Guide to the Project Management Body of Knowledge (PMBOK® Guide)](https://www.pmi.org/pmbok-guide-standards/foundational/PMBOK)
[^3]: [Basic Formatting Syntax for GitHub flavored Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
[^4]: [Advanced Formatting Syntax for GitHub flavored Markdown](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)



###########################
JIRA als PM Tool
Jira ist eine von der Firma Atlassian entwickelte Software, die Ursprünglich für die agile Softwareentwicklung erstellt wurde. Mittlerweile haben sich aber aus dem Ursprünglichen Programm die Unterprodukte Jira Software, Jira Service Management, Jira Work Management und Jira Align entwickelt. [QUELLE EINFÜGEN]. 
Für den Themenbereich des Projektmanagements ist das Produkt Jira Software relevant. Hier können Workflows definiert, Aufgaben erstellt und zugewiesen, sowie Fortschritt und Produktivität verfolgt werden. [QUELLE EINFÜGEN]. Neben den Grundfunktionen die Atlassian in Jira selbst anbieten, hat man als Nutzer die Möglichkeit mit Hilfe des Marketplace Applikationen von Drittanbietern zu installieren und somit noch mehr Funktionen zur Verfügung zu haben.
Hosting
Jira kann sowohl als Cloud-Hosting oder als selbstverwaltetes Hosting betrieben werden. Beim Cloud-Hosting wird der Service von Atlassian selber zur Verfügung gestellt und der Nutzer hat lediglich einen finanziellen Aufwand. [QUELLE] Beim selbstständigen Hosten kann mittels Jira Software Data Center die Umgebung auf der eigenen Serverlandschaft oder bei Infrastructure as a Service-Anbietern (IaaS), wie bei Amazon Web Services, Microsoft, Google oder diversen Anbietern verwalten. Während dieser Ansatz für Enterprise-Teams empfohlen wird, da die verwaltung und Administration in eigener Hand liegt, ist es für kleinere Unternehmen und Teams meist sinnvoll auf die Cloud zurückzugreifen, da hier keine extra Ressourcen für das eigenständige Betreiben der Software notwendig sind. [Quelle]


