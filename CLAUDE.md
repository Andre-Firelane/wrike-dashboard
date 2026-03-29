# Projektkontext: Andre Workstation Dashboard

## Zweck
Dieses Projekt dient der Teamplanung über Wrike. Ziel ist die Entwicklung eines Dashboards, das Aufgaben, Zuständigkeiten und Wochenpläne des Teams visualisiert.

## Wrike-Anbindung
- **Projekt in Wrike:** Andre Workstation
- **Wrike Projekt-ID:** MQAAAAEHNC4r
- **Permalink:** https://www.wrike.com/open.htm?id=4415827499
- Daten werden über den Wrike MCP-Konnektor abgerufen

## Team
| Name | Wrike Contact ID |
|---|---|
| Andre Peschka | KUAUEEQL |
| Markus Franck | KUAUEJUH |
| Christian Langpaap | KUAUGDWA |
| Marvin Poggensee | KUAUGKT3 |

## Dashboard-Ziel
- Wöchentliche Übersicht: Wer macht was in welcher Woche?
- Aufgaben pro Person aus dem Wrike-Projekt „Andre Workstation" abrufen
- Darstellung nach Woche und Teammitglied
- Später ggf. erweiterbar um Status, Auslastung, etc.

## Technologie-Stack
(noch festzulegen – bitte vor Beginn mit Andre abstimmen)

## Konventionen
- Sprache: Deutsch (UI und Kommentare)
- Alle finalen Dateien kommen in diesen Projektordner
- Skills und Vorlagen liegen unter `.claude/skills/`

## MCP-Konfiguration (für Claude Code)
Um den Wrike-Konnektor in Claude Code zu nutzen, muss er einmalig eingerichtet werden:
```bash
claude mcp add wrike --transport http <wrike-url>
```
Die genaue URL ist im Cowork-Konnektor hinterlegt.
