---
name: feature-spezifizieren
description: Erstellt oder überarbeitet eine Feature-Spezifikation unter specs/ auf Grundlage einer Idee oder fachlichen Anforderung. Verwenden, wenn ein neues Feature geklärt, Anforderungen und Akzeptanzkriterien formuliert, offene Fragen gesammelt oder eine bestehende spezifikation.md bis zur Freigabereife verbessert werden soll.
---

# Feature spezifizieren

## Klärung

1. Prüfe, welches einzelne Feature spezifiziert werden soll.
2. Stelle zuerst gezielte Rückfragen zu Ziel, Umfang, Verhalten und relevanten
   Qualitätsanforderungen. Gib jeweils einen konkreten Vorschlag mit.
3. Warte auf die Antworten. Erstelle oder ändere in diesem Schritt noch keine
   Feature-Dateien.

## Ablauf

1. Lies `AGENTS.md`, `docs/vision.md`, `docs/prinzipien.md` und
   `specs/_vorlage/spezifikation.md`.
2. Ermittle den Feature-Ordner. Falls er noch nicht existiert, lege ihn nach
   dem Muster `specs/NNN-kurzer-name/` an und kopiere die drei Vorlagendateien
   hinein.
3. Erfasse Ziel, Nutzen, Umfang, Beteiligte und ausdrücklich ausgeschlossene
   Punkte.
4. Formuliere funktionale Anforderungen als User Stories mit eindeutigen,
   beobachtbaren Akzeptanzkriterien. Fasse zusammengehöriges Verhalten in
   einer Anforderung zusammen. Berücksichtige Normal-, Fehler- und Randfälle
   nur, wenn sie fachlich relevant sind.
5. Prüfe die Kategorien der nichtfunktionalen Anforderungen. Begründe kurz,
   wenn eine Kategorie nicht relevant ist.
6. Dokumentiere Annahmen, offene Fragen und Risiken in der Spezifikation.
   Stelle notwendige Rückfragen und gib jeweils einen konkreten Vorschlag mit.
7. Prüfe die Freigabekriterien am Dateiende. Setze den Status erst nach
   ausdrücklicher menschlicher Bestätigung auf `Freigegeben`.
8. Stoppe nach der Spezifikation. Erstelle weder Plan noch Aufgaben und beginne
   keine Umsetzung.

## Grenzen

- Ändere nur `spezifikation.md` sowie bei einem neuen Feature die aus der
  Vorlage kopierten Dateien.
- Erstelle keinen technischen Plan und ändere keinen Quellcode.
- Ersetze fehlende Informationen nicht durch erfundene Details.
- Wiederhole keine Information in mehreren Abschnitten, wenn ein Verweis
  genügt.
- Spezifiziere nicht automatisch weitere erkannte Features.

## Ergebnis

- Nenne den bearbeiteten Feature-Ordner.
- Liste blockierende Fragen und verbleibende Risiken auf.
- Gib an, ob die Spezifikation noch ein Entwurf oder freigegeben ist.
