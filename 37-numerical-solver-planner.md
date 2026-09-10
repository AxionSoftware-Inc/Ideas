# Numerical Solver Planner / Compiler

## Idea
Given equations plus domain, boundary conditions, scales and accuracy requirements, recommend and configure a numerical solution strategy rather than forcing the user to choose solvers manually.

## Planner reasons about
- ODE/PDE/DAE/stiffness class
- conservation structure
- elliptic/parabolic/hyperbolic character
- discontinuities/shocks
- geometry and boundary conditions
- target error and runtime
- CPU/GPU hardware
- mesh/time-step needs
- stability constraints

## Output
```text
Problem: transient advection-diffusion, high Peclet number
Recommended:
- finite volume / stabilized FEM
- adaptive mesh near front
- implicit diffusion step
- CFL constraint for transport
- convergence verification plan
```

## Material value
Solver selection and tuning require specialist knowledge. Wrong choices waste compute or create plausible but incorrect results.

## Strategic value
Turns Equation→Simulation into a much more autonomous compiler and creates a bridge to external solver ecosystems rather than replacing them.

## Differentiation
Not a solver library. It is a semantic planning/verification layer that selects, configures and validates existing solvers.

## MVP
ODE systems first: classify stiffness, detect conserved quantities, choose explicit/implicit methods, set tolerances, compare candidate solvers and produce convergence evidence. Expand to PDE families later.