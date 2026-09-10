# Quantum Software Opportunities

Purpose: track quantum-software ideas that have a clear strategic or commercial use, remain technically incomplete or fragmented, and do not require waiting for a fully fault-tolerant quantum computer before they can become useful.

## Selection rules

A project belongs here only if most of the following are true:

- The problem exists today or is becoming unavoidable.
- Current solutions are incomplete, vendor-locked, fragmented, research-grade, or expensive to integrate.
- There is a clear buyer: quantum hardware company, cloud provider, enterprise, government, research lab, HPC center, security team, or tool vendor.
- Better software can create a measurable advantage in cost, reliability, validation, portability, utilization or time-to-result.
- The project can begin with simulators, public hardware backends, traces, calibration data, benchmarks or classical infrastructure.
- The value grows as quantum hardware improves.
- The project has a possible technical moat beyond UI, consulting or another thin wrapper around existing SDKs.

## Current project map

1. `01-resource-economics-feasibility-engine.md` — hardware-aware quantum resource, cost, time, energy and feasibility analysis.
2. `02-qec-engineering-benchmark-platform.md` — error-correction experiment, decoder benchmarking and certification workbench.
3. `03-quantum-hardware-digital-twin.md` — calibration-aware digital twin for QPU behavior and control experiments.
4. `04-quantum-hpc-orchestrator.md` — vendor-neutral hybrid CPU/GPU/QPU scheduling and execution layer.
5. `05-quantum-compiler-verification.md` — semantic/equivalence validation and resource-regression testing for quantum compilers.
6. `06-quantum-control-ir.md` — hardware-neutral intermediate representation between circuits and physical pulse/control systems.
7. `07-autonomous-quantum-calibration-engine.md` — self-healing calibration control plane that detects drift and minimizes calibration experiments.
8. `08-real-time-qec-runtime.md` — low-latency production runtime for syndrome decoding, scheduling and QPU feedback.
9. `09-fault-tolerant-logical-scheduler.md` — EDA-like place-and-route/scheduling engine for logical qubits, lattice surgery and magic-state resources.
10. `10-experiment-reproducibility-provenance-engine.md` — reproducible experiment packaging, replay and causal attribution of run-to-run differences.
11. `11-quantum-result-certification-engine.md` — independent trust/certification layer for quantum results that become hard to verify classically.
12. `12-quantum-advantage-discovery-engine.md` — automatic discovery of enterprise/scientific workloads where quantum execution may actually be justified.
13. `13-adaptive-error-mitigation-compiler.md` — device-, circuit- and budget-aware selection of error-mitigation pipelines for noisy hardware.
14. `14-hardware-benchmark-procurement-intelligence.md` — neutral workload-specific comparison of QPU providers by accuracy, runtime, queue, reproducibility and cost.
15. `15-quantum-technology-intelligence-engine.md` — evidence-linked normalization of vendor claims, roadmaps and hardware/QEC progress into capability forecasts.

## Highest-priority strategic candidates

These currently look strongest because they solve infrastructure problems that become more important as hardware scales:

- Autonomous Quantum Calibration Engine
- Real-Time QEC Runtime
- Fault-Tolerant Logical Scheduler / Place-and-Route
- Quantum Resource + Economics + Feasibility Engine
- Quantum Result Certification Engine
- Quantum Hardware Digital Twin

A particularly strong combined direction is a **Quantum Autopilot** stack:

`real QPU telemetry -> hardware digital twin -> drift prediction -> autonomous calibration -> validation -> real QPU`

A second strong combined direction is a **Fault-Tolerant Execution Stack**:

`logical program -> resource model -> logical scheduler/place-and-route -> real-time QEC runtime -> hardware control`

## Near-term commercial candidates

These can create value before large fault-tolerant machines exist:

- Resource/Economics/Feasibility Engine
- QEC Engineering & Benchmark Platform
- Hardware Digital Twin
- Autonomous Calibration Engine
- Experiment Reproducibility & Provenance Engine
- Adaptive Error-Mitigation Compiler
- Hardware Benchmark & Procurement Intelligence
- Quantum Technology Intelligence Engine

## Longer-horizon / watchlist

Worth tracking, but not promoted to separate projects yet because timing or market clarity is weaker:

- Quantum network engineering and simulation infrastructure
- Distributed quantum-network routing/control plane
- Quantum memory orchestration
- Cross-vendor entanglement-service abstraction
- Fully hardware-neutral pulse/control standardization beyond the current Control IR concept
- Automated co-design across quantum chip layout, cryogenic electronics and logical architecture

## Ideas deliberately excluded for now

- Another generic quantum SDK.
- Another visual circuit editor.
- Another basic state-vector simulator.
- A new quantum programming language without a strong infrastructure advantage.
- Consumer-facing quantum apps whose value depends on hardware that does not yet exist.
- Pure education products without a strategic or commercial moat.
- Thin dashboards or news aggregators without proprietary models, evidence graphs or decision engines.

## Status

This quantum opportunity map is intentionally paused after the current set of 15 projects. Future additions should only be made when a genuinely new infrastructure gap appears, not merely a variation of an existing item. The next useful work on this folder is deeper validation of individual candidates: competitors, patents/IP, public datasets, MVP scope, technical difficulty, buyer interviews and build-vs-market risk.