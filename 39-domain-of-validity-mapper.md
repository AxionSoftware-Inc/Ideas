# Domain-of-Validity Mapper

## Idea
Map the region of parameter/state space where a model is supported by evidence, where it is uncertain, and where using it is extrapolation.

## Output
For each query, return not only a prediction but a trust status:
```text
prediction: 83.2 C
status: AMBER
reason:
- temperature within calibration range
- pressure 18% above validated range
- geometry ratio outside training manifold
- conservation checks pass
```

The system also creates a multidimensional validity map from validation experiments, benchmark cases, physical constraints and uncertainty.

## Material value
Critical for safety, engineering QA, surrogate deployment and digital twins. Prevents teams from treating a numerically produced answer as automatically valid.

## Strategic value
Becomes a universal guardrail shared by Model Registry, Surrogate Compiler, Self-Healing Twin, AI Physics Firewall and Model Passport.

## Differentiation
Not just ML out-of-distribution detection. Combine empirical coverage, semantic regime assumptions, nondimensional groups, solver validation, physical constraints and uncertainty.

## MVP
Low-dimensional parameter models first. Ingest calibration/validation samples and declared assumptions, estimate supported region, flag extrapolation and generate a visual validity map.