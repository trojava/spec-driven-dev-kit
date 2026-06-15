# Feature-Spezifikationen

Für jedes Feature gibt es einen eigenen Ordner:

```text
specs/
`-- 001-kurzer-feature-name/
    |-- spezifikation.md
    |-- plan.md
    `-- aufgaben.md
```

## Neues Feature anlegen

1. Kopiere den Ordner `_vorlage`.
2. Benenne die Kopie mit einer fortlaufenden Nummer und einem kurzen Namen,
   zum Beispiel `001-benutzer-anmeldung`.
3. Fülle zuerst `spezifikation.md` aus.
4. Kläre alle blockierenden Fragen und lasse die Spezifikation freigeben.
5. Erstelle und genehmige danach `plan.md`.
6. Erstelle anschließend `aufgaben.md`.
7. Setze die Aufgaben einzeln oder in kleinen Gruppen um.

Beauftrage jeden Schritt ausdrücklich und separat. Ein Agent darf nicht
selbstständig von Spezifikation zu Plan, Aufgaben oder Umsetzung wechseln.

Die Nummern erleichtern Gespräche und Verweise. Sie müssen nicht lückenlos
sein.

Der Ordner `000-beispiel-feature` zeigt ein ausgefülltes Beispiel und kann
gelöscht werden.
