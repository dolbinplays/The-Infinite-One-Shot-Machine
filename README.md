# The Infinite One-Shot Machine

A web-first Virtual Dungeon Master prototype.

Core vision:

> Feed me adventures I like. Build something new from them. Run it. Surprise me.

## Current Build

Version: `v0.26.05.30.0001`

Roadmap status:

- Stage 0 — Foundation: implemented for static GitHub Pages hosting.
- Stage 1 — Adventure Remix Engine: first playable local prototype.
- Stage 2 — Adventure Import System: placeholder only.

## Features in this build

- Single-page browser app.
- Visible version number.
- Random one-shot generator.
- Reusable adventure component model.
- Host Mode scene selector.
- Clue, secret, NPC, faction, twist, reward, complication, and finale generation.
- Local session log.
- Browser text-to-speech scene narration.
- Local save/load.
- JSON export.
- Importer placeholder for future URL/text/PDF ingestion.
- Build Health panel for roadmap review.

## How to run

Open `index.html` in a browser, or host the repository with GitHub Pages.

## GitHub Pages setup

1. Open the GitHub repository.
2. Go to **Settings**.
3. Go to **Pages**.
4. Set source to the default branch and root folder.
5. Save.
6. Open the published Pages URL.

## Development rules

- Every build should remain playable.
- Version format should follow `v0.yy.mm.dd.hhmm`.
- Adventure components should remain human-editable.
- Preserve mystery and surprise.
- Web-first until the project proves it needs a heavier client.
