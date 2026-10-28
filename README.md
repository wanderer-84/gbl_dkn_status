# gbl_dkn_status

Data pack for a private, non-commercial companion app (shared among friends). Not affiliated with or endorsed by
Bandai Namco. Game data © Bandai Namco Entertainment; card thumbnails from the Dragon Ball Z Dokkan Battle Wiki (Fandom).

Built daily from the public Global database export at https://github.com/Nicholas1006/dokkan-backend
(only when the game database version changes). Unreleased content is excluded.

| File | Content |
|---|---|
| `manifest.json` | `game_db_version`, build date, source commit, size and sha256 of the files, row counts |
| `pack.db.gz` | SQLite (gzip): UR/LR cards with skills and EZA, super attack multipliers, links, categories, structured passive effects, items, support memories, stages, battles, enemies, missions |
| `icons.zip` | reference card thumbnails (`<art id>.webp`) used for on-device card recognition |
| `ai/teams.json` | suggested teams written with an AI assistant around the latest cards (shown in the app) |
| `app/latest.json`, `app/dkn-companion.apk` | latest build of the companion app (version, sha256, notes) used for in-app updates |

This repository always contains a single commit: history is replaced on every update.
