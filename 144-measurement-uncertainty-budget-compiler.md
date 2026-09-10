# Measurement Uncertainty Budget Compiler

## Core idea
Compile a measurement procedure, instrument chain, calibration data, environment and correlations into a transparent uncertainty budget with sensitivity ranking and decision margins.

## Product behavior
Input a measurement workflow rather than manually building spreadsheets. The compiler identifies uncertainty sources, units, distributions, correlations and transformations, then computes uncertainty through analytic, interval or Monte Carlo methods as appropriate.

It should also answer:
- Which uncertainty source dominates?
- Which calibration or sensor upgrade would reduce total uncertainty most?
- Is the measurement capability sufficient for the required tolerance?
- How much decision risk comes from measurement uncertainty?

## Buyers
Metrology labs, quality engineering, manufacturing, test labs, instrumentation companies.

## Moat
Couple semantic equations, DCC data, provenance and optimization. The long-term value is not the calculator but a reusable machine-readable uncertainty model attached to every scientific/industrial measurement.