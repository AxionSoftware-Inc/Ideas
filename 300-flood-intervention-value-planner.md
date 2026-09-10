# Flood Intervention Value Planner

## Goal
Convert uncertain flood scenarios into ranked interventions based on avoided loss, confidence and implementation cost.

## Candidates
Retention, drainage upgrades, barriers, pumping, land-use changes, warning systems and monitoring.

## Engine
`hazard ensemble + exposure + vulnerability + intervention model + cost -> expected value / robustness`

## Output
- benefit distribution, not single number
- scenarios where intervention fails
- option value of delaying/monitoring
- portfolio under budget

## MVP
Urban catchment with a small intervention set.