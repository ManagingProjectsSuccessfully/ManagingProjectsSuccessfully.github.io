---
title: Jira_PM_Tool
tags: klassisch Jira Projektmanagement Tracking
author: MKFAUGithub
anrechnung: k
---


Jira ist eine von der Firma Atlassian entwickelte Software, die Ursprünglich für die agile Softwareentwicklung erstellt wurde. Mittlerweile haben sich aber aus dem Ursprünglichen Programm die Unterprodukte Jira Software, Jira Service Management, Jira Work Management und Jira Align entwickelt. [QUELLE]
Für den Themenbereich des Projektmanagements ist das Produkt Jira Software relevant. Hier können Workflows definiert, Aufgaben erstellt und zugewiesen, sowie Fortschritt und Produktivität verfolgt werden. [QUELLE EINFÜGEN]. Neben den Grundfunktionen die Atlassian in Jira selbst anbieten, hat man als Nutzer die Möglichkeit mit Hilfe des Marketplace Applikationen von Drittanbietern zu installieren und somit noch mehr Funktionen zur Verfügung zu haben.

## 1. Hosting
Jira kann sowohl als Cloud-Hosting oder als selbstverwaltetes Hosting betrieben werden. Beim Cloud-Hosting wird der Service von Atlassian selber zur Verfügung gestellt und der Nutzer hat lediglich einen finanziellen Aufwand. [QUELLE] Beim selbstständigen Hosten kann mittels Jira Software Data Center die Umgebung auf der eigenen Serverlandschaft oder bei Infrastructure-as-a-Service-Anbietern (IaaS), wie bei Amazon Web Services, Microsoft, Google oder diversen Anbietern verwalten. 

## 2. Preisliste
Bei Atlassian gibt es sehr viele Preismodelle [Quelle]. Hier wird zwischen Cloud- und selbstverwaltetem Hosting unterschieden, aber auch die Nutzerzahl spielt eine Rolle. Ausgehend von 500 Benutzern ergeben sich bei jährlichem Zahlungsturnus folgende Preise: 


| Cloud-Hosting | Cloud-Hosting | Selbstverwaltetes Hosting |
| ------------- | ------------- | -------------|
| Standard  | Premium  | Data Center |
| $30.000 pro Jahr  | $48.500 pro Jahr  | $42.000 pro Jahr |

## 3. Funktionsweise
In Jira muss zunächst ein Projekt angelegt werden. Im Anschluss kann eine Vorlage für das Projekt ausgewählt werden, was die Darstellung der Aufgaben beeinflusst. Man kann sich bei Jira-Software zwischen Scrum- und Kanbanboards entscheiden. Im Jira-Projekt können sogenannte Vorgänge erstellt werden, die als Aufgaben, Risiken, Bugs aber auch diverse andere Typen gekennzeichnet werden. Diese Vorgänge müssen während ihrer Bearbeitung einen Workflow durchlaufen, der in den Projekteinstellungen definiert werden kann und für jede Aufgabe gilt. Auf den Projektboards oder extra erstellen Dashboards können die Vorgänge nach bestimmten Kriterien gefiltert dargestellt werden.

### 3.1 Scrum Board
![Scrum Board](Jira_PM_Tool/scrum_backlog_full.png)

### 3.2 Kanban Board
![Jira Kanban Board](Jira_PM_Tool/screenshot_JSW_KanbanBoard.png)

## 4. Berechtigungen 
In Jira können vom Administrator diverse Rollen konfiguriert werden, wodurch sichergestellt werden kann, dass nur berechtigte Personen innerhalb eines Projektes die Vorgänge bearbeiten und mitarbeiten können.

## 5. Vorgänge
Aufgaben oder Tickets werden in Jira als Vorgang angelegt. Hierbei kann je nach Bedarf entschieden werden, um welche Art es sich dabei Handeln soll und aus verschiedenen Formaten wie „Aufgabe“, „Unteraufgabe“, „Themes“ eine passende Vorlage auswählen. Beim Erstellen muss ein Titel, sowie eine Beschreibung der Aufgabe hinzugefügt werden bevor diese angelegt werden kann.

![Jira Vorgangserstellung](Jira_PM_Tool/Jira_Issue.png)

## 6. Filter
Mit Hilfe von Filtern kann nach bestimmten Vorgängen gesucht werden. Zum einen kann man als Benutzer direkt auf dem Projektboard mit hinzugefügten Schnell-Filtern per Auswahlliste oder Suchfeld die Ergebnisse einschränken, andererseits hat man die Möglichkeit über Jira-Query-Language (JQL) erweiterte suchen auszuführen. [QUELLE] Diese erweiterten Suchen können auch getrennt von dem Projektboard als eigene Filter abgespeichert werden und so an verschiedenen Stellen wiederverwendet werden.

![JQL_Beispiel](Jira_PM_Tool/JQL_Example.png)

## 7. Dashboards
Neben den Projektboards gibt es noch Dashboards, die unabhängig davon befüllbar sind. Hier können mit sogenannten Gadgets verschiedene Ergebnisse visualisiert werden. Neben Filterergebnissen, die mit JQL erstellt worden sind, können hier auch Grafiken und Reports eingebunden werden um einen schnellen Überblick über ein bestimmtes Thema innerhalb eines Projekts zu gewinnen.

## 8. Herausforderungen
Jira kann durch die Menge an Funktionalitäten sehr unübersichtlich wirken. Als Unternehmen muss hier eine klare Vorgehensweise beim Anlegen und Arbeiten mit den Vorgängen gesetzt werden, da sonst unter anpassungsbedarf und Mehraufwand entstehen kann. 

# Siehe auch

* [Kanban](https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Kanban.md)
* [Kanban Boards](https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Kanban_Boards.md)
* [Scrum](https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/SCRUM.md)
* [Product Backlog](https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Product_Backlog.md)
* [Sprint Backlog](https://github.com/ManagingProjectsSuccessfully/ManagingProjectsSuccessfully.github.io/blob/main/kb/Sprint_Backlog.md)

# Weiterführende Literatur

* Weiterfuehrende Literatur zum Thema z.B. Bücher, Webseiten, Blogs, Videos, Wissenschaftliche Literatur, ...
* [Kanban Boards in Jira](https://support.atlassian.com/jira-software-cloud/docs/monitor-work-in-a-kanban-project/)
* [Jira Issue Types](https://support.atlassian.com/jira-cloud-administration/docs/what-are-issue-types/)

# Quellen

[^1]: Quellen die ihr im Text verwendet habt z.B. Bücher, Webseiten, Blogs, Videos, Wissenschaftliche Literatur, ... (eine Quelle in eine Zeile, keine Zeilenumbrüche machen)
[^2]: [A Guide to the Project Management Body of Knowledge (PMBOK® Guide)](https://www.pmi.org/pmbok-guide-standards/foundational/PMBOK)
[^3]: [Basic Formatting Syntax for GitHub flavored Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
[^4]: [Advanced Formatting Syntax for GitHub flavored Markdown](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables)
[^5]: [What is a Board](https://confluence.atlassian.com/jirasoftwareserver/what-is-a-board-938845235.html)
[^6]: [What is a Jira-SoftwareBoard](https://support.atlassian.com/jira-software-cloud/docs/what-is-a-jira-software-board/)
[^7]: [Jira Issue](https://stiltsoft.com/blog/2020/06/best-practices-for-creating-a-jira-issue-with-templates/)


## Bilder
 Scrum Backlog https://confluence.atlassian.com/jirasoftwareserver/using-your-scrum-backlog-938845361.html
 Kanban Board https://support.atlassian.com/jira-software-cloud/docs/monitor-work-in-a-kanban-project/
 Jira Issue https://stiltsoft.com/blog/2020/06/best-practices-for-creating-a-jira-issue-with-templates/

 

