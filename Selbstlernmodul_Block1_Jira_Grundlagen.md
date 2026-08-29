# Selbstlernmodul – Block 1: Jira-Grundlagen und Projektstruktur

**Bearbeitungszeit:** ca. 3 Stunden  
**Voraussetzung:** Zugang zur bereitgestellten Jira-Trainingsumgebung  
**Projektszenario:** Das im Kick-off vorgestellte Projekt **Firmenumzug**

---

## 1. Lernziele

Nach Bearbeitung dieses Moduls können Sie:

- erklären, welche Rolle Jira im Projektmanagement übernehmen kann,
- sich in einer Ihnen noch unbekannten Jira-Umgebung orientieren,
- Projekt/Space, Vorgang/Work Item, Vorgangstyp, Status, Workflow und Board unterscheiden,
- Vorgänge anlegen und bearbeiten,
- Verantwortlichkeiten, Prioritäten und Termine hinterlegen,
- Kommentare und Anhänge verwenden,
- Vorgänge miteinander verknüpfen,
- einen vorhandenen Workflow zur Bearbeitung von Vorgängen verwenden,
- den Unterschied zwischen Workflow und Board erklären,
- erkennen, welche Bestandteile einer Jira-Umgebung vorgegeben bzw. administrativ konfiguriert sind.

### Was Sie in diesem Modul nicht lernen

Dieses Training ist eine **Anwender- und Projektmanagementschulung**.

Sie konfigurieren deshalb keine:

- Workflows,
- Vorgangstypen,
- Felder,
- Screens,
- Berechtigungen,
- Automatisierungsregeln,
- anderen administrativen Jira-Einstellungen.

Sie lernen stattdessen, eine vorhandene Jira-Konfiguration zu **verstehen und sinnvoll zu nutzen**.

---

## 2. Lernphase 1 – Jira kennenlernen

**Zeitbedarf:** ca. 20 Minuten

Jira ist ein Werkzeug zur Planung, Organisation und Nachverfolgung von Arbeit. Obwohl Jira historisch stark mit Softwareentwicklung verbunden ist, kann es auch zur Organisation anderer Projektarten eingesetzt werden.

Im Projekt **Firmenumzug** könnten beispielsweise folgende Arbeiten mit Jira nachverfolgt werden:

- Raumplanung abstimmen
- Umzugsunternehmen auswählen
- Internetanschluss bereitstellen
- Netzwerkverkabelung abschließen
- Möbel bestellen
- Zutrittskarten erstellen
- Mitarbeitende informieren

Jira hilft insbesondere dabei, Fragen zu beantworten wie:

- Was muss erledigt werden?
- Wer ist verantwortlich?
- In welchem Zustand befindet sich eine Aufgabe?
- Wann muss sie erledigt sein?
- Welche Aufgaben hängen voneinander ab?

### Online-Ressourcen

**Atlassian Learning – Get started with Jira**  
https://learning.atlassian.com/learning/path/get-the-most-out-of-jira/course/get-started-with-jira

Bearbeiten Sie zunächst insbesondere die Abschnitte zur Einführung und Navigation.

**Atlassian – Grundlagen der Arbeit mit Jira**  
https://www.atlassian.com/de/software/jira/guides/getting-started/basics

### Reflexionsaufgabe

Beantworten Sie anschließend für sich:

1. Was ist in Jira das eigentliche Arbeitsobjekt?
2. Welche Informationen können zu diesem Arbeitsobjekt gehören?
3. Welche Bestandteile der gezeigten Jira-Umgebung könnten bei einem anderen Unternehmen anders aussehen?

Notieren Sie Ihre Antworten kurz. Sie werden darauf später zurückkommen.

---

## 3. Lernphase 2 – Das Jira-Modell verstehen

**Zeitbedarf:** ca. 30 Minuten

Um sich auch in einer unbekannten Jira-Umgebung zurechtzufinden, müssen Sie einige Grundkonzepte unterscheiden können.

Vereinfacht:

```text
Projekt / Space
      |
      v
Vorgänge / Work Items
      |
      v
Vorgangstypen und Felder
```

Typische Vorgangstypen sind beispielsweise:

- Epic
- Story
- Task
- Bug
- Sub-Task

Welche Vorgangstypen tatsächlich vorhanden sind, hängt von der jeweiligen Jira-Konfiguration ab.

### Unterschiedliche Begriffswelten

Atlassian verwendet inzwischen teilweise neue Begriffe. In Kundeninstallationen und älteren Dokumentationen können Ihnen deshalb unterschiedliche Bezeichnungen begegnen:

| Neuerer Atlassian-Begriff | Traditioneller Begriff |
|---|---|
| Space | Project / Projekt |
| Work Item | Issue / Vorgang |
| Work Type | Issue Type / Vorgangstyp |

Für das Verständnis ist weniger der konkrete Begriff wichtig als das dahinterliegende Konzept.

### Online-Ressource

**Atlassian – Überblick über Jira-Vorgänge**  
https://www.atlassian.com/de/software/jira/guides/issues/overview

### 3.1 Erste Analyse des Umzugsprojekts

Betrachten Sie folgende Arbeiten:

- Firmenumzug durchführen
- Neue Büroräume vorbereiten
- Raumplan erstellen
- Möbel bestellen
- IT-Infrastruktur bereitstellen
- Netzwerkverkabelung durchführen
- WLAN installieren
- Defekten WLAN Access Point austauschen

Überlegen Sie:

1. Welche Einträge könnten Jira-Vorgänge sein?
2. Welche Einträge könnten übergeordnete Arbeitspakete darstellen?
3. Welche unterschiedlichen Vorgangstypen könnten sinnvoll sein?
4. Welche Informationen würden Sie nicht als eigenen Vorgang abbilden?

### Wichtig

Es gibt hier **nicht zwingend eine einzige richtige Modellierung**.

Beispielsweise könnte **IT-Infrastruktur bereitstellen** ein Epic sein und **Netzwerkverkabelung durchführen** ein Task. In einer anderen Jira-Konfiguration könnte dieselbe Arbeit anders strukturiert sein.

> **Die konkrete Jira-Konfiguration ist nicht Jira selbst.**

Sie müssen die zugrunde liegenden Konzepte verstehen, um mit unterschiedlichen Kundenumgebungen arbeiten zu können.

---

## 4. Lernphase 3 – Vorgänge anlegen und bearbeiten

**Zeitbedarf:** ca. 45 Minuten

Nun wechseln Sie in die bereitgestellte Jira-Trainingsumgebung.

### Begleitendes Tutorial

**Atlassian – Tutorial zu Jira-Vorgängen**  
https://www.atlassian.com/de/software/jira/guides/issues/tutorials

### 4.1 Aufgabe: Einen Vorgang erstellen

Im Umzugsprojekt ergibt sich folgende Aufgabe:

> Für das neue Bürogebäude muss ein Raumplan erstellt werden. Der Raumplan legt fest, welche Abteilungen und Teams welche Bereiche des Gebäudes beziehen. Die Aufgabe besitzt eine hohe Priorität und soll bis zum 15. des kommenden Monats abgeschlossen sein.

Erstellen Sie dafür einen Jira-Vorgang.

Hinterlegen Sie mindestens:

- einen geeigneten Vorgangstyp,
- einen aussagekräftigen Titel,
- eine Beschreibung,
- einen Bearbeiter,
- eine Priorität,
- ein Fälligkeitsdatum.

### Qualitätscheck

Wäre beispielsweise **„Raumplan“** ein guter Titel?

Vergleichen Sie ihn mit:

> **Raumplan für den neuen Unternehmensstandort erstellen**

Fragen Sie sich:

> Könnte eine andere Person anhand des Vorgangs verstehen, **was zu tun ist und welches Ergebnis erwartet wird?**

### 4.2 Aufgabe: Zusammenarbeit

Während der Bearbeitung gibt es eine neue Information:

> Die Geschäftsleitung hat entschieden, dass Vertrieb und Kundenservice im gleichen Gebäudeteil untergebracht werden sollen.

1. Ergänzen Sie diese Information als Kommentar.
2. Erstellen Sie eine einfache Beispieldatei `raumplan-entwurf.pdf` oder verwenden Sie eine vorhandene Datei und hängen Sie sie an den Vorgang an.
3. Ändern Sie anschließend eine Information des Vorgangs, beispielsweise die Priorität oder das Fälligkeitsdatum.
4. Suchen Sie diese Änderung anschließend in der Vorgangsaktivität bzw. Historie.

### Reflexion

> Welche Vorteile bietet es für ein Projekt, wenn Aufgaben, Kommentare, Anhänge und Änderungen gemeinsam nachvollziehbar sind?

---

## 5. Lernphase 4 – Status und Workflow

**Zeitbedarf:** ca. 30 Minuten

Projektaufgaben verändern während ihrer Bearbeitung ihren Zustand.

Ein einfacher Prozess könnte beispielsweise lauten:

```text
Offen → In Bearbeitung → Review → Erledigt
```

Dafür müssen drei Begriffe unterschieden werden.

### Status

Der Status beantwortet:

> **Wo befindet sich der Vorgang momentan?**

### Transition / Übergang

Eine Transition beantwortet:

> **Wie gelangt der Vorgang von einem Status in einen anderen?**

### Workflow

Der Workflow beschreibt den möglichen Lebenszyklus eines Vorgangs aus Status und Übergängen.

### Online-Ressource

**Atlassian – Einführung in Jira-Workflows**  
https://www.atlassian.com/de/software/jira/guides/workflows/overview

### 5.1 Praxisaufgabe

Öffnen Sie den Vorgang **„Raumplan für den neuen Unternehmensstandort erstellen“**.

1. Ermitteln Sie seinen aktuellen Status.
2. Starten Sie die Bearbeitung.
3. Überführen Sie ihn anschließend in den nächsten vorgesehenen Status.
4. Bringen Sie ihn schließlich in den Abschlussstatus.

Beobachten Sie dabei:

- Welche Status gibt es?
- Welche Übergänge stehen zur Verfügung?
- Können Sie jeden beliebigen Status auswählen?
- Welche Informationen ändern sich beim Statuswechsel?

### 5.2 Problemsituation

Während des Umzugsprojekts tritt folgende Situation auf:

> Die Raumplanung kann momentan nicht fortgesetzt werden. Die Geschäftsleitung muss zunächst entscheiden, ob eine zusätzliche Bürofläche angemietet wird.

Sie hätten gerne den Status **„Wartet auf Entscheidung“**. Dieser Status existiert jedoch nicht.

Als Projektanwender arbeiten Sie grundsätzlich innerhalb der vorhandenen Jira-Konfiguration. Wenn ein fachlich benötigter Status fehlt, kann dies ein sinnvoller Änderungswunsch sein. Die administrative Änderung des Workflows gehört jedoch **nicht zu Ihrer Aufgabe in diesem Training**.

Der Bedarf würde mit dem zuständigen Jira-Verantwortlichen abgestimmt.

---

## 6. Lernphase 5 – Board und Workflow unterscheiden

**Zeitbedarf:** ca. 25 Minuten

Ein häufiger Irrtum bei der Arbeit mit Jira lautet:

> **Das Board ist der Workflow.**

Das stimmt nicht.

Ein **Workflow** definiert Status und mögliche Übergänge eines Vorgangs.

Ein **Board** stellt ausgewählte Vorgänge visuell dar.

### Online-Ressourcen und Tutorials

**Atlassian – Einführung in Jira-Boards**  
https://www.atlassian.com/de/software/jira/guides/boards/overview

**Atlassian – Tutorials zu Jira-Boards**  
https://www.atlassian.com/software/jira/guides/boards/tutorials

### 6.1 Erkundungsauftrag

Öffnen Sie das Board des Umzugsprojekts.

Untersuchen Sie:

1. Welche Spalten besitzt das Board?
2. Welche Vorgänge werden angezeigt?
3. Welchen Status besitzen diese Vorgänge?
4. Wie hängen Status und Spalten zusammen?
5. Was passiert, wenn Sie einen Vorgang in eine andere Spalte verschieben?

Bewegen Sie – soweit es der vorhandene Workflow erlaubt – den Vorgang **„Raumplan für den neuen Unternehmensstandort erstellen“** auf dem Board.

Kontrollieren Sie anschließend den Status des Vorgangs.

### Verständnisfrage

Wo befindet sich der Vorgang eigentlich – **im Board**?

Nein.

> Das Board ist eine **Sicht auf Vorgänge**. Der Vorgang ist das eigentliche Arbeitsobjekt.

Diese Unterscheidung wird spätestens bei Filtern, JQL, Dashboards und unterschiedlichen Boards wieder wichtig.

---

## 7. Lernphase 6 – Beziehungen und Abhängigkeiten

**Zeitbedarf:** ca. 15 Minuten

Bei einem Firmenumzug sind viele Arbeiten voneinander abhängig.

Beispielsweise:

```text
Raumplanung freigeben
        |
        v
Möbel bestellen
        |
        v
Arbeitsplätze einrichten
```

Oder:

```text
Netzwerkverkabelung abschließen
        |
        v
WLAN Access Points installieren
        |
        v
WLAN-Abdeckung testen
```

Solche Zusammenhänge können in Jira über Beziehungen zwischen Vorgängen dargestellt werden.

### 7.1 Praxisaufgabe

Erstellen Sie drei Vorgänge:

1. Netzwerkverkabelung abschließen
2. WLAN Access Points installieren
3. WLAN-Abdeckung testen

Stellen Sie anschließend geeignete Beziehungen zwischen den Vorgängen her.

Drücken Sie insbesondere aus:

- Die WLAN Access Points können erst installiert werden, nachdem die Netzwerkverkabelung abgeschlossen ist.
- Die WLAN-Abdeckung kann erst getestet werden, nachdem die Access Points installiert wurden.

### Reflexionsfrage

Vergleichen Sie:

```text
Epic → Task → Sub-Task
```

mit:

```text
Vorgang A blockiert Vorgang B
```

Was ist der Unterschied?

Die erste Beziehung beschreibt eine **Struktur bzw. Hierarchie von Arbeit**.

Die zweite beschreibt eine **fachliche bzw. zeitliche Abhängigkeit zwischen Arbeiten**.

Diese Unterscheidung benötigen Sie in Block 2 bei der Projektplanung.

---

## 8. Abschlussquiz

**Zeitbedarf:** ca. 15 Minuten

Beantworten Sie die folgenden Fragen zunächst ohne Nachschlagen.

### Frage 1

Der Vorgang „Raumplan erstellen“ befindet sich aktuell auf „In Bearbeitung“. Welches Jira-Konzept beschreibt „In Bearbeitung“?

- A: Status
- B: Vorgangstyp
- C: Priorität
- D: Assignee

### Frage 2

Welche Aussage beschreibt einen Jira-Workflow am treffendsten?

- A: Eine grafische Übersicht aller Projektaufgaben
- B: Der Lebenszyklus eines Vorgangs aus Status und Übergängen
- C: Eine Liste der Projektmitarbeitenden
- D: Eine Hierarchie aus über- und untergeordneten Arbeiten

### Frage 3

Welche Aussage beschreibt das Verhältnis von Jira-Board und Vorgang am besten?

- A: Das Board ist eine Sicht auf ausgewählte Vorgänge.
- B: Ein Vorgang existiert nur, solange er auf einem Board angezeigt wird.
- C: Jeder Vorgang besitzt sein eigenes Board.
- D: Board und Workflow sind zwei Namen für dasselbe Konzept.

### Frage 4

Für das Umzugsprojekt wäre der zusätzliche Status „Wartet auf Entscheidung“ hilfreich. Er existiert nicht. Was entspricht Ihrer Rolle in diesem Training?

- A: Den Workflow selbst erweitern.
- B: Den vorhandenen Workflow nutzen und den Änderungsbedarf mit der Jira-Verantwortung abstimmen.
- C: Einen neuen Vorgangstyp als Ersatzstatus anlegen.
- D: Die Aufgabe außerhalb von Jira weiterführen.

### Frage 5

„WLAN Access Points installieren“ kann erst beginnen, nachdem „Netzwerkverkabelung abschließen“ erledigt wurde. Welches Konzept bildet diesen Zusammenhang am direktesten ab?

- A: Blockierungsbeziehung
- B: Gleiche Priorität
- C: Gleicher Assignee
- D: Gleiches Fälligkeitsdatum

### Frage 6

Welches Jira-Konzept klassifiziert, um welche Art von Arbeit es sich bei einem Vorgang handelt?

- A: Vorgangstyp
- B: Status
- C: Priorität
- D: Transition

### Frage 7

Was geschieht typischerweise, wenn eine Karte auf einem Jira-Board in eine andere Workflow-Spalte verschoben wird?

- A: Der zugrunde liegende Vorgang durchläuft einen passenden Workflow-Übergang.
- B: Jira erzeugt automatisch einen neuen Vorgang.
- C: Der Vorgangstyp ändert sich automatisch.
- D: Alle Verknüpfungen werden entfernt.

### Frage 8

Welche Information zeigt am direktesten, wer einen Vorgang aktuell bearbeiten soll?

- A: Assignee
- B: Reporter
- C: Status
- D: Priorität

### Frage 9

Warum können sich Vorgangstypen zwischen verschiedenen Kundeninstallationen unterscheiden?

- A: Vorgangstypen können Teil der jeweiligen Jira-Konfiguration sein.
- B: Jira wählt sie bei jedem Login zufällig aus.
- C: Jeder Benutzer besitzt ausschließlich persönliche Vorgangstypen.
- D: Der aktuelle Status bestimmt die verfügbaren Vorgangstypen.

### Frage 10

Was hilft am meisten, wenn Sie erstmals mit der unbekannten Jira-Umgebung eines neuen Kunden arbeiten?

- A: Die Jira-Grundkonzepte verstehen und anschließend die konkrete Kundenkonfiguration analysieren.
- B: Die Menüpositionen der Trainingsumgebung auswendig lernen.
- C: Davon ausgehen, dass alle Kunden dieselben Workflows verwenden.
- D: Zunächst alle abweichenden Einstellungen ändern.

### Lösungen

| Frage | Lösung |
|---|---|
| 1 | A |
| 2 | B |
| 3 | A |
| 4 | B |
| 5 | A |
| 6 | A |
| 7 | A |
| 8 | A |
| 9 | A |
| 10 | A |

> Prüfen Sie bei falschen Antworten nicht nur die richtige Lösung, sondern erklären Sie sich selbst, **warum die anderen Antworten nicht passen**.

---

## 9. Abschlusskontrolle

Bevor Sie das Modul beenden, sollten Sie folgende Begriffe **ohne Nachschlagen** erklären können:

- Projekt / Space
- Vorgang / Work Item
- Vorgangstyp
- Status
- Transition
- Workflow
- Board
- Assignee
- Hierarchie
- Vorgangsverknüpfung

Versuchen Sie außerdem, folgende Aussagen mit eigenen Worten zu erklären:

> **Ein Board ist eine Sicht auf Vorgänge.**

> **Ein Workflow beschreibt den möglichen Lebenszyklus eines Vorgangs.**

> **Hierarchie und Abhängigkeit sind unterschiedliche Beziehungen zwischen Arbeiten.**

> **Die konkrete Jira-Konfiguration eines Kunden kann anders aussehen, obwohl die grundlegenden Jira-Konzepte dieselben bleiben.**

---

## 10. Vorbereitung auf die Coaching-Session

Bringen Sie zur anschließenden 60-minütigen gemeinsamen Session mit:

- mindestens **eine Frage**, die bei der Bearbeitung entstanden ist,
- einen selbst erstellten Vorgang,
- ein Beispiel für eine Abhängigkeit zwischen zwei Vorgängen,
- eine Beobachtung zum vorhandenen Workflow,
- eine Sache, die Sie in der Jira-Trainingsumgebung anders erwartet hätten.

Bereiten Sie außerdem eine kurze Antwort auf folgende Frage vor:

> **Sie kommen als Projektberater zu einem neuen Kunden und erhalten erstmals Zugang zu dessen Jira-Projekt. Welche Dinge würden Sie sich zuerst ansehen, um zu verstehen, wie dieser Kunde Jira für sein Projekt verwendet?**

Diese Frage wird zu Beginn der Coaching-Session gemeinsam diskutiert.

---

## 11. Zeitplan

| Lernphase | Zeit |
|---|---:|
| 1. Jira kennenlernen | 20 min |
| 2. Jira-Modell verstehen | 30 min |
| 3. Vorgänge anlegen und bearbeiten | 45 min |
| 4. Status und Workflow | 30 min |
| 5. Board und Workflow | 25 min |
| 6. Beziehungen und Abhängigkeiten | 15 min |
| 7. Quiz und Abschlusskontrolle | 15 min |
| **Gesamt** | **180 min** |

---

## Weiterführende Ressourcen

- Atlassian Learning – Get started with Jira  
  https://learning.atlassian.com/learning/path/get-the-most-out-of-jira/course/get-started-with-jira
- Jira – Getting Started / Basics  
  https://www.atlassian.com/de/software/jira/guides/getting-started/basics
- Jira – Vorgänge / Work Items  
  https://www.atlassian.com/de/software/jira/guides/issues/overview
- Jira – Vorgangs-Tutorials  
  https://www.atlassian.com/de/software/jira/guides/issues/tutorials
- Jira – Workflows  
  https://www.atlassian.com/de/software/jira/guides/workflows/overview
- Jira – Boards  
  https://www.atlassian.com/de/software/jira/guides/boards/overview
- Jira – Board-Tutorials  
  https://www.atlassian.com/software/jira/guides/boards/tutorials
