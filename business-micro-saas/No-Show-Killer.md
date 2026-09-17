# No-Show Killer

A focused appointment-confirmation and deposit layer for businesses that lose money when booked customers do not arrive.

## Problem

A missed appointment wastes a time slot that often cannot be resold. Staff also spend time manually calling or messaging customers to confirm bookings.

## Product

```text
Appointment created -> confirmation link -> optional deposit -> reminder -> Confirm / Reschedule -> attendance status
```

This is not intended to replace a salon/clinic CRM. It should integrate with or sit beside the existing booking system.

## Target customers

- salons and barbers
- dentists
- private clinics
- beauty/cosmetology
- tutors/coaches
- photographers/studios
- consultants
- other appointment businesses

## MVP

- business account
- appointments
- customer contact
- secure confirmation link
- Confirm / Cancel / Reschedule action
- configurable deposit requirement
- payment status through licensed provider
- automatic reminders
- dashboard: confirmed / pending / cancelled / no-show
- appointment audit history
- manual booking import/API adapter

## Pricing hypothesis

| Plan | Indicative price |
|---|---:|
| Pilot | free / 49,000-99,000 UZS month |
| Basic | 99,000-149,000 UZS/month |
| Pro | 249,000-299,000 UZS/month |
| Multi-location | 499,000+ UZS/month |

The easiest sales argument is measurable: compare no-show rate before and after the pilot.

## Why a business may pay

- fewer empty booked slots
- fewer manual reminder calls/messages
- deposit makes expensive appointments safer
- customers can reschedule instead of disappearing
- direct measurable revenue recovery

## Later features

- calendar integrations
- recurring appointment series
- waitlist that fills cancelled slots
- automatic offer to waitlist customers
- customer reliability score based only on the business's own history
- campaign/reminder templates
- multi-location scheduling adapters

## Success metrics

- no-show percentage before vs after
- confirmed appointments
- rescheduled instead of missed
- recovered revenue
- reminder delivery/action rate
- customer complaints/friction

## Shared-core fit

Reuses Business, Customer, Payment, Notification, public-link and audit infrastructure. Vertical domain objects are `Appointment`, `Confirmation`, `Deposit`, and `AttendanceOutcome`.
