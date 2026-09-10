# Assumption Graph & Linter

## Idea
Make assumptions first-class machine-readable objects and track how they propagate through derivations, models and conclusions.

Examples:
- incompressible flow
- small-angle approximation
- linear elasticity
- steady state
- Gaussian noise
- isotropy
- locality
- weak coupling
- no-slip boundary

## What the linter does
```text
Equation A assumes: small angle
Equation B assumes: finite rotation
Combined model:
✗ incompatible assumptions
```

It can also report:
```text
Conclusion C depends on:
- incompressibility
- Re < 1
- constant viscosity

Changing viscosity law invalidates 4 downstream results.
```

## Material value
Hidden assumptions are a major source of incorrect model reuse. Engineering teams need to know whether a model from one regime is valid in another.

## Strategic value
This turns a weak point of scientific documents into structured data. It strengthens semantic search, literature compilation, claim auditing, model passports and impact analysis.

## Differentiation
Generic knowledge graphs store relations. This graph performs logical compatibility and dependency checks over scientific assumptions.

## MVP
Define an assumption ontology for mechanics/fluid ODE examples; attach assumptions to equations; propagate them through transformations; flag contradictions and out-of-regime reuse.