# Semantic Scientific Objects

## Idea

A formula such as

```text
F = m a
```

should not be stored only as a visual string. It should be represented as a structured scientific object.

For example:

- `F` is a force vector.
- `m` is a positive scalar mass.
- `a` is an acceleration vector.
- The expression belongs to Newtonian mechanics under an explicit regime.
- Units and dimensions are attached to symbols.
- Coordinate frame and reference frame can be attached when relevant.
- Assumptions are explicit rather than hidden in prose.
- Relationships to equivalent or derived equations are machine-readable.
- Provenance can record where the equation came from.

## Difference from ordinary LaTeX

LaTeX answers: "How should this expression be written?"

A semantic scientific object answers: "What does this expression mean, what are its types and assumptions, and what operations are valid on it?"

## Analogy to programming

This is closer to an Abstract Syntax Tree + type system + symbol table than to autocomplete.

A programming language compiler does not see `x + y` merely as three visible characters. It knows what `x` and `y` are, their types, scopes and valid operations.

A scientific system should treat equations similarly.

## What this unlocks

A semantic equation can become the common source for:

- LaTeX/MathJax rendering
- dimensional analysis
- symbolic manipulation
- equation diagnostics
- numerical solvers
- plotting and animation
- simulation
- code generation
- theorem search
- formal verification
- conversion between notations
- knowledge graphs
- AI reasoning with explicit constraints

## Minimal internal representation

Possible fields:

```text
Expression
  AST
  symbols[]
  operators[]
  types[]
  units[]
  dimensions[]
  domains[]
  codomains[]
  assumptions[]
  coordinate_frame
  physical_regime
  boundary_conditions[]
  initial_conditions[]
  provenance[]
  relationships[]
```

This semantic IR should be the center of the larger scientific ecosystem.
