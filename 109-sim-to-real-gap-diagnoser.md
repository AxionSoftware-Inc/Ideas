# Sim-to-Real Gap Diagnoser

## Thesis
When a robot behaves differently in reality than in simulation, identify which assumptions or model components most likely explain the gap.

## Inputs
simulation traces, real logs, model parameters, sensor/actuator specs, environment metadata.

## Outputs
- ranked mismatch causes
- timing/latency discrepancies
- unmodeled friction/compliance
- sensor bias/noise drift
- actuator saturation
- contact-model mismatch
- recommended calibration experiments

## Buyers
Robotics, autonomy, digital-twin teams.

## MVP
Mobile robot or manipulator with replayable sim/real logs and automated residual decomposition.