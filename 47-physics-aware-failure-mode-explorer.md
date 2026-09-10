# Physics-Aware Failure Mode Explorer

## Idea
Use a system's equations, component constraints, parameter uncertainty and operating envelope to generate and rank plausible physical failure modes before exhaustive testing.

## It asks
- Which constraints can be violated first?
- Which parameter combinations create instability?
- Which couplings amplify small faults?
- What single-point failures are observable/unobservable?
- Which tests best distinguish failure hypotheses?

## Output
```text
Failure candidate #1: thermal runaway under high internal resistance
Trigger region: T > ..., current > ...
Early indicators: dT/dt, voltage sag
Recommended test: ...
Evidence: model path ...
```

## Material value
FMEA and fault analysis consume expensive expert time in product engineering. A physics-grounded explorer can accelerate candidate generation and prioritization, while humans retain approval for safety-critical conclusions.

## Strategic value
Links Missing Physics Diagnoser, Safety Envelope, Experiment Design, Provenance and Domain-of-Validity into reliability engineering.

## Differentiation
Not a generic LLM-generated FMEA checklist. Every proposed failure mode should trace to a model mechanism or explicit empirical evidence.

## MVP
Component-level dynamical models with threshold constraints; systematic parameter/fault perturbation; stability/sensitivity analysis; ranked failure scenarios with reproducible simulations.