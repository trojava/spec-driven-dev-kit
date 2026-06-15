# Gemeinsame Regeln für Coding-Agenten

Diese Regeln gelten unabhängig vom verwendeten Skill. Die konkreten Abläufe
stehen unter `.agents/skills/`.

## Werkzeugkompatibilität

Die kanonischen Skills liegen unter `.agents/skills/`.

- Codex erkennt die Skills dort automatisch.
- Claude Code liest diese Datei über `CLAUDE.md`, erkennt Skills jedoch unter
  `.claude/skills/`.
- Wenn du Claude Code bist und der Benutzer dich ausdrücklich mit der
  Ersteinrichtung beauftragt, übernimm die kanonischen Skills nach
  `.claude/skills/`.
- Behalte Namen und Inhalte der `SKILL.md`-Dateien bei. Codex-spezifische
  Dateien unter `agents/` müssen nicht übernommen werden.
- Führe keine Migration ungefragt oder wiederholt aus.
- Behandle `.agents/skills/` weiterhin als maßgebliche Quelle.

## Verbindliche Quellen

Lies vor der Arbeit:

1. `docs/vision.md`
2. `docs/prinzipien.md`
3. die bereits vorhandenen Dateien des betroffenen Features unter `specs/`

Bei Widersprüchen gilt folgende Reihenfolge:

1. ausdrücklich bestätigte Anweisung des Menschen
2. `docs/prinzipien.md`
3. `spezifikation.md`
4. `plan.md`
5. `aufgaben.md`

Melde Widersprüche, bevor du weiterarbeitest.

## Projektweite Regeln

- Triff keine fachlichen oder technischen Annahmen stillschweigend.
- Arbeite nur am ausdrücklich genannten Feature und Auftrag.
- Halte Änderungen klein und nachvollziehbar.
- Halte Dokumente fokussiert: Hebe wichtige Ziele, Entscheidungen, Risiken und
  Prüfergebnisse hervor. Vermeide Wiederholungen und Details ohne erkennbaren
  Nutzen für Umsetzung oder Review.
- Ändere freigegebene Anforderungen nicht stillschweigend.
- Ändere bei fachlichen Anpassungswünschen nach einer Umsetzung nicht direkt
  den Code. Aktualisiere und genehmige zuerst die Spezifikation, danach den
  Plan und die Aufgabenliste. Setze die Änderung erst auf dieser Grundlage um.
- Füge niemals Zugangsdaten, Schlüssel oder andere Geheimnisse zum Repository
  hinzu.
- Beachte die in `docs/prinzipien.md` festgelegten Qualitätsmaßstäbe.
- Weise auf Widersprüche, Risiken und fehlende Informationen hin.
