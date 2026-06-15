---
name: feature-pruefen
description: Prüft ein Feature unabhängig auf Klarheit, Konsistenz, Abdeckung und korrekte Umsetzung. Verwenden, wenn Spezifikation, Plan und Aufgaben vor der Implementierung analysiert oder eine fertige Umsetzung gegen Anforderungen, Akzeptanzkriterien und Tests abgenommen werden soll.
---

# Feature prüfen

## Prüfumfang bestimmen

Lies `AGENTS.md`, die Projektdokumente und alle Dateien des Feature-Ordners.
Prüfe je nach Entwicklungsstand nur die vorhandenen Artefakte:

- **Vor Umsetzung:** Spezifikation, Plan und Aufgabenliste.
- **Nach Umsetzung:** zusätzlich Codeänderungen, Tests und Dokumentation.

Ändere bei einer Prüfung keine Dateien, außer der Benutzer fordert Korrekturen
ausdrücklich an.

## Artefakte prüfen

1. Suche unklare, widersprüchliche oder nicht überprüfbare Anforderungen.
2. Prüfe Normal-, Fehler- und Randfälle sowie relevante nichtfunktionale
   Anforderungen.
3. Prüfe die Verknüpfung `Anforderung → Planschritt → Aufgabe → Prüfung`.
4. Suche unbegründete technische Entscheidungen, fehlende Risiken,
   Abhängigkeiten und Rücknahmemöglichkeiten.
5. Prüfe, ob Aufgaben klein, geordnet und einzeln überprüfbar sind.

## Umsetzung prüfen

1. Vergleiche das beobachtbare Verhalten mit jedem Akzeptanzkriterium.
2. Prüfe, ob die Implementierung den freigegebenen Umfang überschreitet.
3. Untersuche Fehlerbehandlung, Sicherheit, Datenschutz und
   Rückwärtskompatibilität entsprechend dem Plan.
4. Führe die vorgesehenen Tests aus und bewerte relevante Testlücken.
5. Prüfe, ob Aufgabenstatus und Dokumentation dem tatsächlichen Stand
   entsprechen.

## Bericht

Führe Befunde zuerst auf, nach Schweregrad geordnet. Nenne jeweils die
betroffene Datei und konkrete Stelle sowie die Auswirkung. Schließe mit:

- offenen Fragen oder Annahmen,
- ausgeführten und nicht ausführbaren Prüfungen,
- einer klaren Aussage: `freigabefähig` oder `nicht freigabefähig`.
