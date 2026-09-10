# Formalization Faithfulness Auditor

## Problem
A formal statement can compile while misrepresenting the intended informal mathematics: missing hypotheses, wrong domains, vacuous assumptions, changed quantifiers, or silently strengthened/weakened claims.

## Product
Compare an informal theorem/proof against its Lean/Isabelle/Coq formalization and report semantic mismatches.

## Checks
- variable and domain alignment
- quantifier polarity/order
- missing or extra assumptions
- hidden nonemptiness/positivity conditions
- vacuity detection
- conclusion strength comparison
- definition alignment
- proof-claim fidelity

## Output
A machine-readable fidelity certificate with confidence and concrete mismatch witnesses.

## Value
This becomes QA for autoformalization pipelines, formal-math datasets, AI-generated proofs, publishers and research groups.

## Strategic role
Compilation proves syntactic/formal validity, not faithful translation. Owning the fidelity layer is a stronger moat than owning another theorem prover front end.
