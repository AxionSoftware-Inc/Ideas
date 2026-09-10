# Physical Plausibility Firewall for AI-Generated Science

## Idea
Put a deterministic/semideterministic scientific verification layer between generative AI and any accepted equation, model, parameter set or simulation result.

The AI may propose. The firewall decides whether the proposal is physically admissible.

## Checks
- dimensional consistency
- type/domain/codomain consistency
- conservation laws
- positivity / boundedness
- symmetry constraints
- limiting cases
- known invariants
- causality / temporal ordering where applicable
- boundary/initial condition completeness
- parameter plausibility
- consistency with declared assumptions
- cross-check against numerical model or formal proof where possible

## Example
```text
AI proposal: E = m v
Firewall:
✗ dimension mismatch: energy != momentum
Reject
```

Or a subtler result:
```text
✓ units consistent
✓ equations solvable
✗ violates mass conservation by 2.7%
⚠ extrapolates outside validated Reynolds-number range
```

## Material value
Any company using LLMs for engineering/scientific work needs a trust layer before generated outputs enter design, simulation or reporting workflows.

## Strategic value
This can become the standard validation gateway for AI-generated science and connects directly to Equation Debugger, Model Testbench, Model Passport, Claim Auditor and operator reasoning.

## Differentiation
Do not market it as an AI fact checker. It is a **physics-aware compiler/verifier** with explicit failure evidence.

## MVP
REST/CLI service taking structured equations + metadata and returning pass/fail diagnostics for dimensions, units, declared constraints, invariants and a small library of limiting-case tests.