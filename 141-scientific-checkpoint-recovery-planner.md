# Scientific Checkpoint & Recovery Planner

## Thesis
Choose checkpoint, caching and restart strategies based on the semantic structure and cost of a scientific workflow.

## Consider
- deterministic vs stochastic stages
- expensive intermediate states
- solver restart capability
- cloud/preemptible failure risk
- dataset transfer cost
- reproducibility requirements

## Value
Prevent a failed long-running job from invalidating or repeating days of expensive compute.

## Buyers
HPC/cloud scientific computing teams.

## MVP
Workflow DAG -> checkpoint placement and reusable intermediate-cache plan.