---
name: feature-spezifizieren
description: Erstellt oder überarbeitet eine Feature-Spezifikation unter specs/ auf Grundlage einer Idee oder fachlichen Anforderung. Verwenden, wenn ein neues Feature geklärt, Anforderungen und Akzeptanzkriterien formuliert, offene Fragen gesammelt oder eine bestehende spezifikation.md bis zur Freigabereife verbessert werden soll.
---

# Feature spezifizieren

## Ablauf

1. Lies `AGENTS.md`, `docs/vision.md`, `docs/prinzipien.md` und
   `specs/_vorlage/spezifikation.md`.
2. Ermittle den Feature-Ordner. Falls er noch nicht existiert, lege ihn nach
   dem Muster `specs/NNN-kurzer-name/` an und kopiere die drei Vorlagendateien
   hinein.
3. Erfasse Ziel, Nutzen, Umfang, Beteiligte und ausdrücklich ausgeschlossene
   Punkte.
4. Formuliere funktionale Anforderungen als User Stories mit eindeutigen,
   beobachtbaren Akzeptanzkriterien. Berücksichtige Normal-, Fehler- und
   relevante Randfälle.
5. Prüfe die Kategorien der nichtfunktionalen Anforderungen. Begründe kurz,
   wenn eine Kategorie nicht relevant ist.
6. Dokumentiere Annahmen, offene Fragen und Risiken in der Spezifikation.
   Stelle notwendige Rückfragen und gib jeweils einen konkreten Vorschlag mit.
7. Prüfe die Freigabekriterien am Dateiende. Setze den Status erst nach
   ausdrücklicher menschlicher Bestätigung auf `Freigegeben`.

## Grenzen

- Ändere nur `spezifikation.md` sowie bei einem neuen Feature die aus der
  Vorlage kopierten Dateien.
- Erstelle keinen technischen Plan und ändere keinen Quellcode.
- Ersetze fehlende Informationen nicht durch erfundene Details.

## Ergebnis

- Nenne den bearbeiteten Feature-Ordner.
- Liste blockierende Fragen und verbleibende Risiken auf.
- Gib an, ob die Spezifikation noch ein Entwurf oder freigegeben ist.
