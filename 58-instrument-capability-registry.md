# Instrument Capability Registry / Lab Device ABI

## Goal
Create a machine-readable registry of laboratory instruments and their capabilities.

Each device describes:
- commands and parameters
- measurable quantities
- units, ranges and precision
- calibration state
- timing/throughput limits
- consumables
- safety constraints
- communication adapters
- maintenance status

## Why useful
Lab automation currently depends heavily on device-specific integrations. A capability registry allows software or agents to ask for a capability such as `dispense(volume=20 uL)` and discover compatible hardware.

## Business
Useful for lab integrators, pharma/biotech automation, instrument vendors and self-driving labs.

## Moat
Accumulated device adapters plus a stable semantic ABI can become infrastructure that makes higher-level protocol compilation possible.