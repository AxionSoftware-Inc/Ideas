# Theorem Semantic Versioning

## Thesis
Formal libraries need semantic versioning at the theorem/definition level, not just package releases.

## Product
Classify a change as:
- proof-only / no API change
- statement equivalent
- statement weakened
- statement strengthened
- assumptions added/removed
- definition meaning changed
- downstream breaking change

## Capabilities
Compute affected declarations, suggested migration paths, compatibility shims, and a machine-readable `math-semver` report.

## Example
`2.3.1` proof optimization; `2.4.0` equivalent theorem with new reusable API; `3.0.0` changed mathematical contract.

## Value
Makes large formal libraries safer to depend on and enables stable enterprise theorem APIs.

## Strategic role
Combines theorem equivalence, dependency graphs, proof repair and semantic diff into a governance layer for verified mathematics.
