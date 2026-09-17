# Nuclear Sensor Degradation & Virtual Sensor Assurance

## Idea
Detect sensor degradation and safely substitute or supplement failing instrumentation using physics-grounded virtual sensors.

## Engine
`redundant sensors + plant model + historical calibration -> consistency tests -> degradation probability -> virtual estimate + uncertainty`

## Requirements
- never hide observability loss
- quantify uncertainty after sensor loss
- separate sensor fault from plant anomaly
- preserve calibration traceability

## Value
Supports condition monitoring, maintenance planning and resilient digital twins.

## MVP
Thermal transient instrumentation with simulated sensor bias/dropout.