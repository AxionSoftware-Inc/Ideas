# Theorem Query Planner

## Problem
A hard theorem request often needs multiple search modes: natural-language retrieval, type-pattern search, dependency expansion, definition unfolding, premise set retrieval and local goal-state search.

## Product
Plan theorem retrieval as a query-optimization problem rather than issuing one embedding search.

## Planner actions
- normalize the requested statement
- identify mathematical entities and structures
- choose semantic vs type-aware vs graph search
- expand definitions selectively
- retrieve premise groups rather than isolated lemmas
- use dependency neighborhoods
- stop when the expected marginal value of more retrieval falls below cost

## Value
Improves prover success while reducing context/token/search cost. Useful for AI theorem provers and IDE assistants.

## Strategic role
Database-style query optimization for mathematical knowledge. It can route across TheoremGraph-like indexes, Mathlib search, local project proofs and proprietary theorem registries.
