# Business Micro-SaaS Product Pipeline

A set of small, focused B2B products designed to remove one expensive or annoying workflow from a business without replacing its entire CRM/POS/ERP.

The strategy is deliberately different from building large management systems: each product should be explainable in one sentence, demonstrable in minutes, cheap to operate, and valuable enough for a business to pay a monthly subscription.

## Product candidates

1. **Restaurant QR Pay** — table QR -> live bill -> pay -> leave. Dedicated repo: `AxionSoftware-Inc/Restaurant-QR-Pay`.
2. **Repair Approval Link** — send diagnosis, photos and estimate; customer approves work remotely.
3. **Repair Status QR** — customers check device/vehicle repair status without calling the shop.
4. **Field Service Dispatch** — assign technicians, track job status, photos, completion and payment.
5. **No-Show Killer** — appointment confirmation, deposit, reminder and one-click rescheduling.
6. **Debt Reminder** — automate B2B invoice/credit reminders and overdue dashboards.
7. **QR Call Staff** — table/room QR for waiter, cleaner, service or assistance requests.

## Shared technical core

```text
Organization / Location
Users / Roles
Customers
Orders / Jobs / Appointments
Status machine
Public tokenized links / QR
Payments and payment status
Notifications
Audit trail
Dashboard and analytics
Integrations / adapters
```

The goal is to build the common core once and expose vertical products/configurations on top of it.

## Commercial principle

Prefer recurring SaaS pricing over transaction-percentage revenue in early versions. Keep customer funds flowing directly through licensed payment providers to the merchant where payments are involved.

## Validation rule

Do not spend weeks building a full product before customer validation. For each product:

1. make a clickable/demo-quality MVP;
2. show 10-20 target businesses;
3. get 1-3 pilots;
4. measure the problem before/after;
5. only then deepen integrations and automation.
