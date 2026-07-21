# Redeployment Instructions — Public Package v1.1.0

This final deployment package follows the established Lititz BMX overwrite-and-review protocol for the existing repository.

## Destination

- **GitHub account:** `Article134-tech`
- **Existing repository:** `lititzbmx-docs`
- **Branch:** `main`
- **Affected top-level folder:** `record-collection`

Do **not** create a new repository. Do **not** move, rename, delete, or restructure any sibling repository content.

## Controlled GitHub Desktop sequence

1. Open GitHub Desktop.
2. Confirm the selected repository is `Article134-tech/lititzbmx-docs`.
3. Confirm the branch is `main`.
4. Click **Fetch origin** and resolve any incoming changes before continuing.
5. Open the local repository in File Explorer.
6. Make a local backup copy of the existing `record-collection` folder.
7. Copy the complete `record-collection` folder from this deployment ZIP into the repository root.
8. When Windows identifies matching files, choose **Replace the files in the destination**.
9. Return to GitHub Desktop and inspect the complete Changes list.
10. Confirm every changed path begins with `record-collection/`.
11. Confirm no root file or sibling folder changed.
12. Use this commit summary:

   `Expand Lititz BMX Record Collection to v1.1.0`

13. Commit to `main` and click **Push origin**.
14. Complete the post-deployment checks in `docs/V1.1.0_GITHUB_DEPLOYMENT_WALKTHROUGH.md`.

## Root repository README

No root-repository README change is required when the existing Record Collection entry is already present. If that entry is missing or still says seven dossiers, use the prepared replacement text in `docs/ROOT_README_INDEX_ENTRY.md` as a separate README-only commit.

## Public/private rule

Only this reviewed public package belongs in `lititzbmx-docs`. Do not upload the private preservation supplement or any working-source folder outside this package.
