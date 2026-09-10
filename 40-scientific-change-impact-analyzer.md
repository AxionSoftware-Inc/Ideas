# Scientific Change-Impact Analyzer

## Idea
When any scientific dependency changes — parameter, equation, dataset, assumption, paper, calibration, solver, material property — automatically identify which downstream results may no longer be valid.

## Example
```text
Changed: viscosity model v2 -> v3
Affected:
- 6 equations
- 2 calibrated parameters
- 4 simulation scenarios
- Figures 3, 7, 8
- Claim C12
- model-passport validation status
```

## Material value
Engineering organizations constantly revise models and data. Today impact analysis is often manual and risky. This product reduces revalidation work and prevents stale conclusions from surviving upstream changes.

## Strategic value
Turns the Scientific Provenance Graph into an active dependency system, similar to a build system for knowledge.

## Differentiation
Git finds changed files. This system finds changed **scientific meaning and evidence dependencies**.

## MVP
Track equations, parameters, datasets and outputs as a DAG. Changes mark downstream nodes stale; Scientific CI reruns only affected verification tasks.