# Lititz BMX Record Collection Archival Standard

**Version:** 1.0.0  
**Effective date:** 2026-07-20

## 1. Purpose

The Lititz BMX Record Collection preserves original media productions as complete archival events. A published recording is important, but it is only one part of the surviving record.

A dossier may also preserve:

- the proposal or original concept;
- question development and scripts;
- production notes and title graphics;
- the original public description and press release;
- raw and verified transcript layers;
- derivative Shorts, Reels, and clip descriptions;
- research and verification notes;
- rights, privacy, and preservation history.

## 2. Controlled hierarchy

```text
Collection -> Category or Series -> Dossier -> Record -> Source and Supporting Records
```

### Collection

**The Lititz BMX Record Collection** is the public-facing and institutional container.

### Category or series

Examples include:

- Fireside BMX Chat
- Pump Track Chat
- Unboxing
- Chasing Harry, as an explicitly named subseries of Fireside BMX Chat

A category or series describes **where the work belongs editorially**. It does not determine the dossier type.

### Dossier

A dossier is the complete archival package for one recorded work or event.

### Record

The first document in a dossier is its descriptive record, such as an **Interview Record**. The record explains what the work is, who participated, why it matters, what survives, and what remains uncertain.

### Source and supporting records

These include the original recording reference, transcript, description, title card, proposal, press release, research, derivatives, and administrative notes.

## 3. Dossier types

Dossier type is determined by **what happened**, not by the series name.

### Interview Dossier

For interviews, conversations, and oral histories. Subtypes may include:

- studio or remote interview;
- on-location interview;
- family oral history;
- experiential interview;
- collection encounter;
- memorial walk;
- recovered or lost conversation.

### Recording Dossier

For recordings in which the primary event is not an interview, including unboxings, artifact walkthroughs, demonstrations, and field captures.

### Presentation Dossier

For speeches, public testimony, museum talks, and formal presentations.

### Tour Dossier

For guided museum, archive, track, or exhibit tours in which the tour itself is the principal work.

### Documentary Dossier

For edited documentary productions with a distinct production history and evidence package.

## 4. Standard Interview Dossier structure

```text
Interview Dossier
├── README.md
├── interview-record.md
├── metadata.json
├── CITATION.cff
├── assets/
├── source/
│   ├── youtube-record.md
│   ├── published-description.md
│   ├── original-transcript-timestamped.txt
│   ├── pre-production/
│   └── publication/
├── transcript/
│   └── working-transcript.md
└── docs/
    ├── dossier-contents.md
    ├── provenance.md
    ├── topic-index.md
    ├── chapter-index.md
    ├── curator-notes.md
    ├── verification-notes.md
    ├── transcript-status.md
    ├── source-inventory.md
    ├── rights-and-access.md
    └── revision-history.md
```

A missing section is documented; it is not filled with invented material.

## 5. Interview Record requirements

The Interview Record is not a transcript or metadata dump. It should allow a future researcher to understand the recording without watching it first.

Required fields:

- stable record identifier;
- title and published title;
- collection and explicit subseries, when documented;
- dossier and recording type;
- host, guest, and other participants;
- recording and publication dates, or explicit “not supplied” language;
- location, with private addresses excluded;
- duration;
- summary;
- historical significance;
- major themes;
- source-material status;
- transcript status;
- preservation status;
- related records;
- curator and verification notes.

## 6. Transcript layers

1. **Raw machine transcript** - preserved unchanged.
2. **Working transcript** - timestamps normalized for editing; no silent factual repair.
3. **Verified transcript** - speaker-labeled and checked against audio.
4. **Annotated transcript** - optional research layer, kept separate from verified wording.

The recording remains authoritative when transcript and audio conflict.

## 7. Provenance and versioning

- Never overwrite an earlier historical state without retaining it in version control.
- Distinguish original publication material from later archival description.
- Preserve legacy URLs and titles as historical references, while identifying the current canonical URL.
- Record transformations such as redaction, page removal, normalization, and filename changes.
- Use Git history and `revision-history.md` together.

## 8. Testimony and verification

Oral-history statements are attributed to the speaker unless independently verified. Sensitive claims about health, behavior, death, motive, ownership, or business history must not be silently converted from recollection into institutional fact.

Recommended language includes:

- “the speaker recalls…”
- “according to the interview…”
- “the submitted materials identify…”
- “not independently verified in this dossier…”

## 9. Privacy and public access

- Do not publish private phone numbers, guest contact fields, signatures, or unreviewed legal forms.
- Use labeled public-access redacted copies when appropriate.
- Preserve unaltered originals in a separate restricted supplement.
- Do not bury or silently delete accidental unrelated material; preserve it privately and document why it was excluded publicly.

## 10. File naming

- lower-case kebab-case;
- stable record IDs;
- no spaces in repository filenames;
- descriptive role-based names rather than software-generated names;
- original filenames preserved in source inventories and the private supplement.

## 11. Preservation statuses

- `source-captured`
- `dossier-compiled`
- `transcript-verification-pending`
- `verified`
- `restricted-source-present`
- `documentation-gap-recorded`

Multiple statuses may apply simultaneously.

## 12. Guiding principles

1. Preserve context, not only content.
2. Preserve provenance and uncertainty.
3. Keep description, testimony, evidence, and interpretation separate.
4. Never make a missing record appear to exist.
5. Protect private information without erasing the existence of the original source.
6. Make the structure understandable to a future museum, archive, researcher, or family member without relying on institutional memory.
