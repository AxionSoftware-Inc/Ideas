# BIM Boundary-Condition Extractor

## Thesis
Automatically infer candidate simulation boundary conditions from BIM topology, object semantics, location and engineering intent.

## Examples
- exterior wall -> ambient thermal boundary
- room adjacency -> internal interface
- window -> glazing/radiation boundary
- support/connection metadata -> structural constraints
- inlet/outlet equipment -> fluid boundary candidates

## Safety model
Never silently guess. Classify each boundary as explicit, inferred, ambiguous or missing and require evidence for high-impact assumptions.

## Buyers
CAE/BIM integrators and engineering teams.

## MVP
Thermal envelope boundary inference with confidence/evidence labels.