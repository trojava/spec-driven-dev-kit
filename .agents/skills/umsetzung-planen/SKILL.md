---
name: umsetzung-planen
description: Erstellt auf ausdrückliche Aufforderung entweder den technischen Umsetzungsplan oder die Aufgabenliste für eine freigegebene Feature-Spezifikation. Verwenden, wenn plan.md oder aufgaben.md eines Feature-Ordners separat erstellt, ergänzt oder auf vollständige Anforderungsabdeckung gebracht werden sollen.
---

# Umsetzung planen

## Voraussetzungen

- Lies `AGENTS.md`, die Projektdokumente und alle Dateien des Feature-Ordners.
- Kläre, ob der Benutzer ausdrücklich den Plan oder die Aufgabenliste
  beauftragt hat. Führe nie beide Schritte in einem Auftrag aus.
- Beginne nur, wenn `spezifikation.md` den Status `Freigegeben` hat und keine
  blockierenden Fragen enthält.

## Plan erstellen

1. Untersuche den bestehenden Code und die betroffenen Schnittstellen.
2. Fülle `plan.md` anhand der Vorlage aus.
3. Begründe technische Entscheidungen und nenne relevante Alternativen.
4. Plane Tests, Sicherheit, Datenschutz, Datenänderungen, Betrieb und
   Rücknahme entsprechend ihrer Relevanz.
5. Ordne jede Anforderung mindestens einem Planschritt und einer Prüfung zu.
6. Weise auf Entscheidungen hin, die menschliche Bestätigung benötigen.
7. Setze den Plan erst nach ausdrücklicher Bestätigung auf `Freigegeben`.

Ändere in diesem Abschnitt keinen Quellcode und keine Aufgabenliste. Stoppe
nach Erstellung oder Überarbeitung des Plans und warte auf einen separaten
Auftrag.

## Aufgaben erstellen

Beginne damit erst, wenn `plan.md` freigegeben ist:

1. Zerlege die Planschritte in überschaubare, geordnete und einzeln prüfbare
   Aufgaben. Fasse zusammengehörige Änderungen zusammen, solange sie ein
   gemeinsames Ergebnis und eine gemeinsame Prüfung besitzen.
2. Gib für jede Aufgabe Bezug, erwartetes Ergebnis und konkrete Prüfung an.
3. Ergänze notwendige Dokumentations- und Abschlussaufgaben.
4. Prüfe, dass alle Planschritte und Anforderungen abgedeckt sind.

Erstelle keine eigenen Aufgaben für offensichtliche Zwischenschritte,
Dateioperationen oder einzelne Tests, wenn diese sinnvoll zur Umsetzung einer
anderen Aufgabe gehören.

Stoppe nach Erstellung oder Überarbeitung der Aufgabenliste. Beginne keine
Umsetzung.

## Grenzen

- Ändere keine freigegebene Spezifikation ohne ausdrücklichen Auftrag.
- Ändere keinen Quellcode.
- Markiere keine Umsetzungsaufgabe als erledigt.
- Setze den Ablauf nicht selbstständig mit der nächsten Phase fort.

## Ergebnis

- Nenne erstellte oder geänderte Planungsdateien.
- Liste offene Entscheidungen, Risiken und Abdeckungslücken auf.
- Gib den Freigabestatus von Plan und Aufgabenliste an.
