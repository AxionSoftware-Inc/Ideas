# Proof Strategy Atlas

## Thesis
Proof libraries store finished proofs, but they rarely expose reusable proof strategy as a first-class asset.

## Product
Extract and index strategy patterns such as:
- induction over which object and why
- contradiction pivots
- compactness reductions
- normalization chains
- invariant introduction
- extremal argument structure
- change of representation
- local-to-global bridges
- finite-model or approximation reductions

## Search
Ask: `How are statements of this structural type usually proved?` and retrieve proof plans before retrieving exact lemmas.

## Value
Improves human onboarding, automated proving, theorem transfer across domains and proof explanation.

## Moat
A strategy graph is more abstract and transferable than a theorem corpus. Over time it can support proof planning independent of notation and even independent of a specific prover.
