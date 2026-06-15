# Einfaches Template für Spec-Driven Development

Dieses Repository ist eine einfache, werkzeugunabhängige Vorlage für
Softwareprojekte, die mit Unterstützung eines KI-Coding-Agenten entwickelt
werden.

Der Ablauf basiert auf drei Dokumenten pro Feature:

1. `spezifikation.md` beschreibt, **was** und **warum** gebaut wird.
2. `plan.md` beschreibt, **wie** das Feature umgesetzt werden soll.
3. `aufgaben.md` zerlegt den Plan in kleine, überprüfbare Arbeitsschritte.

Die Vorlage ergänzt diesen Kern um wenige wichtige Leitplanken: offene Fragen,
nichtfunktionale Anforderungen, Sicherheitsbetrachtung, Tests, Nachverfolgbarkeit
und menschliche Freigaben.

## Schnellstart

1. Fülle [docs/vision.md](docs/vision.md) aus.
2. Passe [docs/prinzipien.md](docs/prinzipien.md) an dein Projekt an.
3. Kopiere `specs/_vorlage` nach `specs/001-mein-feature`.
4. Erstelle und prüfe zuerst `spezifikation.md`.
5. Erstelle danach `plan.md`.
6. Leite daraus `aufgaben.md` ab.
7. Setze die Aufgaben in kleinen Abschnitten um und prüfe jeden Abschnitt.

Jeder Schritt wird separat beauftragt. Der Agent stellt zuerst Rückfragen und
stoppt nach jedem Schritt, bis der nächste ausdrücklich angefordert wird.

Ein vollständig ausgefülltes, aber bewusst kleines Beispiel liegt unter
`specs/000-beispiel-feature`. Es kann nach dem Kennenlernen der Vorlage
gelöscht werden.

## Ordnerstruktur

```text
.
|-- AGENTS.md
|-- CLAUDE.md
|-- LICENSE
|-- README.md
|-- .agents/
|   `-- skills/
|       |-- feature-pruefen/
|       |-- feature-spezifizieren/
|       |-- feature-umsetzen/
|       `-- umsetzung-planen/
|-- docs/
|   |-- prinzipien.md
|   `-- vision.md
|-- specs/
|   |-- README.md
|   |-- _vorlage/
|   |   |-- aufgaben.md
|   |   |-- plan.md
|   |   `-- spezifikation.md
|   `-- 000-beispiel-feature/
|       |-- aufgaben.md
|       |-- plan.md
|       `-- spezifikation.md
```

## Arbeitsweise mit einem KI-Agenten

Das Template enthält unter `.agents/skills/` vier Skills, die Codex automatisch
erkennt. Andere Agenten können die jeweiligen `SKILL.md`-Dateien als kurze
Arbeitsanleitung verwenden.

- `feature-spezifizieren`: Idee klären und `spezifikation.md` erstellen
- `umsetzung-planen`: `plan.md` und danach `aufgaben.md` erstellen
- `feature-umsetzen`: freigegebene Aufgaben kontrolliert umsetzen
- `feature-pruefen`: Dokumente oder fertige Umsetzung unabhängig prüfen

Beispielaufrufe:

> Nutze `$feature-spezifizieren` für meine Idee einer Benutzeranmeldung.
> Stelle zunächst Rückfragen und ändere noch keine Dateien.
>
> Nutze `$umsetzung-planen` für `specs/001-benutzer-anmeldung`.
> Erstelle nur den Plan und stoppe danach.
>
> Der Plan ist freigegeben. Erstelle jetzt nur die Aufgabenliste und stoppe.
>
> Nutze `$feature-umsetzen` für Aufgabe T-01 in
> `specs/001-benutzer-anmeldung` und stoppe danach.
>
> Nutze `$feature-pruefen`, um die Umsetzung von
> `specs/001-benutzer-anmeldung` abzunehmen.

Die verbindlichen Regeln für Agenten stehen ausschließlich in `AGENTS.md`.
Projektweite Qualitätsmaßstäbe werden in `docs/prinzipien.md` gepflegt.

### Claude Code

`CLAUDE.md` importiert die gemeinsamen Regeln aus `AGENTS.md`. Bitte Claude
Code bei der ersten Nutzung ausdrücklich:

> Richte dieses Projekt für Claude Code ein. Befolge dazu den Abschnitt
> "Werkzeugkompatibilität" in `AGENTS.md`.

Claude legt daraufhin seine Skill-Kopien unter `.claude/skills/` an. Die
kanonischen Skills unter `.agents/skills/` bleiben maßgeblich. In Claude Code
werden sie beispielsweise mit `/feature-spezifizieren` aufgerufen.

## Als GitHub-Template verwenden

Veröffentliche dieses Repository auf GitHub und aktiviere in den
Repository-Einstellungen die Option **Template repository**. Andere
Entwickler können danach über **Use this template** ein eigenes Repository
mit einer unabhängigen Historie erstellen.

## Lizenz

Dieses Template steht unter der [MIT-Lizenz](LICENSE).
