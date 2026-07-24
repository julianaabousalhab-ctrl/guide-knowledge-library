# Guide Knowledge Library

A structured knowledge base of **BrainLifts** — reusable, evidence-grounded units of Alpha Guide practice — extracted from real coaching artifacts and organized by topic of Guide practice.

## What's a BrainLift?

One recurring, transferable Guide behavior or decision rule, written so a Guide who wasn't in the room can use it. Every BrainLift contains a Pattern, verbatim Evidence with linked source artifacts, an Anti-Pattern drawn from the same corpus, a Reusable Coaching Move, and a Confidence Level with rationale. See [FILE_SCHEMA.md](FILE_SCHEMA.md) for the full template.

## Repository structure

```
brainlifts/
  <Category>/                e.g. Coaching & Accountability
    Note.md                  scope log: what's in, what's out, what was ambiguous
    <Node>/                  e.g. Action Planning
      BL-0XX.md              one BrainLift per file
TAXONOMY_PROPOSAL.md         category/node structure, sources in use, known gaps
FILE_SCHEMA.md               BrainLift file format
```

Taxonomy paths follow [TAXONOMY_PROPOSAL.md](TAXONOMY_PROPOSAL.md). Nodes marked *(planned)* exist in the taxonomy but have no BrainLifts yet.

## Current contents

- **98 BrainLifts** (BL-001–BL-098) across 8 categories and 30+ nodes
- Per-category **Note.md scope logs** documenting inclusion/exclusion decisions
- **Confidence levels** on every BrainLift: High = 3+ independent instances across guides/campuses or an executed contrast; Medium = real pattern, few instances or a single corpus; Low = one documented case or flagged by its own scope log

## Sources

BrainLifts draw on: 1:1 Limitless Meetings transcripts, Mentor Mindset Analytics, Limitless Launch recordings, Townhall transcripts, Student 360 Reviews, Student360 Profiles, Motivational Models, Feathers and Fix retrospectives, Behavior Plans and Trackers, Alpha Incident Reports, Parent Comms, Session Snapshots, and the SY25-26 Standards for Guide Comments (normative). Each category's sources-in-use and known gaps are listed in TAXONOMY_PROPOSAL.md.

Some source documents recur across BrainLifts within a node: the underlying corpus is still limited, and each citation supports a distinct behavior within the artifact. Confidence levels account for this.

## Conventions

- Evidence quotes are verbatim — including terminology now superseded (e.g. "Test2Pass" in quoted material; current term: AlphaTest).
- Related BrainLifts cross-reference each other with `Related:` / `Scope note:` / `Boundary:` lines rather than duplicating content.
- Dates use `YYYY-MM-DD`. Student names in public-facing examples are anonymized as [Student].

## Status

All BrainLifts are candidates pending human review. Empty nodes are work in progress.
