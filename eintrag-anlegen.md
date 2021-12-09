---
title: Eintrag anlegen
tags: orga
---

Im folgenden wird das Vorgehen für die Erstellung des Kompendiums beschrieben.

# Themenzuordnung

* Die [Finale Themenzuordnung](Themenzuordnung.md) ist jetzt fertig.
* Themenwechsel sind nicht mehr möglich
* Falls ihr von einem Thema zurücktreten möchtet dann bitte dem MPS-Lehrstuhl-Team bescheid geben.


# Zeitplan

* Phase 1

  - 2021-11-02 Start der Beitragserstellung
  - 2021-11-24 23:59 Uhr Deadline erste Version des Beitrags
  - 2021-12-08 23:59 Uhr Deadline Einreichung Review
  - 2021-12-21 23:59 Uhr Deadline verbesserte Version des Beitrag
  - ~~2021-11-17 Deadline erste Version des Beitrags~~
  - ~~2021-11-29 Deadline Feedback~~
  - ~~2021-12-13 Deadline Abgabe Finale Version Beitrag~~

* Phase 2
  - 2022 Start von Phase 2, Ausgestaltung abhängig von Phase 1
  
## Anmerkungen

* TODO: dem [ws_21_22](https://github.com/orgs/ManagingProjectsSuccessfully/teams/ws_21_22)-Team auf GitHub beitreten.
* Mit der Bearbeitung erst nach der Vorlesung am 2.11.2021 beginnen, bis dahin sind noch substantielle Änderungen and dem Repository möglich.
  - Wenn ihr ein Thema nicht bearbeiten wollt (weil ihr z.B. das Scrum-Zertifikat machen möchtet) dann teilt uns das bitte mit.
  
## Phase 1

Die erste Phase beinhaltet folgende Schritte:
* Erstellung des Beitrags
  - Erstellen des Beitrags (Studierende)
  - Einreichung via Pull-Request (Studierende)
* Review-Schritt
  - Zuweisung von Reviewern zu Pull-Requests (MPS-Lehrstuhl-Team)
  - Verfassen von 3 Reviews pro verfasstem Beitrag (Studierende)
  - Überarbeitung des eigenen Beitrags basierend auf dem Feedback der Reviewer:innen und Aktualisierung des Pull-Requests (Studierende)
  - Prüfung der Überarbeitung durch Reviewer (Studierende)
  - Hinzufügen der Beiträge zum MPS-Kompendium wenn Beitrag von Reviewern freigegeben wurde (MPS-Lehrstuhl-Team)

  
### Konkretes Vorgehen zur Erstellung des Beitrags

* Fork von zentralem Repository erstellen
* Datei für eigenes Thema vorbereiten
  - Zu jedem Thema existiert eine Markdown-Datei (z.B. Projekt.md) und ein Ordner (z.B. Projekt)
  - In der Projekt.md Datei ganz oben (front-matter):
    - GitHub account Namen eintragen und tags für euer Thema vergeben, gerne auch mehrere durch Leerzeichen getrent (evtl. auch erst später)
    - bei `anrechnung` eintragen ob der Beitrag für klassisches (k) oder agiles (a) Projektmanagement angerechnet werden soll
* In Thema einlesen
* Bezüge zu anderen Artikeln Herstellen
  - Beispiel: [Kanban](kb/Kanban.md) und [Kanban_Boards](kb/Kanban_Boards.md). Der Kanban-Artikel adressiert Kanban allgemein und gibt kurze Übersicht und Verlinkung zu Unterthemen.
  - Ggf. in die Forks von Kommiliton:innen schauen um dort aktuellen Stand zu sehen (Wichtig für alle: Regelmäßig Commits machen und Pushen).
* Materialien sammeln
  - Inhaltlich (in Markdown-Datei) evtl. am Ende einen temporären Abschnitt zur Stoffsammlung einfügen der am Ende dann wieder gelöscht werden kann. 
  - Abbildungen in entsprechendem Ordner ablegen und einbinden.
* Struktur für den Artikel erstellen
  - Was sind relevante Aspekte?
  - Einordnung in den Gesamtzusammenhang
* Artikel füllen
  - Text (mit Verlinkungen)
  - Abbildungen
  - Tabellen
* Rechtschreibung und Grammatik prüfen
* Links prüfen
* Pull-Request erstellen
  - Update ([fetch upstream](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork)) des eigenen Repositories
  - ggf. Konflikte auflösen
  - Pull-Request erstellen
  
### Konkretes Vorgehen für den Review-Schritt

* Die Beiträge zu denen Reviews verfasst werden sollen, werden durch das MPS-Lehrstuhl-Team zugewiesen (3 Reviews pro Beitrag)
* [Review-Funktionalität](https://docs.github.com/en/github/collaborating-with-pull-requests/reviewing-changes-in-pull-requests) von GitHub nutzen um Review zu erstellen.
  - Detailiertes Review (Allgemeine Kommentare, Zeilenbasierte Anmerkungen, Änderungsvorschläge)
  - Ergebnis von Review kann "Request Changes" oder "Approve" sein
    - Anmerkung: Approve beim ersten mal ist unwahrscheinlich weil meistens noch Verbesserungspotential vorhanden ist.
* Überarbeitung des eigenen Beitrags basierend auf den Reviews
* Aktualisierung des Pull-Requests (neuer commit und nochmal pull-request stellen)
* Überprüfung der Änderungen durch Reviewer
* Bei Freigabe durch die Reviewer: Merge in MPS-Kompendium

## Phase 2

Start 2022



# Kriterien

Die folgenden Kriterien werden für die Bewertung der Beiträge herangezogen. Pull-Requests von Beiträgen die eines der Ko-Kriterien (s. Tabelle) nicht erfüllen werden abgelehnt. Nach einer Ablehnung ist es im entsprechenden Zeitraum möglich einen aktualisierten Pull-Request zu stellen. Es werden nur Beiträge bewertet deren Pull-Requests von uns in das zentrale Repository gemerged werden.

| Kriterium | Erklärung | Ko-Kriterium |
|-----|---|---|
| Anpassungen an anderen Beiträgen | Bei der Einreichung dürfen nur Anpassungen an den eigenen Beiträgen vorgenommen worden sein | x |
| Front-Matter | Metadaten im Front-Matter korrekt ausgefüllt | x |
| Umfang | ca. 500 Wörter ohne Quellenverweise | x |
| Strukturierung des Beitrags | Inhaltlich und Visuell (z.B. durch Überschriften) | x |
| Rechtschreibung | Achtet bitte auf Korrekte Rechtschreibung und Grammatik | x |
| Sprache | Deutsch, Sachlich (Enzyklopädiestil s. Wikipedia) | x |
| Belege | Quellen zu den Inhalten angeben (auch bei Abbildungen) und prüfen ob die Links funktionieren | x |
| Formatierung | Korrekte Formatierung wie z.B. Überschriften zur Strukturierung, Punktelisten für Aufzählungen | x |
| Verlinkungen | Zu Unter- und Überthemen sowie zu angrenzenden Themengebieten | x |
| Abbildungen | Mindestens eine Abbildung / Visualisierung | x |
| Tabellen | Abhänging vom Inhalt | |
| Inhaltlich | Inhaltliche Korrektheit, wichtigste Aspekte zum Thema sind vorhanden |
| Einordnung | Einordnung in Bezug auf angrenzende Themengebiete |
| Ansprechend für Zielgruppe | Kommiliton:innen erhalten durch den Beitrag einen guten Überblick über das entsprechende Thema, haben Spaß beim Lesen des Artikels und folgen den Verlinkungen |


Der Bearbeitungszeitraum wird über MS-Teams bekanntgegeben.

## Hinweise zu den Kriterien

* Die Anzahl der Wörter kann z.B. ermittelt werden indem der Text in Microsoft Word oder LibreOffice Writer kopiert wird.

# Tipps

* Regelmäßig Commits erstellen (z.B. eine Abbildung eingefügt, einen Absatz geschrieben) und pushen.
* Formatierungshinweise
  - Tabellarische Daten als Tabelle formatieren (nicht als Abbildung einfügen)
  - Ebenen von Überschriften beachten
* Schreibtipps:
  - Nicht gleich nach Perfektionismus streben
  - Ein erster vollständiger Entwurf ist besser als ein perfekter Satz
  - Entwurf dann Stück für Stück überarbeiten
* Die Beiträge sollen bestehendes und gesichertes Wissen abbilden (keine eigenen Interpretationen)
* Orientierung an Wikipedia
