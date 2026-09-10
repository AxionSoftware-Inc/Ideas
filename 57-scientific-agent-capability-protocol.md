# Scientific Agent Capability Protocol

## Thesis
Define a standard typed protocol through which AI agents can discover and safely use scientific tools.

A tool should advertise more than a function name. It should expose:
- physical inputs and outputs
- units and dimensions
- valid ranges
- uncertainty behavior
- side effects and hazards
- cost and estimated runtime
- deterministic vs stochastic behavior
- required calibration or environment

## Example capability
```text
measure_temperature(sample)
input: SampleRef
output: Temperature[K] ± uncertainty
range: 20..1200 K
side_effect: none
cost: low
```

## Value
Scientific agents become portable across simulation engines, databases and laboratories without hard-coded integrations.

## Strategic value
Potentially a scientific equivalent of a universal agent/tool ABI, built around physical semantics rather than generic JSON calls.