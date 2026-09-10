# Semantic Scientific Build Cache

## Thesis
Reuse previous scientific results only when the semantic dependencies that make them valid have not changed.

## Cache key
Not just file hash. Include model version, equations, parameters, units, assumptions, solver settings, dependency versions, relevant geometry and validity regime.

## Benefit
Skip expensive recomputation safely while invalidating results when a scientifically meaningful dependency changes.

## Buyers
Simulation platforms, HPC workflows, digital twins, optimization systems.

## Strategic fit
Scientific Lockfile + Change-Impact Analyzer + Compute Broker + CI/CD become a complete scientific build system.