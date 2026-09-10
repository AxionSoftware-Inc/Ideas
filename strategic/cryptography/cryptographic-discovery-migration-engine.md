# Cryptographic Discovery & Migration Engine

## Problem
Large organizations often do not know where cryptography is actually used across source code, binaries, containers, firmware, certificates, APIs, TLS, SSH, signing systems, HSM integrations, and third-party dependencies. PQC migration therefore becomes an inventory and dependency-graph problem before it becomes a cryptography problem.

## Product
A cryptographic observability and migration engine that discovers cryptographic usage, builds a dependency graph, identifies risky/obsolete algorithms, models data-lifetime risk, and produces an actionable migration plan.

### Core pipeline
1. Scan source, binaries, containers, firmware, certificates, network endpoints and cloud assets.
2. Identify algorithms, key sizes, libraries, protocols and ownership.
3. Build a CBOM-like dependency graph.
4. Estimate risk by algorithm, data lifetime, protocol and system criticality.
5. Recommend migration targets and sequencing.
6. Optionally generate patches/configuration changes and verify the migrated state.

## Buyers
Banks, governments, telecoms, defense, cloud/enterprise operators, regulated industries.

## Moat
Cross-layer discovery + dependency reasoning + migration verification. The valuable part is not another TLS scanner; it is a system-level graph of cryptographic dependencies and migration consequences.

## Why now
PQC migration is becoming an operational requirement, while crypto inventory remains fragmented across tools and teams.

## MVP
- Git/container/binary scanner
- certificate/TLS inventory
- crypto dependency graph
- risk scoring
- migration planner
- before/after verification

## Strategic value
High. Can become a persistent security infrastructure layer rather than a one-time migration tool.
