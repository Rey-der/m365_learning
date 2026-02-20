# Tenant Setup

## Purpose

This folder documents the foundational configuration decisions and administrative structure for the Microsoft 365 tenant. It represents the first operational layer — decisions made here affect every subsequent workstream.

---

## Goals

- Establish a defensible baseline configuration
- Define clear administrative boundaries and responsibilities
- Document licensing decisions and their operational impact
- Create reproducible setup processes for tenant initialization

---

## Planned Structure

```
tenant_setup/
│
├── baseline_configuration.md       Core tenant settings and defaults
├── admin_model.md                  Role separation and access control
├── licensing_strategy.md           License allocation and justification
├── naming_conventions.md           Standards for users, groups, resources
├── tenant_timeline.md              Key configuration milestones
└── scripts/
    ├── Initialize-Tenant.ps1       Baseline setup automation
    └── Validate-Baseline.ps1       Configuration verification
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **Baseline Configuration** | Core tenant settings, security defaults, regional settings | ☐ |
| **Admin Role Model** | Separation of duties, role assignments, PIM configuration | ☐ |
| **Naming Standards** | User principal names, group names, resource conventions | ☐ |
| **Licensing Strategy** | Business Premium vs E5 usage, assignment logic | ☐ |
| **Initialization Script** | PowerShell automation for repeatable tenant setup | ☐ |

---

## Decision Log Topics

- Why Business Premium was chosen as the baseline (cost vs. feature trade-off)
- Admin role separation strategy (least privilege vs. operational friction)
- Regional data residency considerations
- Security defaults: enabled or custom Conditional Access from day one

---

## Operational Context

This is **not** a feature demo — every setting here has a reason, a trade-off, and a documented alternative. Configuration choices reflect realistic constraints: budget, skill level, time, and risk tolerance.
