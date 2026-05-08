# User Stories

## 1. Tasks anzeigen

Als Benutzer möchte ich alle vorhandenen Tasks sehen, damit ich weiss, welche Aufgaben aktuell offen sind.

**Akzeptanzkriterien:**

- Beim Öffnen des Frontends werden die vorhandenen Tasks vom Backend geladen.
- Jeder Task wird in einer Liste angezeigt.
- Jeder Task wird mit seiner Beschreibung angezeigt.
- Die Tasks werden fortlaufend nummeriert angezeigt.

## 2. Neuen Task erfassen

Als Benutzer möchte ich einen neuen Task erfassen, damit ich eine neue Aufgabe in meine To-do-Liste aufnehmen kann.

**Akzeptanzkriterien:**

- Es gibt ein Eingabefeld für die Task-Beschreibung.
- Es gibt einen Button zum Absenden des neuen Tasks.
- Nach dem Absenden wird der Task an das Backend gesendet.
- Nach dem Speichern erscheint der neue Task in der Liste.

## 3. Doppelte Tasks verhindern

Als Benutzer möchte ich, dass eine Task-Beschreibung nur einmal vorkommt, damit die Liste keine doppelten Einträge enthält.

**Akzeptanzkriterien:**

- Wenn ein Task mit derselben Beschreibung bereits existiert, wird kein zweiter gleicher Task gespeichert.
- Die bestehende Task-Liste bleibt erhalten.
- Die Task-Beschreibung dient als eindeutiger Wert für einen Task.

## 4. Task als erledigt markieren

Als Benutzer möchte ich einen Task als erledigt markieren können, damit erledigte Aufgaben aus der Liste verschwinden.

**Akzeptanzkriterien:**

- Jeder angezeigte Task hat einen Done-Button mit Haken.
- Beim Klick auf den Done-Button wird der entsprechende Task an das Backend zum Löschen gesendet.
- Nach dem Löschen wird der Task nicht mehr in der Liste angezeigt.

## 5. Tasks ohne dauerhafte Speicherung verwalten

Als Benutzer möchte ich die To-do-Liste während der laufenden Serversitzung verwenden, damit ich temporäre Aufgaben verwalten kann.

**Akzeptanzkriterien:**

- Tasks werden im Backend während der Laufzeit gespeichert.
- Nach einem Neustart des Backend-Servers sind die vorherigen Tasks nicht mehr vorhanden.
- Es gibt keine dauerhafte Speicherung in einer Datenbank oder Datei.
