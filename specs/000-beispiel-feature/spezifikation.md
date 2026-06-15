# Spezifikation: Begrüßungsseite

**Status:** Freigegeben

## Ziel

Neue Besucher sollen sofort erkennen, wie die Beispielanwendung heißt und
dass sie erfolgreich gestartet wurde.

## Nicht im Umfang

Navigation, Anmeldung, Mehrsprachigkeit und eine dauerhafte Datenspeicherung
gehören nicht zu diesem Beispiel.

## Beteiligte

- Besucher der Anwendung
- Entwickler, die die Anwendung lokal starten

## Annahmen

- A-01: Die Anwendung wird in einem modernen Webbrowser verwendet.

## Offene Fragen

Keine.

## Funktionale Anforderungen

### R-01: Anwendungstitel anzeigen

**User Story:** Als Besucher möchte ich den Namen der Anwendung sehen, damit
ich weiß, welche Anwendung geöffnet ist.

**Akzeptanzkriterien:**

- Wenn die Startseite geladen wurde, dann muss die Überschrift
  "Meine Anwendung" sichtbar sein.
- Wenn die Seite bei schmalem Bildschirm angezeigt wird, dann darf die
  Überschrift nicht horizontal abgeschnitten werden.

### R-02: Bereitschaft anzeigen

**User Story:** Als Entwickler möchte ich eine eindeutige Statusmeldung sehen,
damit ich erkenne, dass die Anwendung erfolgreich läuft.

**Akzeptanzkriterien:**

- Wenn die Startseite geladen wurde, dann muss der Text
  "Die Anwendung ist bereit." sichtbar sein.

## Nichtfunktionale Anforderungen

### Sicherheit und Datenschutz

- NFR-01: Die Seite darf keine Benutzerdaten erfassen oder übertragen.

### Barrierefreiheit und Bedienbarkeit

- NFR-02: Die Seite muss eine hierarchisch korrekte Hauptüberschrift besitzen
  und vollständig per Browser-Zoom nutzbar bleiben.

### Leistung und Zuverlässigkeit

- NFR-03: Für das statische Beispiel bestehen keine zusätzlichen
  Leistungsanforderungen.

### Betrieb und Beobachtbarkeit

- NFR-04: Die sichtbare Statusmeldung dient als manuelle Startprüfung.

## Risiken

| ID | Risiko | Auswirkung | Gegenmaßnahme |
| --- | --- | --- | --- |
| RIS-01 | Zu starkes Design lenkt vom Template ab. | Beispiel wird unnötig komplex. | Nur minimales HTML und CSS verwenden. |

## Freigabe

- [x] Ziel und Umfang sind verständlich.
- [x] Anforderungen sind eindeutig und überprüfbar.
- [x] Normalfälle, Fehlerfälle und relevante Randfälle sind beschrieben.
- [x] Nichtfunktionale Anforderungen wurden betrachtet.
- [x] Blockierende Fragen sind beantwortet.
- [x] Spezifikation wurde beispielhaft freigegeben.
