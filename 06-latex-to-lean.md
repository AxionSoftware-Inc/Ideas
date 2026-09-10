# LaTeX-to-Lean / Formal Verification Bridge

## Goal

Allow mathematicians and physicists to work in familiar notation while progressively translating suitable claims into formally verifiable statements.

## Pipeline

```text
natural language + LaTeX
  -> semantic scientific IR
  -> explicit variables/types/assumptions
  -> formal statement candidate
  -> Lean representation
  -> proof search / proof planning
  -> kernel verification
  -> verified / incomplete / disproved status
```

## Important distinction

The system must distinguish:

- formally verified
- verified only by symbolic transformation
- numerically tested
- finite-model tested
- empirically supported
- plausible but unverified
- falsified

Never collapse these evidence levels into one generic "correct" label.

## Physics challenge

Physics often includes modeling assumptions, approximations, empirical laws, coordinate conventions and regimes that do not map cleanly to theorem proving.

Therefore a physics verification layer should preserve both:

1. formal mathematical correctness
2. validity conditions of the physical model

## Long-term vision

A user can click a theorem/equation and inspect a provenance chain from informal source to semantic representation to formal proof certificate where one exists.
