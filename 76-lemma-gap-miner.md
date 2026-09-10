# Lemma Gap Miner

## Problem
Large proof developments repeatedly re-prove local facts because the right intermediate lemma is missing, hard to find, or never exposed as a reusable API.

## Product
Analyze proof corpora and identify high-value missing lemmas whose addition would shorten many proofs or unlock multiple stalled goals.

## Signals
- repeated tactic/proof fragments
- recurring subgoals
- expensive premise-search patterns
- duplicated local helper lemmas
- graph bottlenecks
- proof failures sharing the same unresolved shape

## Output
Ranked candidate lemmas with estimated reuse count, proof difficulty, affected files/theorems, and suggested formal statement.

## Value
This is profiler-guided optimization for a theorem library. It can reduce proof maintenance cost and improve automated prover success.

## Moat
Usage telemetry + proof-dependency graphs create a unique map of what mathematical abstractions are missing from a library.
