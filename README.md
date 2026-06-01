# The Infinite One-Shot Machine

Version: v0.26.05.30.0009

Stage 2B.4 Import Commit Hotfix

## What changed

- Fixed visible version badge so it matches the internal build version.
- Added component-library migration for older localStorage data that used singular keys.
- Fixed the import commit path so plural candidate types like hooks, npcs, factions, locations, encounters, clues, twists, rewards, and complications are accepted.
- Added self-healing in the import routine if expected library arrays are missing.
- Added a Build Health check for library key normalization.

## Upload instructions

Upload `index.html` and this `README.md` to the repository root for GitHub Pages.

After uploading, hard refresh the browser with Ctrl+F5. If import still reports unknown types, click Reset Defaults only if you are comfortable clearing local component data, or export your library first.
