# AEC Physics Regression CI

## Thesis
Treat building-model changes like software changes: automatically rerun affected engineering checks and detect physics regressions.

## Example
A window area changes by 18%:
- rerun affected thermal zones
- recompute solar gains
- flag HVAC sizing impact
- compare energy/load deltas
- identify stale reports

## Key idea
Use semantic change-impact analysis to avoid rerunning every expensive simulation.

## Buyers
AEC engineering teams and digital delivery platforms.

## MVP
IFC diff -> dependency analysis -> selective thermal regression checks.