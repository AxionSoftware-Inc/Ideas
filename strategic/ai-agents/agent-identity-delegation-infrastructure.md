# AI Agent Identity & Delegation Infrastructure

## Problem
As AI agents act across APIs, payments, enterprise apps and infrastructure, organizations need to know exactly which agent acted, on whose authority, within which task, with what permissions, and who is accountable. Traditional service accounts and OAuth scopes are often too coarse for autonomous software actors.

## Product
A portable identity, delegation and authorization layer for AI/software agents.

## Core concepts
- cryptographic agent identity
- human/org principal linkage
- explicit delegation chains
- task-scoped and time-scoped authority
- value/impact limits
- revocation and emergency stop
- non-repudiable action receipts
- cross-organization trust assertions
- policy evaluation before tool/API access

## Example delegation
CFO -> Procurement Agent -> Vendor-Negotiation Subagent
Authority:
- read approved suppliers
- negotiate price
- may commit <= $2,000
- cannot change bank details
- expires 18:00 UTC

Every action carries evidence of that chain.

## Buyers
Banks, payment networks, SaaS platforms, enterprise identity vendors, governments, agent-framework vendors and regulated industries.

## Moat
A vendor-neutral identity/delegation protocol plus enforcement runtime. The goal is to become infrastructure analogous to workload identity/OAuth for autonomous agents, not another agent framework.

## Relationship to Agent Transaction Firewall
Identity/delegation answers 'who is allowed to act and under whose authority?'. The transaction firewall answers 'should this specific proposed action be allowed after considering its consequences?'. They can form one stack but remain separable products.

## MVP
Issue verifiable agent identities, define delegation policies, intercept a small set of API/tool calls, attach signed action receipts and support immediate revocation.

## Strategic value
High if agentic commerce and cross-company autonomous workflows become mainstream.
