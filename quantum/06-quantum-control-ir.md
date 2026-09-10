# Hardware-Neutral Quantum Control IR

## Problem

Circuit-level SDKs abstract away the physical control layer, while pulse/control interfaces are often hardware-specific. This makes control research, portability and hardware/software co-design difficult.

## Product

A hardware-neutral intermediate representation between logical/circuit operations and device-specific pulse/control backends.

Pipeline:

`circuit/QIR -> control IR -> scheduling/calibration bindings -> hardware backend`

## Core capabilities

- explicit timing, phase, frequency and amplitude semantics
- measurement/readout operations
- calibration references
- hardware constraints
- pulse/control scheduling
- backend lowering
- static validation
- round-trip serialization
- simulator/digital-twin target
- reproducible control programs

## Buyers

Quantum control vendors, QPU companies, research labs, compiler teams and digital-twin/simulation tool vendors.

## Why it can matter

A portable control representation could reduce vendor lock-in and provide a common target for compilers, simulators, digital twins and control hardware.

## Risks

This is physics-heavy, standardization-sensitive and can fail if vendors refuse to expose low-level control. It should therefore remain below the first three priorities until a concrete integration partner or strong open hardware target exists.

## MVP

Define a minimal IR around one hardware family, build a validator and simulator backend, then prove that two different control backends can consume the same semantic program.
