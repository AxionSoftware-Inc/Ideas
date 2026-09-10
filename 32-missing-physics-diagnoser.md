# Missing Physics Diagnoser

## Idea
When experiment/sensor data and a model disagree, diagnose *why* instead of only reporting residual error.

Candidate causes:
- wrong parameter
- sensor bias/noise
- missing forcing term
- neglected nonlinear effect
- incorrect boundary condition
- omitted coupling
- time delay
- wrong regime/model form

## Workflow
```text
model + measurements
 -> residual structure
 -> sensitivity / identifiability analysis
 -> candidate discrepancy models
 -> physical constraint checks
 -> ranked explanations + proposed experiments
```

## Why it matters
Model-measurement discrepancy is unavoidable in engineering. Existing research shows value in learning systematic residuals and identifying missing dynamics; digital-twin work also uses discrepancy diagnosis to decide when models require updating.

## Material value
Root-cause analysis for digital twins, predictive maintenance, calibration and simulation validation. Reduces expert debugging time and prevents blind parameter fitting from hiding model-form errors.

## Strategic value
Connects Inverse Problem Studio, Governing Equation Discovery, Experiment Design and Self-Healing Digital Twin.

## Differentiation
Do not simply fit residuals with ML. Produce interpretable physical hypotheses and tests that can falsify them.

## MVP
ODE systems + time-series measurements. Separate parameter error, additive bias and candidate missing terms; rank candidates using fit improvement, complexity and physical admissibility.