# Telemetry-to-Model Discrepancy Diagnoser

## Idea
When spacecraft or space-robot telemetry diverges from expected behavior, rank candidate causes instead of merely raising anomalies.

## Inputs
- telemetry streams
- subsystem models
- command history
- environment estimates
- calibration state
- configuration versions

## Outputs
- likely missing physics or degraded component
- sensor bias vs true state change
- parameter drift
- cross-subsystem causal paths
- recommended discriminating maneuver/test

## Buyers
Mission operations, satellite fleets and space robotics teams.

## Moat
Physics-aware diagnosis tied to model provenance and operational context.