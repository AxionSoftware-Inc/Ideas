# Biological Model Validity & Drift Monitor

## Problem
Biological systems adapt, mutate and shift; a calibrated model can silently become stale.

## Product
Monitor residuals, phenotype changes, sensor shifts and process context to determine whether a biological/process twin remains valid.

## Status
`GREEN: calibrated regime`
`AMBER: drift detected, predictions widened`
`RED: model no longer admissible for control`

## Actions
- identify likely drift source
- recommend recalibration data
- distinguish sensor drift from biology drift
- preserve old/new model provenance

## MVP
Fermentation growth/production model with online residual monitoring.