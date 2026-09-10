# Protocol-to-Hardware Transpiler

## Thesis
Compile an abstract experimental protocol into device-specific executable instructions.

Input:
```text
mix A and B at 1:3 ratio
heat to 80 C for 20 min
measure absorbance every 30 s
```

Compiler stages:
1. resolve required capabilities
2. select available instruments
3. map semantic operations to device commands
4. insert calibration and synchronization steps
5. validate ranges and safety constraints
6. emit executable workflow plus provenance

## Why valuable
A protocol should be portable across laboratories instead of being tightly coupled to one vendor's hardware.

## Business
Lab automation vendors, pharma, biotech, chemistry and materials R&D.

## Strategic value
Combines the Scientific Agent Protocol, Instrument Capability Registry and Autonomous Lab Protocol Compiler into deployable infrastructure.