# Verified Model Registry / Scientific Package Manager

## Idea
Create an `npm/pip`-like registry for scientific models, but packages are not just code. Each model package contains equations, semantic types, units, assumptions, domain of validity, reference papers, tests, validation evidence, uncertainty, supported solvers, and executable adapters.

A package could be imported as:

```text
use model mechanics/pendulum@2.1
use model electrochemistry/doyle-fuller-newman@1.4
```

## Why it matters
Scientific models are repeatedly reimplemented from papers, often with lost assumptions and inconsistent conventions. A verified registry turns models into reusable infrastructure.

## Key package fields
- semantic equations / IR
- inputs, outputs, units, coordinate conventions
- assumptions and validity regime
- numerical implementation(s)
- analytic limits / invariants
- testbench results
- provenance and citations
- V&V / uncertainty evidence
- version compatibility
- export targets: Python, Julia, C++, FMI/FMU, Lean where possible

## Material value
Engineering teams pay for trusted reusable components because reimplementation, validation and integration consume expert time. Enterprise tiers can provide private registries, approval workflows, signed packages and compliance evidence.

## Strategic moat
The registry becomes a network of machine-readable scientific knowledge. Every other product in this repository can consume it: debugger, simulation compiler, inverse problems, literature compiler, claim auditor, experiment design and equation discovery.

## Differentiation
Do not build another code package manager. The atomic unit is a **scientific model with evidence**, not a source archive.

## MVP
Start with 20-50 canonical mechanics/ODE models, each with semantic metadata, dimensional tests, conservation checks and executable Python/Julia backends.