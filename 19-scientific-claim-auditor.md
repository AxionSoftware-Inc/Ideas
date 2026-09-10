# Scientific Claim Auditor

## Core idea
Given a paper, report or model, identify each major quantitative/scientific claim and trace whether the supplied equations, data, code and assumptions actually support it.

## Checks
- claim has a derivation or computational path
- cited equation is valid under stated assumptions
- units and numerical substitutions are consistent
- plots/tables can be regenerated from declared inputs
- statistical/uncertainty claims match the analysis
- hidden or contradictory assumptions
- conclusions that depend on fragile parameter choices
- stale claims after model/data changes

## Important boundary
This is not an AI 'truth detector'. It audits internal support, reproducibility and consistency; external scientific truth still requires evidence and expert judgment.

## Buyers
Publishers, reviewers, universities, regulated R&D, internal engineering/science teams and scientific-AI developers.

## Monetization
Per-document audit, institutional review workflow, journal integration and private enterprise deployment.

## Strategic value
Combines Semantic IR, provenance graph, model testbench, reproducibility capsule and uncertainty engine into one high-value workflow.

## MVP
Start with computational papers where code/data are available. Extract 5-20 quantitative claims and verify traceability to reproducible computations and equations.