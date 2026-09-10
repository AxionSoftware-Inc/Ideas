# Digital Dependency & Substitutability Engine

## Problem
Organizations often know their direct software vendors but not the operational consequences of losing one cloud, model, API, package, certificate authority, SaaS product, region, or proprietary format. Vendor replacement can take months because hidden dependencies are discovered only during migration or outage.

## Product
A continuously updated dependency graph that answers: "If provider X disappears tomorrow, what breaks and what can replace it?"

## Core capabilities
- discover software/cloud/AI/API/data-format dependencies
- map direct and transitive dependencies
- identify vendor concentration and single points of failure
- measure portability of data, models and workloads
- maintain tested substitute providers/components
- generate exit/migration plans
- simulate sanctions, outage, price increase, API deprecation or vendor failure
- calculate recovery time and switching cost

## Example
Scenario: primary AI vendor unavailable for 30 days.
Output:
- 17 affected services
- 4 cannot migrate due to proprietary embeddings/API semantics
- substitute model A passes 91% acceptance tests
- estimated migration: 3 days
- service B has no tested substitute: critical

## Buyers
Governments, banks, telecoms, large enterprises, defense, critical infrastructure and cloud-heavy SaaS companies.

## Moat
Live dependency graph + executable replacement tests. This goes beyond SBOM/CMDB inventory by measuring whether dependencies are actually substitutable.

## MVP
Start with AI/cloud dependencies: repositories, IaC, API calls, model providers, storage and deployment manifests. Build a graph and automatically test one alternative backend against an acceptance suite.

## Strategic value
Very high as digital sovereignty and operational resilience become board-level concerns.
