# Quantum Experiment Reproducibility & Provenance Engine

## Problem
Two runs of the same circuit can differ because calibration state, qubit mapping, transpiler version, mitigation settings, backend firmware and runtime parameters changed. Published results are therefore difficult to reproduce exactly.

## Product
A provenance layer that packages a quantum experiment with circuit, compiler/transpiler versions, mapping, calibration snapshot, pulse/control settings, noise metadata, mitigation configuration, backend identity and results.

## Core capability
Capture -> sign/version -> replay -> compare -> attribute result drift to environmental or software changes.

## Buyers
Research labs, universities, hardware vendors, journals, regulated R&D teams and benchmarking organizations.

## Moat
Cross-vendor metadata schema, replay adapters, experiment differencing, provenance graph and causal attribution of result changes.

## MVP
Support Qiskit/Cirq-style workflows and simulator backends first; record complete experiment manifests and reproduce or explain differences across runs.

## Strategic value
As quantum results become commercially important, reproducibility moves from academic convenience to evidence and audit infrastructure.