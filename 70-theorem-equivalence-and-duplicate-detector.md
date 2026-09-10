# Theorem Equivalence & Duplicate Detector

## Problem
The same mathematical fact can appear with different notation, reordered hypotheses, changed variables, equivalent definitions, dual formulations, or a more general/special statement. Text or embedding search often misses exact mathematical equivalence.

## Product
Given two statements, classify:
- exact alpha-equivalent
- equivalent after normalization
- one strictly generalizes the other
- one is a corollary/special case
- dual/isomorphic formulation
- merely semantically related
- genuinely different

## Engine
Semantic IR + normalization + theorem retrieval + rewrite search + lightweight proof obligations + formal verification where available.

## Value
- removes duplicate work in formal libraries
- finds hidden prior art in papers
- improves theorem search dramatically
- helps library maintainers consolidate APIs
- supports novelty checking for conjectures

## Moat
A growing corpus of verified equivalence/generalization edges becomes high-value mathematical metadata unavailable from ordinary document search.
