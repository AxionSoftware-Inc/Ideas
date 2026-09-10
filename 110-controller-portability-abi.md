# Controller Portability ABI

## Thesis
Define a typed interface between controllers, plant models, estimators, sensors and actuators so control logic can move across simulators and hardware with explicit compatibility checks.

## Interface metadata
- signal meaning and units
- coordinate/frame conventions
- sample rates and latency budgets
- actuator limits
- uncertainty
- required state estimates
- safety invariants

## Product value
Reduce fragile glue code between simulation, ROS-like middleware, embedded targets and digital twins.

## Buyers
Robotics platforms, industrial automation, simulation vendors.