# Material-to-Design Compiler

## Thesis
Compile engineering requirements into ranked material candidates with explicit trade-offs and evidence.

Input:
```text
max temperature: 450 C
minimum yield strength: 600 MPa
mass priority: high
corrosion: marine environment
manufacturing: CNC + welding
budget: constrained
```

Output:
- feasible material candidates
- rejected candidates and reasons
- uncertainty and missing data
- manufacturability constraints
- simulation-ready property sets
- cost/performance trade-off frontier

## Difference from a material selector
This is not a filter over a catalog. It reasons over regime-dependent properties, process history, uncertainty, standards and design constraints.

## Business
High-value for mechanical design, aerospace, energy, robotics, automotive and manufacturing procurement.