# Scientific Compiler

## Vision

A formula should behave like executable scientific source code.

The editor displays familiar mathematical notation, while internally the expression is typed, normalized and linked to computational and verification backends.

## Actions on an expression

Possible context actions:

- simplify
- expand/factor
- differentiate
- integrate
- solve
- inspect units
- inspect dimensions
- inspect assumptions
- infer domains
- verify transformation
- plot
- simulate
- convert notation
- generate Python
- generate Julia
- generate C++
- generate Lean
- find equivalent formulas
- find related theorems
- explain derivation

## Compiler stages

```text
Source notation
   -> parser
   -> semantic AST
   -> type/unit/domain checking
   -> normalization
   -> optimization / symbolic transformations
   -> target lowering
   -> backend
```

Possible backends:

```text
rendering
CAS
numerical solver
simulation
code generation
formal proof
search/indexing
knowledge graph
```

## Scientific IR

The most valuable component may be the intermediate representation shared by every backend.

This IR should understand more than syntax:

- operators
- domains/codomains
- tensors
- units/dimensions
- assumptions
- regimes
- frames
- constraints
- uncertainty/evidence level
- derivation provenance

## AI role

AI is useful for:

- interpreting prose
- resolving ambiguous notation
- proposing mappings
- explaining errors
- suggesting transformations

But deterministic components should perform type checking, normalization, proof checking and numerical execution wherever possible.
