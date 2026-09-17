# Repair Status QR

A self-service repair tracking page for customers of phone, laptop, appliance, auto and equipment repair businesses.

## Problem

Customers repeatedly call or message a repair shop asking whether their device or vehicle is ready. Staff spend time answering the same status question, while customers still feel uncertain.

## Product

Each repair order gets a QR code / secure link:

```text
Received -> Diagnostics -> Waiting for approval/part -> Repairing -> Testing -> Ready -> Collected
```

The customer can check status at any time without calling the shop.

## Target customers

- phone repair shops
- laptop/computer repair
- appliance repair
- auto service centers
- camera/electronics repair
- equipment workshops

## MVP

- business account
- repair order with unique reference/token
- customer and asset/device details
- public mobile status page
- QR code and shareable link
- configurable status pipeline
- ETA / expected completion field
- short staff notes visible to customer
- optional diagnosis/estimate link
- ready-for-pickup notification
- dashboard with active repairs
- audit history

## Pricing hypothesis

| Plan | Indicative price |
|---|---:|
| Pilot | free / 49,000-99,000 UZS month |
| Small shop | 99,000-149,000 UZS/month |
| Pro | 249,000 UZS/month |
| Multi-branch | 499,000+ UZS/month |

One-time setup/branding can be **200,000-500,000 UZS**.

## Why a business may pay

- fewer repetitive phone calls and Telegram messages
- more professional customer experience
- visible repair pipeline
- less front-desk workload
- easy path to upsell approval/payment modules

## Later features

- Repair Approval Link integration
- invoice/payment
- warranty certificate
- pickup authorization
- customer satisfaction/review link
- repair history
- parts waiting status
- automated Telegram/SMS notifications

## Success metrics

- support calls/messages per 100 repair orders
- percentage of customers using status page
- average staff time saved
- customer satisfaction
- monthly paid retention

## Shared-core fit

This can share almost all infrastructure with Repair Approval Link. A combined commercial product may ultimately be stronger than two separate apps, but this spec keeps the customer-value proposition independently testable.
