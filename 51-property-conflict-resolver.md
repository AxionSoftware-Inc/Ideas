# Property Conflict Resolver / Scientific Consensus Engine

## Problem
Scientific sources often report different values for the same quantity because conditions, methods, samples and conventions differ.

## Product
Given conflicting values, automatically determine whether they are:
- genuinely contradictory
- measured in different regimes
- using different conventions or definitions
- affected by sample/process differences
- statistically compatible

Output a consensus distribution rather than a naive average.

## Example
```text
Property: thermal conductivity of material X
Reported: 122, 147, 151, 205 W/mK

Result:
- 122 belongs to phase B
- 205 measured at 80 K
- 147 and 151 are compatible at 300 K
Recommended 300 K value: 149 ± 6 W/mK
```

## Value
Useful for simulation parameter selection, standards work, materials databases, literature review and safety-critical engineering.