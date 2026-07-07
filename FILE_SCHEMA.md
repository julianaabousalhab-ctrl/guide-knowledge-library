# BrainLift File Schema

## Purpose

This schema defines the standard structure for every BrainLift document in the repository. Using a consistent format makes BrainLifts easier to read, compare, search, and expand as the knowledge base grows.

---

# Required Structure

## Metadata

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| id | String | Yes | Unique identifier for the BrainLift. |
| title | String | Yes | Name of the BrainLift. |
| taxonomy_path | String | Yes | Full taxonomy location of the BrainLift. |
| sources | List | Yes | Source documents used to derive the insight. |
| last_updated | Date | Yes | Date the BrainLift was last modified. |

---

## Pattern

### Description

The recurring behavior, principle, or observation consistently found across multiple pieces of evidence.

### Type

Text

---

## Evidence

### Description

Supporting evidence demonstrating the pattern.

### Type

List

### May include

- Evidence summary
- Direct quotes
- Transcript excerpts
- QC observations
- Student reflections
- Guide observations

---

## Anti-Pattern

### Description

A common Guide behavior that prevents the desired outcome or weakens the learning experience.

### Type

Text

---

## Reusable Coaching Move

### Description

A practical coaching recommendation that Guides can immediately apply during Launches or Workshops.

### Type

Text

---

# Standard BrainLift Template

```markdown
---
id: <uniques_brainlift_id>
title: <brainlift_title>
taxonomy_path: <full_taxonomy_path>
sources:
<list_of_sources>
last_updated: <YYYY_MM_DD>
---

# Pattern

...

# Evidence

...

# Anti-Pattern

...

# Reusable Coaching Move

...
```
