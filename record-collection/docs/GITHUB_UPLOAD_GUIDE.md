# GitHub Upload Guide

## Established repository destination

The Lititz BMX Record Collection belongs inside the existing public documentation repository:

- **Account:** `Article134-tech`
- **Repository:** `lititzbmx-docs`
- **Branch:** `main`
- **Destination folder:** `record-collection/`

No new repository is required or recommended for this upload.

## GitHub Desktop method

1. Open GitHub Desktop.
2. Confirm `Article134-tech/lititzbmx-docs` is selected.
3. Confirm the branch is `main`.
4. Click **Fetch origin**.
5. Open the local repository folder in File Explorer.
6. Copy the complete `record-collection` folder into the repository root.
7. Do not delete, rename, replace, or reorganize any existing repository content.
8. Return to GitHub Desktop and confirm every changed path begins with `record-collection/`.
9. Commit with:

   `Add Lititz BMX Record Collection archival standard and first seven dossiers`

10. Push to `origin`.

## Repository index update

After the first commit is visible on GitHub, add a link to the existing root `README.md` using the text in `docs/ROOT_README_INDEX_ENTRY.md`.

Commit that README-only change separately with:

`Add Record Collection to repository index`

## Verification after upload

1. Confirm `record-collection/README.md` renders on GitHub.
2. Open `record-collection/COLLECTION_INDEX.md` and test dossier links.
3. Confirm images and PDFs display.
4. Confirm the existing repository folders and files are unchanged.
5. Confirm no unredacted phone number appears in repository search.
6. Confirm the private preservation supplement was not uploaded.

## Private supplement

The private preservation supplement must remain outside the public `lititzbmx-docs` repository. It preserves unaltered source material requiring privacy controls.
