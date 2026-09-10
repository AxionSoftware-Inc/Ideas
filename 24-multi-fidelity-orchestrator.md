# Multi-Fidelity Orchestrator

## Idea
Automatically decide when to use a cheap approximate model, a medium-fidelity simulation, a high-fidelity simulation, or a real physical experiment.

Instead of always running the most accurate and expensive option, the system allocates compute/experiment budget to the source that gives the most information per cost.

## Example
```text
Goal: optimize turbine geometry
Budget: $2,000 compute

Recommended next evaluations:
- 120 low-fidelity runs
- 18 medium-fidelity CFD runs
- 3 high-fidelity runs near uncertain optimum
```

## Why it matters
2026 multi-fidelity optimization work explicitly targets expensive simulations and experiments by combining models of different costs and fidelities.

## Material value
Direct ROI is easy to explain: reduce simulation/HPC or laboratory cost while reaching a target confidence level faster.

## Strategic value
This is the scheduler for the entire scientific ecosystem. It can orchestrate simulators, surrogates, experiments and uncertainty reduction.

## Differentiation
Not another Bayesian optimization library. The product understands semantic model relationships, fidelity hierarchy, uncertainty, physical constraints and monetary/computational cost.

## MVP
Support 2-3 fidelity levels, cost-aware Bayesian/adaptive sampling, uncertainty tracking and a dashboard showing money/compute saved versus high-fidelity-only search.