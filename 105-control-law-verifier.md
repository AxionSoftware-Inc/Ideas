# Control-Law Verifier

## Thesis
Provide compiler-like diagnostics for controllers before deployment: stability assumptions, actuator limits, sampling constraints, robustness margins and model mismatch.

## Checks
- equilibrium and linearization validity
- pole/eigenvalue conditions
- Lyapunov or invariant evidence when available
- saturation and slew-rate limits
- discretization/sample-time compatibility
- delay/jitter sensitivity
- uncertainty margins

## Buyers
Robotics, drones, industrial automation, automotive controls.

## MVP
LTI/state-space + PID/LQR controllers with unit-aware plant models and deployment warnings.