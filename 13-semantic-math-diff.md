# Semantic Math Diff

## Core idea
Git diff for mathematics, physics and scientific models. Compare meaning rather than lines of LaTeX.

## Examples
Instead of showing many textual edits, report:
- parameter `c` renamed to `gamma`
- sign of potential term changed
- assumption changed from `m > 0` to `m >= 0`
- boundary condition changed from Dirichlet to Neumann
- equation algebraically equivalent; only notation changed
- model now includes an additional dissipative term
- unit changed from cm to m

## Why it matters
Scientific documents and models are currently versioned mostly as text/code. Formatting changes can hide scientifically important modifications.

## Product angle
GitHub/GitLab app, editor plugin, collaboration feature for papers, models and simulation projects.

## Strategic value
Requires the Semantic Scientific IR and therefore reinforces the ecosystem core. It also creates machine-readable model lineage useful for provenance, review and AI training.

## Monetization
Free individual extension; paid private repositories, review dashboards, institutional/on-prem version.

## MVP
LaTeX equations + semantic AST normalization. Detect algebraic equivalence, symbol renames, changed constants/assumptions and added/removed terms.