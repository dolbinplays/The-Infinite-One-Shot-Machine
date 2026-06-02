# The Infinite One-Shot Machine

Version: v0.26.05.30.0010  
Stage: 2B.5 — Library Hygiene & Source Tracking

## Patch Summary

This patch builds on v0.26.05.30.0009 and adds source-aware component storage and library management tools.

### Included

- Source attribution for imported components
- Source field for manual component creation
- Import source name field for pasted/URL-assisted imports
- Library search by component text or source
- Source statistics panel
- Library audit panel
- Duplicate prevention using normalized component text
- Migration layer for older string-only component libraries
- Export/import support for source metadata
- Visible version badge updated to v0.26.05.30.0010

## Recommended Tests

1. Confirm the header version shows v0.26.05.30.0010.
2. Import Clam Island text with source name `Clam Island`.
3. Confirm selected candidates import successfully.
4. Open Component Library and search `Bonecrushers`.
5. Search `Clam Island` and confirm imported components appear.
6. Confirm Source Statistics shows counts for Clam Island.
7. Import the same candidates again and confirm duplicates are skipped.
8. Export the library JSON and confirm entries include `text`, `source`, and `importedAt`.
9. Refresh/load and confirm source metadata remains.

## Roadmap Status

Completed through Stage 2B.5. Next recommended milestone: Stage 2C — PDF Import, after source tracking and library hygiene are verified.
