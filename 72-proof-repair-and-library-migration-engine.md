# Proof Repair & Library Migration Engine

## Problem
Formal libraries evolve. Renamed lemmas, changed signatures, stronger abstractions, namespace moves, deprecations and solver changes can break large proof bases.

## Product
A semantic migration engine that repairs proofs after dependency/library upgrades.

## Workflow
1. detect broken declarations
2. classify breakage: rename, signature change, missing instance, changed coercion, changed normal form, theorem replacement
3. search replacement premises
4. synthesize minimal patch
5. re-run kernel verification
6. generate migration report and semantic diff

## Enterprise value
Large formal verification projects cannot afford manual repair every time their theorem ecosystem moves. This is Dependabot + compiler migration assistant for mathematics.

## Moat
Historical graph of theorem/API changes, successful repairs, equivalences and replacement patterns becomes training and retrieval infrastructure for future migrations.
