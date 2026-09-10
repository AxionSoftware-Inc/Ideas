# Measurement Procedure Compiler

## Core idea
Turn a measurement requirement into an executable, versioned procedure with instrument requirements, calibration constraints, environment, sampling plan, uncertainty target and acceptance logic.

## Workflow
`required measurand + tolerance + confidence + available instruments -> procedure -> preflight -> execution -> trust passport`.

The compiler should identify missing capability before testing starts, generate operator/robot instructions, bind instrument identities, calculate the expected uncertainty budget and record provenance during execution.

## Buyers
Test labs, calibration labs, manufacturing inspection, R&D labs and autonomous laboratories.

## Strategic value
This closes the loop between Standards-to-Tests Compiler, Instrument Capability Registry, DCCs and Measurement Trust Passports. A measurement method becomes executable infrastructure rather than a PDF SOP.