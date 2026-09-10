# Architecture & Product Roadmap

## Central architecture

```text
                  Scientific Workspace
                         |
                Semantic Scientific IR
                         |
       +-----------------+-----------------+
       |        |        |        |        |
     Editor   Debugger   CAS   Simulation  Search
       |        |        |        |        |
   Rendering  Units    Symbolic  Solvers  Knowledge Graph
                         |
                  Formal Verification
```

## Build vs integrate

Avoid rebuilding mature commodity layers unless there is a strong technical reason.

### Integrate initially

- LaTeX-compatible notation
- MathJax/KaTeX-style rendering
- symbolic algebra backends
- notebook concepts
- numerical solvers
- formal proof systems
- plotting/visualization

### Build as core IP

- semantic scientific IR
- scientific type system
- operator/domain/codomain model
- unit/dimension reasoning
- equation diagnostics
- derivation verification
- semantic normalization
- equation/theorem indexing
- backend orchestration
- evidence/provenance model
- scientific UX

## Suggested product sequence

### Phase 1 — Semantic equation core

Deliver:

- parser
- AST
- symbol table
- scientific types
- units/dimensions
- assumptions
- normalization

### Phase 2 — Equation Debugger

Deliver immediate user value with diagnostics and derivation checking.

### Phase 3 — Scientific Compiler

Add symbolic actions, code generation and backend abstraction.

### Phase 4 — Equation-to-Simulation

Connect validated models to numerical/simulation systems.

### Phase 5 — Semantic Search

Index equations, theorems and documents using normalized structures.

### Phase 6 — Scientific Document Ingestion

Turn papers/books into semantic corpora.

### Phase 7 — Formal Verification

Progressively connect suitable objects to Lean/formal proof infrastructure.

## Connection to operator-discovery systems

A semantic scientific IR naturally overlaps with operator-oriented mathematical engines. Domain/codomain constraints, composition, inverses, adjoints, commutators, normalization and proof certificates can all become reusable primitives rather than separate ad-hoc features.

That makes a scientific workspace potentially more than a front-end application: it can become an interface to deeper mathematical reasoning engines.
