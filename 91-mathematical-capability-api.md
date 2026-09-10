# Mathematical Capability API

## Thesis
Scientific agents should query mathematical capabilities through typed contracts instead of hard-coding library names or tool-specific syntax.

## Example questions
- can this backend simplify rational functions exactly?
- does it support distributions on manifolds?
- can it prove linear-arithmetic goals?
- can this object compute an adjoint numerically or symbolically?

## Product
A common capability schema describing supported objects, operations, domains, guarantees, complexity hints, exactness, assumptions and proof/certificate types.

## Value
Lets agents route tasks among Lean, SymPy, Sage, SMT solvers, numerical libraries and proprietary engines safely.

## Strategic role
This is an API-discovery layer for mathematical computation, analogous to hardware capability negotiation. It can become part of the Scientific Agent Capability Protocol.

## Moat
As adapters accumulate, the platform becomes the routing fabric across otherwise incompatible scientific tools.
