# Counterexample Compiler

## Thesis
False mathematical statements should be handled as first-class outputs, not failed proof attempts.

## Product
Given a conjecture, search for the smallest or most explanatory counterexample and produce a verified disproof certificate.

## Modes
- finite-model search
- SMT/SAT-backed search
- numeric-to-symbolic witness lifting
- hypothesis-dropping mutation
- adversarial boundary-case generation
- Lean-checked witness/proof when possible

## Output
`FALSE` plus witness, violated condition, minimality information, which assumptions would repair the theorem, and a machine-verifiable certificate.

## Value
- theorem debugging
- AI math evaluation
- faster conjecture refinement
- formal library QA
- scientific model falsification

## Strategic role
Proof systems are biased toward proving. A proof/disproof symmetric platform is more useful for discovery and far safer for autonomous mathematics.
