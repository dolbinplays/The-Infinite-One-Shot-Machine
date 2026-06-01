# The Infinite One-Shot Machine — v0.26.05.30.0007

Stage 2B.2 Import Quality Pass.

## What changed

- Added generic heading filtering for import candidates.
- Added confidence scoring for extracted components.
- High-confidence candidates are selected by default.
- Medium and low-confidence candidates are reviewable but not auto-selected.
- Added visible confidence labels and score reasons.
- Added import controls for selecting by confidence level.
- Improved Build Health checks for Stage 2B.2.

## Current roadmap status

- Stage 0 Foundation: Complete
- Stage 1A Component Database: Complete
- Stage 1B Adventure Assembly: Complete
- Stage 1C Host Secrets: Complete
- Stage 1D Component Library: Complete
- Stage 2A Text Import: Complete
- Stage 2B URL-Assisted Import: Complete with GitHub Pages/CORS fallback
- Stage 2B.1 Extraction Upgrade: Complete
- Stage 2B.2 Import Quality Filtering: Current patch

## Suggested test

Paste the Clam Island source text into the importer. The parser should still find useful hooks like “Defeat Bonecrushers” and “Defeat Cursed Club Clan,” while generic labels like “Main quest,” “MAINQUEST LINES,” and “Quest ideas” should be low confidence and left unselected by default.
