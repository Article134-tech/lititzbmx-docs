# GitHub Deployment — Greg Mathias Episode 4 Visual Access Fix v1.3.1

This folder remains integrated inside the existing Episode 4 parent dossier. Do not upload it as a disconnected project.

## Recommended patch deployment

1. Extract `GM4-visual-fix-v1.3.1.zip` to a short Windows path such as `C:\GM4FIX`.
2. Copy the extracted `record-collection` folder into the root of the local `Article134-tech/lititzbmx-docs` repository.
3. Choose **Replace the files in the destination** when Windows reports matching files.
4. In GitHub Desktop, confirm every changed path begins with `record-collection/`.
5. Confirm that the 32 published-frame PNG files appear as unchanged; this fix changes their display references, not their bytes.
6. Recommended commit summary: `Add visual access to Greg Mathias Episode 4 Shorts archive`.
7. Commit and push to `main`.
8. In GitHub, verify the Record Collection root, Fireside BMX Chat index, Episode 4 parent dossier, visual Shorts index, GM-010, GM-012A, GM-012B, and several individual GM record pages.
9. Complete the separate repository-root README index update using `record-collection/docs/ROOT_README_INDEX_ENTRY.md`.

## Full controlled replacement

The complete v1.3.1 ZIP may also replace the existing `record-collection/` folder. No unrelated repository folder should be changed.
