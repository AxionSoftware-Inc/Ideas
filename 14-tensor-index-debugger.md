# Tensor / Index / Convention Debugger

## Core idea
A specialized debugger for tensor-heavy mathematics and physics: general relativity, continuum mechanics, field theory, differential geometry and related domains.

## Checks
- free vs dummy index mismatches
- illegal repeated indices
- covariant/contravariant type errors
- metric/signature assumptions
- coordinate-system consistency
- symmetry/antisymmetry constraints
- contraction compatibility
- tensor rank/type mismatches
- unit/dimension consistency
- convention conflicts between sources

## Example
If an expression has a free index on one side and a contracted index on the other, flag the exact subexpression and suggest valid repairs.

## Product angle
Narrower market than a general equation debugger, but high-value users and relatively weak mainstream UX make it an attractive specialist product.

## Buyers
GR/QFT researchers, computational mechanics, relativity groups, advanced students and scientific software teams.

## Strategic value
Builds a rigorous typed tensor layer for the wider Semantic Scientific IR.

## MVP
Einstein notation parser, tensor rank/variance type system, metric handling, symmetry metadata and diagnostic messages.