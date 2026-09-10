# Paper → Benchmark / Regression-Suite Compiler

## Idea
Turn the quantitative claims of a scientific paper into an executable benchmark suite.

The system extracts:
- equations
- parameter values
- datasets
- tables / reported metrics
- figure curves
- experimental conditions
- claimed limits

Then generates tests such as:
```text
reproduce Figure 4 within tolerance
reproduce Table 2 metric
recover Eq. 17 limiting case
compare model A vs baseline B
```

## Material value
Labs, publishers and engineering teams can quickly determine whether a method actually reproduces and whether later code/model changes break published behavior.

## Strategic value
Every processed paper becomes machine-executable scientific data. It connects Literature→Executable Model, Reproducibility Capsules, Claim Auditor, Scientific CI and Model Registry.

## Differentiation
A paper summarizer outputs prose. This tool outputs tests.

## MVP
Start with papers that provide code/data and numerical tables. Generate a containerized regression suite plus a report stating which reported results were reproduced.