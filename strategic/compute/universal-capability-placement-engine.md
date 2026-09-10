# Universal Hardware/Software Capability Placement Engine

## Problem
Modern systems contain CPUs, GPUs, NPUs, FPGAs, remote accelerators and eventually QPUs. Software is usually hard-wired to one execution target, while the best target depends on operation type, data location, transfer overhead, queue time, power and cost.

## Product
A runtime/compiler layer that profiles available compute resources and places operations on the best target automatically.

## Decision factors
- operation type and supported kernels
- latency and throughput
- data transfer cost
- memory capacity/bandwidth
- remote network delay
- queue availability
- monetary cost
- energy budget
- precision requirements

## Example
For one operation:
- local GPU: 4.1 ms
- CPU AVX2: 18 ms
- remote H100: 1.1 ms compute + 12 ms transfer
-> choose local GPU.

## Buyers
AI inference platforms, engineering software, rendering, edge computing, heterogeneous HPC, device makers.

## Moat
Performance models + adaptive placement + portable operation IR. The long-term asset is an execution planner that understands both software semantics and actual hardware behaviour.

## MVP
Support CPU + CUDA GPU + one remote GPU backend and a limited kernel set. Benchmark automatically and route tasks based on measured total cost rather than raw accelerator speed.

## Risk
Very broad if attempted as a universal system immediately. Must begin with one workload family such as inference, geometry processing or numerical kernels.
