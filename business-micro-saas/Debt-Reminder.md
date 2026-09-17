# Debt Reminder

A lightweight B2B receivables reminder tool for businesses that sell on credit or invoice customers and then manually chase overdue payments.

## Problem

Small wholesalers, distributors and service companies often track receivables in spreadsheets, notebooks, Telegram chats or accounting software that does not actively help collect the money. Staff repeatedly call customers and owners lack a clear view of overdue cash.

## Product

```text
Invoice/credit recorded -> due date -> automatic reminder -> overdue escalation -> payment recorded -> closed
```

## Target customers

- wholesalers/distributors
- building-material sellers
- B2B service companies
- small manufacturers
- agencies/contractors
- businesses selling to regular customers on credit

## MVP

- company account
- customers
- invoices / debt entries
- amount, due date and status
- reminder schedules
- Telegram/SMS/email adapter
- secure customer payment/invoice link
- overdue dashboard
- due-this-week dashboard
- payment recording/reconciliation
- reminder history and audit log
- CSV import/export

## Pricing hypothesis

| Plan | Indicative price |
|---|---:|
| Pilot | free / 49,000-99,000 UZS month |
| Basic | 99,000-149,000 UZS/month |
| Pro | 249,000-299,000 UZS/month |
| Business | 499,000+ UZS/month |

Optional setup/import: **200,000-800,000 UZS** depending on customer/debt data quality.

## Why a business may pay

- less staff time chasing payments
- faster collections
- owner sees total overdue cash instantly
- consistent reminders instead of forgotten follow-ups
- clear evidence of reminders and payment promises

## Later features

- accounting integrations
- promise-to-pay date
- partial payments
- customer statements
- aging buckets
- manager escalation
- recurring invoices
- cash-flow forecasting
- per-customer payment behavior analytics

## Success metrics

- average days overdue
- amount collected after reminders
- staff calls/messages saved
- overdue balance before vs after
- percentage paid without manual follow-up

## Shared-core fit

Reuses customer, payment, notification, public-link, dashboard and audit modules. Vertical objects are `Receivable`, `ReminderSchedule`, `Payment`, and `CollectionEvent`.
