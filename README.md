# The Infinite One-Shot Machine

Version: v0.26.05.30.0005

## Stage 2B URL Import Patch

This build advances the roadmap from Stage 2A Text Import to Stage 2B URL Import.

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
