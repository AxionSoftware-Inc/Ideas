# Quantum Program Semantic IR

## Thesis
Represent quantum programs above vendor circuit syntax: algorithm intent, logical operations, observables, precision targets, noise assumptions, dynamic control and hardware constraints in one typed IR.

## Why
Circuit syntax alone loses why operations exist and what transformations are legally equivalent for the scientific task.

## Targets
OpenQASM 3, QIR-like backends, vendor SDKs, simulators and resource estimators.

## Moat
Semantic equivalence and provenance across compilation levels.

## MVP
A restricted IR for variational/measurement-based workloads with round-trip adapters and invariant checks.