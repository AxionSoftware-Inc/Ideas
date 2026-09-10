# Semantic Equation & Theorem Search

## Problem

Scientific knowledge is difficult to search because equivalent mathematics can be written using different notation, symbol names and algebraic forms.

A text search may fail to recognize that two expressions are structurally the same.

## Idea

Create search over normalized semantic mathematical objects rather than only text strings.

## Search modes

- exact structural search
- alpha-renamed variable search
- algebraically equivalent expression search
- operator-pattern search
- theorem hypothesis/conclusion search
- dimension/type-aware search
- physical-regime-aware search
- equation family search
- derivation predecessor/successor search

## Example

A query involving a commutator should discover equivalent representations even when another document expands the commutator explicitly or uses different symbol names.

## Search results can include

- equations
- identities
- theorems
- proofs
- derivations
- physical laws
- papers
- book sections
- simulations
- code implementations

## Knowledge graph

Each semantic object can be connected through relationships such as:

```text
is_equivalent_to
is_special_case_of
is_generalization_of
is_derived_from
requires_assumption
used_in
contradicts_under_regime
implemented_by
verified_by
```

This becomes a scientific knowledge graph rather than a document-only search engine.
