# Greg Mathias / Chasing Harry Episode 4 - Validation Report

**Package version:** 1.3.0  
**Validation date:** 2026-07-22  
**Result:** PASS

## Recovered and preserved

- corrected v1.2.0 Record Collection base;
- 32 supplied published-frame captures;
- nine Studio/channel publication-evidence screenshots;
- one supplemental supplied image preserved without forcing a GM identifier;
- supplied timestamped parent transcript;
- supplied working-source PDF;
- supplied press release;
- all pre-existing v1.2.0 files.

## Automated validation

- [x] 32 frame captures - 32
- [x] 32 visible record directories - 32
- [x] GM-010 missing directory
- [x] GM-012A present
- [x] GM-012B present
- [x] All JSON files parse - 66
- [x] Register count - 32
- [x] Unique visible IDs - ['GM-001', 'GM-002', 'GM-003', 'GM-004', 'GM-005', 'GM-006', 'GM-007', 'GM-008', 'GM-009', 'GM-011', 'GM-012A', 'GM-012B', 'GM-013', 'GM-014', 'GM-015', 'GM-016', 'GM-017', 'GM-018', 'GM-019', 'GM-020', 'GM-021', 'GM-022', 'GM-023', 'GM-024', 'GM-025', 'GM-026', 'GM-027', 'GM-028', 'GM-029', 'GM-030', 'GM-031', 'GM-032']
- [x] GM-010 excluded from visible records
- [x] Two distinct #12 IDs
- [x] GM-012A Private/Uploaded - ('private', 'uploaded')
- [x] GM-012B Public/Published - ('public', 'published')
- [x] GM-012A date - 2025-11-10
- [x] GM-012B date - 2025-11-14
- [x] GM-012A Studio description preserved
- [x] All 32 descriptions included
- [x] All direct URLs null
- [x] All parent URLs included
- [x] All publication dates included
- [x] All transcript refs included
- [x] Sensitive qualifications included
- [x] All CSV files parse - 39
- [x] CSV register count - 32
- [x] CSV descriptions included
- [x] All PNG files decode - 115
- [x] Frame original filenames preserved
- [x] Frame hashes preserved
- [x] Hash identity 09-original-transcript-timestamped.txt - e20a70cc025e3a004199e343718887bee952945709766f1632bc264573b641ae / e20a70cc025e3a004199e343718887bee952945709766f1632bc264573b641ae
- [x] Hash identity 07-reels-and-short-descriptions-working-source.pdf - 58445514fa32954a09a7733499c037a18497a8a7d5b1697c12b0abd4bdf1f7d8 / 58445514fa32954a09a7733499c037a18497a8a7d5b1697c12b0abd4bdf1f7d8
- [x] Hash identity 08-press-release.pdf - 144a3b86e60ad8dc1f160705f9d537372fe5ff6bda45e429fc4d2e2ca2178bac / 144a3b86e60ad8dc1f160705f9d537372fe5ff6bda45e429fc4d2e2ca2178bac
- [x] All PDFs have valid header - 21
- [x] All v1.2.0 base files retained - []
- [x] All dossier metadata schema-valid - 22
- [x] All local Markdown/HTML links resolve - []
- [x] Derivative SHA256SUMS verifies - 249 entries; bad=[]
- [x] Frame manifest has 32 rows - 32
- [x] Frame manifest hashes verify
- [x] Source manifest covers 45 sources - 45
- [x] Source manifest hashes verify
- [x] No temporary files in package - []

## Counts

- Package files before ZIP: 893
- JSON files parsed: 66
- CSV files parsed: 39
- PNG files decoded: 115
- PDF files checked: 21
- Visible Short records: 32
- Explicit missing record: GM-010
- Distinct number-12 records: GM-012A and GM-012B

## Source fixity

- Parent timestamped transcript: `e20a70cc025e3a004199e343718887bee952945709766f1632bc264573b641ae`
- Working-source PDF: `58445514fa32954a09a7733499c037a18497a8a7d5b1697c12b0abd4bdf1f7d8`
- Press release: `144a3b86e60ad8dc1f160705f9d537372fe5ff6bda45e429fc4d2e2ca2178bac`

The separately supplied copies are byte-identical to the copies already preserved in the corrected v1.2.0 parent dossier.

## PDF verification

The working-source PDF rendered successfully to 19 pages and the press release rendered successfully to 1 page at 150 DPI. Contact-sheet inspection showed readable pages without render failure, clipped-page corruption, or black-page substitution.

## Final packaging checks

After this report was written, the v1.3.0 deployment manifest and root SHA-256 list were regenerated. The delivery process then verified every root checksum, every manifest row, the ZIP CRC, and the single top-level `record-collection/` package shape. The external delivery validation file records the final ZIP byte count and SHA-256.
