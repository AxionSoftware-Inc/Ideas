# Scientific Compute Broker

## Thesis
Route scientific workloads across local CPU/GPU, clusters, national HPC and cloud based on real solver performance, queue time, price, energy, data locality and reproducibility constraints.

## Inputs
workflow DAG, solver/container, dataset size, precision target, deadline, budget, available resources.

## Outputs
- execution placement plan
- predicted runtime/cost range
- data-transfer overhead
- checkpoint strategy
- fallback resources

## Buyers
Labs, universities, simulation teams, AI-for-science platforms.

## Moat
Scientific workload semantics, not generic VM scheduling.