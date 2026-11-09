# .github (Org-Profil von cldNexus)

Dieses Repo ist das **Profil der GitHub-Org cldNexus**: `profile/README.md` wird auf https://github.com/cldNexus angezeigt. Das Repo ist **öffentlich**, jede Zeile ist weltweit lesbar.

## Vor jeder Änderung pullen
Vor **jedem** Change zuerst `git pull --ff-only` (auf dem aktuellen Branch), damit Änderungen von Nico und Nick nicht überschrieben werden. Für einen Feature-Branch: erst `main` pullen, den Branch von dort anlegen, vor dem Push erneut `git pull --rebase`. Bei einem Fehler (Konflikt, uncommittete Änderungen) nichts erzwingen und kein `--force`, sondern dem User den Stand zeigen und nachfragen.

## Struktur
- `profile/README.md`: Org-Startseite (Logo, Tagline, Terminal-Karte als GIF, Was wir bauen).
- `profile/avatar.jpg`: Branding-Bild der Org (gleich wie der Org-Avatar).
- `profile/cftch.gif`: animierte cftch-Terminalkarte (Fenster mit drehendem ASCII-Skull und Infos). Wurde aus der Karte auf `cldnexus.github.io` Bild für Bild mit Headless-Chrome gerendert (Skull-Rotation per `#t=<Sekunden>` an der Seiten-URL) und zu einer nahtlosen Schleife zusammengesetzt. Bei einem neuen Stand der Karte das GIF neu erzeugen und unter **neuem Dateinamen** ablegen, sonst zeigt GitHub wegen des Bild-Caches lange das alte Bild.

## Regeln
- **Nur Harmloses**: keine Links auf private Repos oder interne Systeme, keine Mailadressen, Server, Tokens, Zugangsdaten oder persönlichen Daten. Vorschläge für neue Inhalte vor dem Push dem User zeigen.
- Branding: Farben Cyan `#00E5FF`, Magenta `#FF2BD6`, Rot `#FF4D4D`, Hintergrund `#05020A`, Schrift Share Tech Mono; Logo `profile/avatar.jpg`.
- Bilder per absoluter `raw.githubusercontent.com`-URL einbinden (relative Pfade funktionieren im Org-Profil nicht zuverlässig). GIFs klein halten (unter ca. 2 MB).
- Sprache: Deutsch, Du-Form, knapp, keine Marketing-Floskeln. Name immer `cldNexus` (kleines c, großes N), Handles `cldNico`, `cldNiick`.
- Push nur auf Auftrag des Users (Änderungen sind sofort öffentlich sichtbar). Größere Umbauten auf einem Feature-Branch mit Pull Request (Skill `feature-branch-workflow`).
