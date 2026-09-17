# Planned Repositories

Repository naming plan for the business micro-SaaS products.

| Product | Planned repository | Current status |
|---|---|---|
| Restaurant QR Pay | `AxionSoftware-Inc/Restaurant-QR-Pay` | Repository exists; README populated |
| Repair Approval Link | `AxionSoftware-Inc/Repair-Approval-Link` | Spec staged in Ideas |
| Repair Status QR | `AxionSoftware-Inc/Repair-Status-QR` | Spec staged in Ideas |
| Field Service Dispatch | `AxionSoftware-Inc/Field-Service-Dispatch` | Spec staged in Ideas |
| No-Show Killer | `AxionSoftware-Inc/No-Show-Killer` | Spec staged in Ideas |
| Debt Reminder | `AxionSoftware-Inc/Debt-Reminder` | Spec staged in Ideas |
| QR Call Staff | `AxionSoftware-Inc/QR-Call-Staff` | Spec staged in Ideas |

## Staged source specs

- `Repair-Approval-Link.md`
- `Repair-Status-QR.md`
- `Field-Service-Dispatch.md`
- `No-Show-Killer.md`
- `Debt-Reminder.md`
- `QR-Call-Staff.md`

Once each repository exists, its staged spec can become the repository `README.md` and development can begin without redesigning the business scope.

## Recommended implementation order

1. Restaurant QR Pay
2. Repair Approval Link + Repair Status QR on the same shared core
3. Field Service Dispatch
4. No-Show Killer
5. Debt Reminder
6. QR Call Staff

Build the reusable organization/auth/customer/payment/notification/public-link/audit foundation once. Avoid duplicating infrastructure across repositories.
