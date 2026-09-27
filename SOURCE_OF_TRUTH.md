# SOURCE OF TRUTH

This document defines the canonical evidence hierarchy for **Chile State Institutional Map**.

## Canonical hierarchy

1. Primary official sources listed in `sources.csv`.
2. Literal source snapshots such as `data/executive_public_services_gobcl.csv`.
3. The normalized analytical master `data/institutional_map.csv`.
4. `data/coverage_audit.csv` for completeness and known boundaries.
5. `docs/methodology.md` and `docs/data_dictionary.md`.
6. README as a presentation layer.

## Preservation rule

A literal official directory snapshot is not silently rewritten to look current. Newer institutions, renamed bodies or controlled corrections belong in explicitly identified supplement/crosswalk layers.

## Integrity rules

- Separate stable institutions from volatile officeholders.
- Preserve source names when a layer is explicitly "as published".
- Do not invent official codes; repository IDs are analytical unless stated otherwise.
- Keep coverage claims tied to a stated official universe and verification date.
- Revalidate volatile institutional layers before a new release.

## Citation

Use `CITATION.cff` for the dataset and `sources.csv` for observation-level institutional provenance.
