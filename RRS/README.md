## RRS Folder Overview

This folder contains the expert-validated files used for benchmarking Requirement Extraction Automation (REA) output.

### Files

- `RRS.csv` — Final expert‑validated Reference Requirement Set (golden set) used for evaluation; definitive IDs.
- `out of scope set.csv` — Reviewed out‑of‑scope set: statements not belonging to the heater specification but potentially confusable by an automated extractor (e.g., Cozy Coffee Mug properties).

Use `RRS.csv` and `out of scope set.csv` for benchmarking REA output.

### ID Convention

The Reference Requirement Set uses a minimal, forward‑extensible identifier scheme:

1. Canonical (original) requirement: plain integer only (e.g., `31`).
2. First alternative formulation of that requirement: `alt. 31b` (letter sequence starts at b; the canonical form implicitly corresponds to an omitted a).
3. Additional alternatives increment the trailing letter: `alt. 31c`, `alt. 31d`, etc.

Rationale:

- Keeps canonical IDs short and stable over time.
- Supports high number of ordered alternative phrasings without renumbering.
- Maintains natural grouping via shared base integer.

Parsing guidance for tooling:

- Canonical rows match regex: `^[0-9]+$`
- Alternative rows match regex: `^alt\.\s+[0-9]+[b-z]$` (case-insensitive); letter range intentionally excludes a.

Example set:

```text
31
alt. 31b
alt. 31c
```

Only alternatives that convey materially different phrasing (scope emphasis, ambiguity resolution, quantitative variant, or contradiction) should be retained.
