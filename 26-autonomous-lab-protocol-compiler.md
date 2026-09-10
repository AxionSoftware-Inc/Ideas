# Autonomous Lab Protocol Compiler

## Idea
Compile a scientific experiment specification into a machine-executable laboratory workflow with safety constraints, provenance and hardware adapters.

Input can be equations, protocol text, target variables and constraints. Output is a structured experiment graph that can run on supported instruments/robots or generate a human checklist when automation is unavailable.

## Example
```text
Goal: characterize reaction rate vs temperature
Constraints: 20-80 C, max pressure 2 bar
Replicates: 5

Compiler ->
prepare -> calibrate -> heat -> dose -> measure -> clean -> repeat
```

## Why now
2026 self-driving-laboratory reviews identify interoperability, generalizability, orchestration, safety and provenance-complete experimentation as major requirements for the next generation of autonomous labs.

## Material value
Labs spend heavily on custom integration between instruments, scripts and data systems. A protocol compiler can sell to chemistry/materials labs, biotech automation groups and instrument vendors.

## Strategic moat
It closes the loop between Optimal Experiment Design and physical execution: software can propose the highest-value next experiment and compile it into a reproducible protocol.

## Safety principle
Never allow unconstrained AI text to directly command hardware. Use typed operations, device capability schemas, parameter limits, approval gates and execution-time interlocks.

## MVP
Start hardware-light: compile protocols into a vendor-neutral DAG + provenance log + human-readable run sheet. Add adapters for a small set of common instruments later.