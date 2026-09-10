# Scientific Entity Resolver

## Problem
The same scientific object appears under different symbols, names, units, conventions and local definitions across papers and software.

Examples:
- `k`, `κ`, `lambda` may all denote thermal conductivity
- the same tensor may use different index conventions
- a parameter name may silently change meaning between papers

## Product
Resolve symbols and terms into stable semantic identities using context, units, equations, definitions and domain ontology.

## Output
```text
Paper A: κ -> thermal_conductivity
Paper B: k_th -> thermal_conductivity
Code C: lambda -> thermal_conductivity
Confidence: 0.997
```

## Value
This is foundational infrastructure for literature-to-model compilation, semantic search, knowledge graphs, data integration and AI agents.