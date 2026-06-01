# The Infinite One-Shot Machine

Version: v0.26.05.30.0004  
Stage: 2A — Adventure Text Import

## What changed

This patch advances the project beyond Stage 1D into the first Stage 2 importer milestone.

Implemented:

- Classified adventure text importer
- Paste notes/public summaries and analyze them into candidate components
- Local heuristic classification into hooks, villains, NPCs, locations, encounters, clues, secrets, twists, rewards, complications, and finales
- Per-candidate review/type dropdown before approval
- Approve one candidate at a time
- Approve all candidates at once
- URL reference handling as a Stage 2B/2C placeholder
- Approved imported text is saved into the editable component library
- Build Health updated through Stage 2A

## Upload instructions

Upload `index.html` and this `README.md` to the root of the GitHub repository.

## Suggested success checks

1. Confirm the version badge shows v0.26.05.30.0004.
2. Paste a paragraph of adventure notes into the importer and click Analyze Text.
3. Confirm multiple candidates appear with component type dropdowns.
4. Approve one candidate and confirm the component library count increases.
5. Approve all candidates and confirm the library updates.
6. Generate adventures and confirm imported components can appear.
7. Paste a URL and confirm it is handled as a source/reference candidate without breaking.
8. Confirm existing Stage 1D add/edit/delete/import/export still works.
9. Confirm Build Health shows Stage 2A implemented.
