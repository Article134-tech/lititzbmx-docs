# Upload Instructions — Existing Lititz BMX Documentation Repository

This package is designed for the established Lititz BMX GitHub workflow.

## Destination

- **GitHub account:** `Article134-tech`
- **Existing repository:** `lititzbmx-docs`
- **Branch:** `main`
- **New top-level folder:** `record-collection`

Do **not** create a new repository. Do **not** replace the repository root. Do **not** delete, rename, or restructure any existing Lititz BMX folders or files.

## Safe upload sequence in GitHub Desktop

1. Open GitHub Desktop.
2. Confirm the current repository is `Article134-tech/lititzbmx-docs`.
3. Confirm the current branch is `main`.
4. Click **Fetch origin** before changing files.
5. Open the repository in File Explorer.
6. Copy the complete `record-collection` folder from this package into the root of the existing local `lititzbmx-docs` folder.
7. Confirm that the existing folders remain untouched, including:
   - `brand-assets`
   - `campaigns`
   - `data`
   - `learning-resources`
   - `reference`
   - `standards`
8. Return to GitHub Desktop and review the changed-file list. It should show only newly added files under `record-collection/`.
9. Use this commit summary:

   `Add Lititz BMX Record Collection archival standard and first seven dossiers`

10. Commit directly to `main`.
11. Click **Push origin**.
12. Verify the new folder on GitHub before making any index change.

## Separate repository-index update

After the folder upload has been verified, update the existing repository `README.md` in a separate commit using the copy-ready text in:

`record-collection/docs/ROOT_README_INDEX_ENTRY.md`

Use this second commit summary:

`Add Record Collection to repository index`

Keeping the folder upload and index update in separate commits follows the established additive, reviewable Lititz BMX workflow.

## Public/private rule

Only this reviewed public package belongs in `lititzbmx-docs`.

Do **not** upload the private preservation supplement to the public repository.
