# Experiment Preflight Simulator / Safety Sandbox

## Goal
Run an experimental protocol through a digital preflight before real hardware executes it.

Checks can include:
- impossible instrument commands
- timing conflicts
- unsafe temperature/pressure/voltage ranges
- reagent or material compatibility rules
- resource and consumable shortages
- expected measurement saturation
- collision/deadlock risks in robotic workflows

## Output
```text
PREFLIGHT FAILED
Step 18: requested 125 C exceeds vessel rating 110 C
Step 27: detector expected to saturate
Suggested fixes available
```

## Value
Prevents wasted experiments, equipment damage and unsafe autonomous-agent actions.

## Business
A safety and reliability layer for self-driving laboratories and automated test facilities.