# Repair Approval Link

A lightweight approval layer for auto service centers, electronics repair shops, appliance repair businesses and similar services.

## Problem

A technician diagnoses additional work, then staff must call the customer, explain the issue, send photos manually, quote a price, wait for a response and later prove what was approved. This creates delays, disputes and lost staff time.

## Product

The business sends one secure customer link:

```text
Diagnosis -> photos/video -> proposed work -> price -> Approve / Reject -> audit trail
```

Example:

- Brake pads — 450,000 UZS — Approve
- Oil change — 350,000 UZS — Approve
- Brake discs — 800,000 UZS — Reject

Approved work appears instantly in the shop dashboard.

## Target customers

- auto repair/service centers
- tire/brake/oil service shops
- phone and laptop repair
- appliance repair
- industrial/equipment repair

## MVP

- business account and staff roles
- customer + asset: vehicle/device/equipment
- repair order
- diagnosis text
- before/diagnostic photos
- line-item estimate
- secure public approval link
- approve/reject per line item or full estimate
- timestamped approval record
- Telegram/SMS link delivery adapter
- dashboard status
- optional deposit/payment link
- final balance/payment link
- audit log

## Pricing hypothesis

| Plan | Indicative price |
|---|---:|
| Pilot | free / 99,000 UZS month |
| Small shop | 199,000 UZS/month |
| Pro | 399,000 UZS/month |
| Multi-branch | 699,000+ UZS/month |

Optional setup/integration: **300,000-1,000,000 UZS** depending on existing CRM/POS.

## Why a business may pay

- fewer approval phone calls
- faster repair turnaround
- fewer disputes about authorized work
- higher conversion on recommended repairs
- visible evidence and price before approval
- reusable history for repeat customers

## Later features

- repair-status tracking
- electronic signature/confirmation
- warranty records
- parts approval
- customer chat
- before/after report
- invoice/payment
- CRM integrations

## Success metrics

- approval turnaround time
- staff calls per repair order
- recommended-work approval rate
- repair cycle time
- disputes/complaints
- monthly recurring willingness to pay

## Shared-core fit

This should reuse the common Business Micro-SaaS core. The vertical objects are `Asset`, `RepairOrder`, `EstimateItem`, `Evidence`, and `Approval`.
