# Field Service Dispatch

A lightweight job-dispatch system for companies that send technicians or workers to customer locations.

## Problem

Many small service businesses coordinate work through phone calls and Telegram chats: the administrator receives an order, manually contacts a worker, sends an address, later asks whether the worker arrived, and finally reconciles photos and payment. Information gets lost and managers cannot see the real state of today's jobs.

## Product

```text
New job -> assign technician -> route/location -> Arrived -> work photos -> customer confirmation -> payment -> Done
```

## Target customers

- air-conditioner installation/service
- plumbers
- electricians
- cleaning companies
- CCTV/security installers
- internet/network installers
- appliance repair
- maintenance contractors
- small construction/service crews

## MVP

- company + staff accounts
- customer and address
- new job form
- technician assignment
- technician mobile job page
- map/deep-link to location
- status transitions: Assigned / En route / Arrived / Working / Done
- before/after photos
- job notes and materials used
- customer confirmation
- payment status
- admin dispatch board
- daily technician workload
- audit history

## Pricing hypothesis

| Plan | Indicative price |
|---|---:|
| Pilot | free / 99,000 UZS month |
| Small team | 199,000 UZS/month |
| Growing team | 399,000-599,000 UZS/month |
| Multi-branch | 999,000+ UZS/month |

Optional onboarding/custom workflow: **300,000-1,500,000 UZS**.

## Why a business may pay

- fewer phone calls between dispatcher and technicians
- manager sees every active job in one place
- evidence that worker arrived and completed the work
- before/after photos reduce disputes
- easier workload and payment reconciliation
- faster customer updates

## Later features

- recurring maintenance jobs
- route optimization
- technician GPS check-in
- inventory/material usage
- quotes and approvals
- invoices/payment links
- customer portal
- SLA timers
- technician performance analytics
- WhatsApp/Telegram/SMS notifications

## Success metrics

- dispatcher calls/messages per job
- average time from new order to assignment
- jobs completed per technician/day
- missed/forgotten jobs
- customer disputes
- on-time arrival rate

## Shared-core fit

This is a high-reuse vertical of the common SaaS core. The main domain objects are `Job`, `Technician`, `Assignment`, `VisitEvidence`, and `Completion`.
