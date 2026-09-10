# Equation Debugger / Verifier

## Product idea

Build an IDE-style diagnostics engine for mathematics and physics.

Programming IDEs detect type mismatches, undefined variables and invalid calls. Scientific editors should detect analogous mathematical and physical mistakes before a user wastes time deriving or simulating them.

## Example

If a user writes an equation where the left-hand side has the dimensions of energy while the right-hand side has the dimensions of momentum, the editor should flag the exact subexpression responsible for the mismatch.

## Diagnostics to support

- dimensional inconsistency
- unit inconsistency
- scalar/vector/tensor type mismatch
- invalid operator domain/codomain
- invalid matrix dimensions
- tensor index errors
- illegal or ambiguous contractions
- undeclared symbols
- conflicting assumptions
- hidden singularities
- invalid division by potentially zero quantities
- branch/domain problems
- missing initial conditions
- missing boundary conditions
- coordinate-frame inconsistency
- incompatible physical regimes
- sign-convention inconsistencies
- malformed transformations
- invalid use of identities/theorems

## UX

Diagnostics should attach to the exact expression span, similar to a code editor:

```text
Dimension mismatch
Expected: energy
Received: momentum
```

The user should be able to click a diagnostic and get:

- explanation
- expected type/unit/domain
- likely correction
- related identity or theorem
- automatic safe fix when unambiguous

## Advanced mode

The debugger can track derivations line by line:

```text
line 12 -> line 13
```

and verify whether the transformation is valid under the declared assumptions.

This turns a notebook into a partially verified scientific development environment.
