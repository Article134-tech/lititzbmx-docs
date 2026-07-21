# Redeployment Instructions — Public Package v1.0.2

This package follows the established Lititz BMX overwrite-and-review protocol for the existing repository.

## Destination

- **GitHub account:** `Article134-tech`
- **Existing repository:** `lititzbmx-docs`
- **Branch:** `main`
- **Affected top-level folder:** `record-collection`

Do **not** create a new repository. Do **not** move, rename, delete, or restructure any established repository content.

## Established GitHub Desktop sequence

1. Open GitHub Desktop.
2. Confirm the current repository is `lititzbmx-docs`.
3. Confirm the current branch is `main`.
4. Click **Fetch origin**.
5. Open the repository in File Explorer.
6. Copy the complete `record-collection` folder from this package into the existing local `lititzbmx-docs` repository.
7. When Windows identifies matching files, choose **Replace the files in the destination**.
8. Return to GitHub Desktop and review the complete Changes list.
9. Confirm every changed path begins with `record-collection/`.
10. Confirm no root file or sibling folder changed.
11. Use this commit summary:

   `Update Record Collection visuals to v1.0.2`

12. Commit directly to `main`.
13. Click **Push origin**.
14. Verify the Record Collection landing page, Fireside BMX Chat index, Lost DIRTWERX dossier, Pump Track Chat page, and Unboxing page on GitHub.

## Root README

The repository-root README index update remains a separate commit. Use the prepared text in:

`record-collection/docs/ROOT_README_INDEX_ENTRY.md`

Recommended root-index commit summary:

`Add Record Collection to repository index`

## Public/private rule

Only this reviewed public package belongs in `lititzbmx-docs`. Do not upload the private preservation supplement.
