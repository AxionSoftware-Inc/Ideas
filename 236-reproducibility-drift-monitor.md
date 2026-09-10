# Reproducibility Drift Monitor

## Problem
A workflow that reproduced last year may silently stop reproducing after dependency updates, hardware changes, data revisions or external service changes.

## Product
Periodically replay selected scientific capsules/benchmarks and detect drift in outputs, numerics, runtime, dependencies and environmental assumptions.

## Buyers
Labs, publishers, benchmark maintainers, model registries and regulated R&D.

## Material value
Catch reproducibility decay before a critical rerun, audit or customer request.

## Moat
Semantic tolerance rules distinguish harmless numerical variation from scientifically meaningful drift.

## MVP
Monitor several containerized workflows across dependency/version changes.