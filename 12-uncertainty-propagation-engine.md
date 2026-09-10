# Uncertainty Propagation Engine

## Core idea
Make uncertainty a first-class property of every scientific variable and automatically propagate it through formulas, solvers and simulations.

A variable is not only `x = 2.4 m`; it may be `x = 2.4 ± 0.03 m`, a probability distribution, interval, covariance-aware vector, or model uncertainty object.

## Capabilities
- measurement uncertainty propagation
- covariance/correlation handling
- Monte Carlo propagation
- linearized/automatic-differentiation propagation
- interval arithmetic
- polynomial chaos / surrogate methods
- sensitivity ranking: which input dominates output uncertainty?
- uncertainty-aware plots and reports

## Example
Given uncertain material properties and loads, return the distribution of stress/failure probability instead of one deterministic number.

## Product angle
Engineering, metrology, quality assurance, simulation and regulated R&D all need defensible uncertainty reports.

## Strategic value
Because uncertainty lives inside the same Semantic Scientific Object model, every equation, simulation and fitted parameter becomes uncertainty-aware automatically.

## Monetization
Professional desktop/SaaS tool; enterprise reporting and audit features; domain-specific templates.

## MVP
Scalar/vector equations + covariance, Monte Carlo, first-order propagation, sensitivity chart and reproducible report export.