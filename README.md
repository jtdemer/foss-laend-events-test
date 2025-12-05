
# FOSS LÄND Community-Kalender (Starter)

Einreichungen erfolgen über **GitHub Issue Forms**. Nach Freigabe (Label `event:approved`) aktualisiert ein Workflow die **`events.ics`** per Commit.

## Einreichen
- Nutze das Formular: `Issues` → `New issue` → `Event einreichen`.

## Moderation
- Maintainer prüfen die Felder / Plausibilität.
- Bei Erfolg Label `event:approved` → ICS-Update.

## Veröffentlichung
- GitHub Pages zeigt eine Kalender-Ansicht (Open Web Calendar Embed).
- Die ICS-Datei liegt im Repo: `events.ics`.

## Technische Basis
- IssueOps Form Parser (Issue → JSON)
- GitEvents ICS Generator (Issues → `.ics`)
- Open Web Calendar Embed (Anzeige)

## Lizenz
- Standard: MIT (für diese Beispiel-Dateien).
- Alternativ für Inhalte: CC BY 4.0 oder CC BY-SA 4.0 (siehe LICENSE-CC.txt).
