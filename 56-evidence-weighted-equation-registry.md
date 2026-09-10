# Evidence-Weighted Equation Registry

## Goal
Create a registry where equations are first-class versioned scientific objects.

Each equation stores:
- canonical semantic form
- alternative notations
- derivation dependencies
- assumptions and validity regime
- dimensional information
- experimental or computational evidence
- known implementations
- benchmark tests
- competing variants

## Why useful
Instead of copying an equation from a paper, a researcher imports a versioned equation object with known evidence and constraints.

## Example
```text
import equation://battery/butler-volmer@2.3
```

## Moat
This bridges literature, executable models, verification and the Verified Model Registry. Over time it becomes infrastructure for machine-actionable scientific knowledge.