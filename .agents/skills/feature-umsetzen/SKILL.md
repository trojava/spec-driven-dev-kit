---
name: feature-umsetzen
description: Setzt Aufgaben eines geplanten Features in kleinen, überprüften Schritten um. Verwenden, wenn eine bestimmte oder die nächste offene Aufgabe aus aufgaben.md implementiert, getestet, dokumentiert und nach erfolgreicher Prüfung abgeschlossen werden soll.
---

# Feature umsetzen

## Voraussetzungen

1. Lies `AGENTS.md`, die Projektdokumente und alle Dateien des Feature-Ordners.
2. Prüfe, dass Spezifikation und Plan freigegeben sind.
3. Beginne nur, wenn der Benutzer die Umsetzung ausdrücklich beauftragt hat.
4. Bearbeite die ausdrücklich genannte Aufgabe. Falls keine Aufgabe genannt
   ist, frage nach und ändere keinen Code.

## Aufgabe bearbeiten

1. Prüfe Bezug, Ergebnis und vorgesehene Prüfung der Aufgabe.
2. Untersuche den betroffenen Code und bestehende Tests.
3. Implementiere nur den erforderlichen Umfang.
4. Ergänze oder aktualisiere Tests und notwendige Dokumentation.
5. Führe zuerst die aufgabenspezifische Prüfung und danach angemessene
   Regressionstests aus.
6. Markiere die Aufgabe nur bei erfolgreicher Prüfung mit `[x]`.
7. Stoppe nach dieser Aufgabe. Bearbeite keine weitere Aufgabe ohne
   ausdrückliche Aufforderung.

## Bei Abweichungen

- Stoppe bei widersprüchlichen oder nicht erfüllbaren Vorgaben.
- Behandle fachliche Anpassungswünsche an ein bereits umgesetztes Feature
  zuerst mit `$feature-spezifizieren` und anschließend mit
  `$umsetzung-planen`. Ändere bis zu deren Freigabe keinen Code.
- Dokumentiere neu entdeckte Arbeit als zusätzliche Aufgabe.
- Verlange eine Aktualisierung und erneute Freigabe, wenn sich eine Anforderung
  oder ein wesentlicher Planschritt ändern muss.
- Lasse die Aufgabe offen, wenn eine Prüfung fehlschlägt oder nicht ausgeführt
  werden konnte.

## Abschluss

Berichte:

- bearbeitete Aufgabe und Änderungen,
- ausgeführte Prüfungen mit Ergebnis,
- verbleibende Risiken, Einschränkungen oder Folgeaufgaben.
