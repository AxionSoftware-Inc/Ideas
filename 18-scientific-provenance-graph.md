# Scientific Provenance Graph

## Core idea
Every scientific result should answer: where did this equation, number, plot or conclusion come from?

Represent dependencies as a graph:
source → definition → assumption → equation → transformation → parameter/data → simulation → plot → claim.

## User experience
Click any equation/number/plot and inspect its complete ancestry and downstream impact.

If an assumption, dataset or parameter changes, automatically show which equations, simulations, figures and claims become stale.

## Capabilities
- source/citation provenance
- equation derivation lineage
- data lineage
- parameter/version lineage
- impact analysis
- dependency visualization
- stale-result detection
- signed/verifiable transformation records

## Product angle
This is more strategic infrastructure than standalone UI. It can power paper review, reproducibility, team collaboration, semantic diff and AI scientific assistants.

## Monetization
Enterprise knowledge graph, lab/team collaboration, publisher review infrastructure and regulated/audited R&D.

## Moat
The provenance graph becomes an accumulating map of verified scientific relationships, not merely a document store.

## MVP
Track variables/equations/transformations/data/plots inside one project and support `why is this here?` plus `what breaks if I change this?` queries.