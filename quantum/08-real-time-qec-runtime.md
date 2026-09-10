# Real-Time QEC Runtime

## Problem
Fault-tolerant quantum computing requires decoding syndrome streams under strict latency constraints. Research decoders are usually benchmarked as algorithms, but production systems need an end-to-end runtime with predictable tail latency, hardware integration and fault isolation.

## Product
A real-time operating layer between the QPU controller and one or more decoders. It ingests syndrome streams, routes work, enforces latency budgets, handles backpressure and failover, emits corrections/logical feedback, and records deterministic traces.

## Core pipeline
Syndrome stream -> preprocessing -> decoder scheduling -> correction decision -> controller feedback -> telemetry.

## Buyers
QPU vendors, QEC teams, control-stack vendors, HPC centers and fault-tolerant architecture teams.

## Moat
Low-latency scheduler, decoder plugin ABI, deterministic replay, FPGA/GPU/CPU backends, tail-latency control and hardware-specific feedback integration.

## MVP
Run Stim-generated syndrome streams through multiple decoders with hard latency budgets, replay, failure injection and comparative end-to-end metrics.

## Strategic value
A good decoder is not enough if the whole loop misses timing constraints. This runtime can become infrastructure required by many decoder families and hardware platforms.