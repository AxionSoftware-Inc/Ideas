# Optimal Experiment Design Engine

## Core idea
Given a model, unknown parameters, current uncertainty and practical constraints, recommend the next experiment or measurement that will produce the most useful information.

## Example
A battery model contains five uncertain parameters. Instead of collecting arbitrary data, the engine recommends voltage/current profiles, temperatures and sampling times that maximize parameter identifiability while respecting equipment limits.

## Capabilities
- parameter identifiability analysis
- information-gain objectives
- model discrimination
- observation-time optimization
- sensor placement
- robust design under parameter uncertainty/noise
- cost/time/safety constraints
- sequential design: update after each experiment

## Why it matters
Experiments are expensive. Reducing the number of experiments needed to identify a model has direct monetary value.

## Buyers
Battery/energy, biotech/pharma, chemistry, materials, control systems, university and industrial labs.

## Monetization
High-value B2B/on-prem software or project-based optimization service. Pricing can be tied to saved experimental time/cost rather than user seats.

## Strategic value
Closes the loop:
model → simulation → uncertainty → choose experiment → collect data → parameter inference → improved model.

## MVP
ODE models with continuous/discrete design variables, Fisher-information or sensitivity-based objectives, practical bounds and a clear experiment recommendation report.