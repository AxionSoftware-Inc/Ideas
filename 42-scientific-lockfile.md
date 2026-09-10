# Scientific Lockfile

## Idea
Create the scientific equivalent of `package-lock.json`: freeze every external dependency needed to reproduce a result, including not only software but scientific meaning.

## Lockfile records
- model package/version/hash
- equations / semantic schema version
- physical constants and source/version
- material-property datasets
- calibration datasets
- solver and numerical settings
- units/conventions
- random seeds
- environment/container
- external paper/model identifiers

## Why it matters
A result can change even when source code does not: constants are revised, datasets update, remote models change, solver defaults shift, or a material database entry is replaced.

## Material value
Cheap insurance for long-lived engineering projects, regulated evidence and reproducible research.

## Strategic value
Pairs naturally with Reproducibility Capsules, Model Registry, Provenance Graph and Scientific CI. It gives the ecosystem deterministic builds of scientific results.

## Differentiation
Software lockfiles freeze packages. A scientific lockfile freezes **the complete evidence/model dependency state**.

## MVP
Generate `science.lock` for a simulation project containing model/data hashes, parameters, units, solver/version and environment; provide `verify-lock` and reproducible rerun commands.