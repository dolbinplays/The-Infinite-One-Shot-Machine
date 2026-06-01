# The Infinite One-Shot Machine

Version: v0.26.05.30.0006

## Stage 2 Import Extraction Upgrade Patch

This build advances the roadmap from Stage 2A Text Import to Stage 2 Import Extraction Upgrade.

### Included

- GitHub Pages-ready single-file app
- Adventure Remix Engine
- Host Mode with host-only secrets
- Component Library editor
- JSON import/export
- Text importer
- URL import attempt
- URL import fallback for CORS-blocked pages
- Candidate review/approval flow
- Build Health panel

### Important URL Import Note

Because this version runs as a static GitHub Pages app, many websites will block direct browser fetching through CORS. This patch still implements the Stage 2B workflow safely:

1. Paste a URL.
2. App attempts to fetch it.
3. If blocked, app explains why.
4. User can paste page text into the fallback importer.
5. Extracted candidates can be reviewed and imported into the component library.

A future backend version can replace this with server-side URL fetching.


## v0.26.05.30.0006 - Stage 2 Import Extraction Upgrade

This patch rolls the Clam Island import test findings into the roadmap direction:

- URL import remains URL-assisted on GitHub Pages because many sites block browser fetch/CORS.
- Pasted adventure text import is now the primary reliable path until a backend importer exists.
- Extractor upgraded to recognize:
  - numbered adventure headings and questlines
  - towns, villages, shops, taverns, temples, offices, and dungeons as locations
  - factions described in prose
  - NPC parenthetical lines and "run by" service-owner lines
  - encounter blocks with environments and monsters
  - traps and complications
  - rewards and item blocks
  - clue/twist keywords such as maps, wanted posters, sigils, secrets, and hidden truths
- Candidate preview is now grouped by component type with category-select buttons.

Roadmap/Bible note: This is a Stage 2A/2B quality patch, not a new stage. It improves the Adventure Import System before PDF import or Host Mode expansion.
