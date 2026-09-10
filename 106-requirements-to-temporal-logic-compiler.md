# Requirements-to-Temporal-Logic Compiler

## Thesis
Translate engineering safety/behavior requirements into machine-checkable temporal properties while preserving traceability to the original requirement.

## Example
"If obstacle distance falls below 0.5 m, the robot must stop within 200 ms" -> formal property + units + timing semantics + monitored signals.

## Critical feature
Generate ambiguity warnings rather than inventing missing semantics.

## Buyers
Robotics, autonomous systems, industrial control, certification teams.

## MVP
Restricted requirement grammar -> temporal logic/runtime monitors for ROS-style signals.