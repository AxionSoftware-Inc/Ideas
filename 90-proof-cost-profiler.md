# Proof Cost Profiler

## Problem
Formal proof projects know whether a proof passes, but often not why it is expensive in elaboration, search, maintenance or human effort.

## Product
Profile theorem proving like software performance profiling.

## Metrics
- elaboration/checking time
- tactic/search branching
- premise retrieval cost
- dependency fan-in/fan-out
- proof fragility under library changes
- repeated normalization/rewrite patterns
- memory footprint
- generated-term size

## Output
Hotspot map plus recommendations: extract lemma, replace tactic, cache normalization, reduce imports, strengthen API, or change representation.

## Value
AI-math labs and large formal verification teams can reduce compute and maintenance cost. It also helps prioritize which library abstractions to improve.

## Strategic role
Feeds Lemma Gap Miner, Incremental Proof Build System and Proof Repair Engine.
