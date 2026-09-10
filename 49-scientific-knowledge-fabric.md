# Scientific Knowledge Fabric

## Thesis
Build a machine-actionable knowledge layer that links papers, equations, claims, datasets, experiments, models, assumptions, implementations and validation evidence.

## Why it matters
Search engines return documents. A scientific knowledge fabric should return structured scientific objects and their dependencies.

Example:

```text
Claim -> Figure -> Dataset -> Model -> Equation -> Assumptions -> Paper
```

A user should be able to ask: "Which equations support this claim?", "Which results depend on this constant?", or "Which papers disagree about this property?"

## Product value
- cross-paper reasoning without flattening everything into text
- machine-actionable RAG for scientific agents
- impact analysis when a result or assumption changes
- foundation for evidence-weighted scientific search

## Moat
The graph becomes proprietary infrastructure: not just documents, but normalized scientific relationships accumulated over time.