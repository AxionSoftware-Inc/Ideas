# AI Agent Transaction Firewall

## Problem
AI agents are moving from read-only assistance toward actions: payments, deployments, emails, account changes, purchasing, infrastructure changes and database operations. Existing guardrails are often model-level, while real risk is action-specific and consequence-specific.

## Product
A runtime authorization and consequence-analysis layer between an AI agent and real systems.

### Core pipeline
Agent intent -> proposed action -> identity/role -> policy -> consequence analysis -> approval threshold -> execution -> immutable audit evidence.

## Key capabilities
- verified agent identity
- task-scoped permissions
- transaction/value limits
- irreversible-action detection
- blast-radius estimation
- environment awareness (dev/staging/prod)
- human approval gates
- rollback/precondition checks
- auditable action provenance

## Buyers
Banks, SaaS vendors, enterprises deploying agents, cloud platforms, agent-framework vendors, regulated industries.

## Moat
Action-level governance with real consequence modelling, not simply prompt filtering or sandboxing.

## MVP
Start with GitHub + cloud + database actions. Intercept tool calls, classify consequence level, enforce policy, request approval when required, and log proof.

## Strategic value
Very high if autonomous agents become common enterprise actors.
