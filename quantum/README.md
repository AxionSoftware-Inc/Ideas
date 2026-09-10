# Quantum Software Opportunities

Purpose: track quantum-software ideas that have a clear strategic or commercial use, remain technically incomplete or fragmented, and do not require waiting for a fully fault-tolerant quantum computer before they can become useful.

## Selection rules

A project belongs here only if most of the following are true:

- The problem exists today or is becoming unavoidable.
- Current solutions are incomplete, vendor-locked, fragmented, research-grade, or expensive to integrate.
- There is a clear buyer: quantum hardware company, cloud provider, enterprise, government, research lab, HPC center, security team, or tool vendor.
- Better software can create a measurable advantage in cost, reliability, validation, portability, or time-to-result.
- The project can begin with simulators, public hardware backends, traces, calibration data, or classical infrastructure.
- The value grows as quantum hardware improves.

## Priority ideas

1. `01-resource-economics-feasibility-engine.md` — hardware-aware quantum resource, cost, time, energy and feasibility analysis.
2. `02-qec-engineering-benchmark-platform.md` — error-correction experiment, decoder benchmarking and certification workbench.
3. `03-quantum-hardware-digital-twin.md` — calibration-aware digital twin for QPU behavior and control experiments.
4. `04-quantum-hpc-orchestrator.md` — vendor-neutral hybrid CPU/GPU/QPU scheduling and execution layer.
5. `05-quantum-compiler-verification.md` — semantic/equivalence validation and resource-regression testing for quantum compilers.
6. `06-quantum-control-ir.md` — hardware-neutral intermediate representation between circuits and physical pulse/control systems.

## Ideas deliberately excluded for now

- Another generic quantum SDK.
- Another visual circuit editor.
- Another basic state-vector simulator.
- A new quantum programming language without a strong infrastructure advantage.
- Consumer-facing quantum apps whose value depends on hardware that does not yet exist.
- Pure education products without a strategic or commercial moat.

## Current market signal

Resource estimation, error correction, middleware/orchestration, hybrid HPC integration and hardware-aware tooling are still active research and engineering gaps. The strongest opportunities are therefore infrastructure products that reduce hardware requirements, validate claims, improve portability, or convert physical assumptions into engineering and economic decisions.
