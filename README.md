# Vorteile der Nutzung von GitHub-Issue Templates zur Prüfungsvorbereitung

Dieses Projekt demonstriert, wie GitHub-Issue Templates gezielt zur Prüfungsvorbereitung in der Ausbildung zum Fachinformatiker bzw. zur Fachinformatikerin in der Anwendungsentwicklung eingesetzt werden können. Die standardisierte Struktur der Templates hilft dabei, Themen systematisch zu erfassen, Lernfortschritte zu dokumentieren und den Austausch in Lerngruppen zu fördern.

## Projektübersicht

- **Ziel:**  
  Verbesserung der Prüfungsvorbereitung durch strukturierte Erfassung und Bearbeitung von Prüfungsfragen, Übungsaufgaben und Lerninhalten.

- **Nutzen:**  
  - **Standardisierung:** Einheitliche Vorlagen sorgen für eine konsistente Bearbeitung aller Themen.
  - **Transparenz:** Offene und abgeschlossene Aufgaben werden zentral dokumentiert.
  - **Nachvollziehbarkeit:** Der Lernfortschritt wird durch die Dokumentation einzelner Schritte sichtbar.
  - **Kollaboration:** Einfacher Austausch und Feedback innerhalb von Lerngruppen.
  - **Integration:** Nahtlose Einbindung in den üblichen Entwicklungsworkflow auf GitHub.

## Funktionsweise

1. **Erstellung eines neuen Issues:**  
   Mithilfe vordefinierter Templates können gezielt neue Prüfungsfragen, Übungsaufgaben oder Themenvorschläge erstellt werden.

2. **Bearbeitung und Dokumentation:**  
   Jedes Issue dient als Arbeitsbereich, in dem Lösungsvorschläge, offene Fragen und Feedback dokumentiert werden können.

3. **Feedback und Revision:**  
   Diskussionen und Kommentare im Issue-Thread ermöglichen eine kontinuierliche Verbesserung der Lösungsansätze.

4. **Abschluss und Archivierung:**  
   Nach erfolgreicher Bearbeitung wird das Issue geschlossen – ein klarer Indikator für den erarbeiteten Lernfortschritt.

## Beispiel eines Issue-Templates

Ein typisches Template könnte wie folgt aussehen:

```yaml
name: "Prüfungsfrage"
about: "Ein Template zur Dokumentation und Bearbeitung von Prüfungsfragen und Übungsaufgaben"
title: "[Prüfungsfrage] Kurztitel der Frage"
labels: [Frage, Prüfungsvorbereitung]
assignees: []


**Thema:**  
(z.B. Objektorientierte Programmierung)

**Frage:**  
(Bitte die Prüfungsfrage hier einfügen.)

**Lösungsvorschlag:**  
- [ ] Erarbeitung des Lösungsvorschlags  
- [ ] Feedback einholen  
- [ ] Überarbeitung

**Referenzen:**  
(z.B. Lehrbuchkapitel, Online-Ressourcen)
```

---

## Installation und Nutzung

### 1. Repository klonen

Klone das Repository auf deinen lokalen Rechner:

```bash
git clone https://github.com/dein-benutzername/dein-repository.git
```

---

### 2. Repository-Verzeichnis betreten

```bash
cd dein-repository
```

---

### 3. Einrichtung der Templates

Stelle sicher, dass sich die Issue Templates im Ordner .github/ISSUE_TEMPLATE/ befinden. So stehen sie bei der Erstellung neuer Issues automatisch zur Auswahl.

---

### 4. Erstellen und Bearbeiten von Issues

Nutze die vordefinierten Templates, um neue Prüfungsfragen oder Übungsaufgaben anzulegen und dokumentiere deine Lernfortschritte.

---

## Contributing

Beiträge sind jederzeit willkommen! So kannst Du mitwirken:

1. Forke das Repository.
2. Erstelle einen neuen Branch:

```bash
git checkout -b feature/NeuePruefungsfrage
```

3. Nimm Deine Änderungen vor und committe sie:

```bash
git commit -m "Neue Prüfungsfrage hinzugefügt"
```

4.	Pushe Deinen Branch:

```bash
git push origin feature/NeuePruefungsfrage
```

5.	Öffne einen Pull Request, um deine Änderungen zur Diskussion einzureichen.

Lizenz: Dieses Projekt steht unter der MIT Lizenz.
