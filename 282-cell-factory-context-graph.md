# Cell Factory Context Graph

## Idea
Represent an engineered strain as more than a genome edit list. Link genotype, pathway edits, host state, medium, induction, growth phase, reactor regime, measured phenotype and evidence.

## Why it matters
The same genetic design can behave differently under different biological and process contexts. A context graph prevents results from being reused outside their evidence domain.

## Capabilities
- identity resolution for strains and constructs
- genotype -> pathway -> phenotype dependencies
- condition-specific evidence
- provenance for measurements
- conflict detection across studies
- transferability queries

## Strategic value
This can become the semantic identity layer beneath bioprocess twins, DBTL automation and biological model registries.

## MVP
E. coli production strains, common pathway edits and fermentation metadata.