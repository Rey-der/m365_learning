# Security Basics

## Purpose

This folder documents foundational security configurations: Multi-Factor Authentication, Conditional Access, Microsoft Secure Score, and baseline threat protection. It represents the **minimum viable security posture** for a production tenant.

---

## Goals

- Enforce MFA for all users (or document exceptions)
- Implement Conditional Access policies with clear intent
- Track and improve Microsoft Secure Score systematically
- Enable Microsoft Defender for Office 365 (if licensed)

---

## Planned Structure

```
security_basics/
│
├── mfa_strategy.md                 MFA methods, enforcement, exceptions
├── conditional_access.md           Policy design, testing, deployment
├── secure_score.md                 Baseline score, improvement tracking
├── defender_basics.md              Safe Links, Safe Attachments, anti-phishing
├── audit_logging.md                Unified Audit Log configuration and usage
├── security_incidents.md           Detection, response, lessons learned
├── screenshots/                    Configuration evidence
└── policies/
    ├── CA-Block-Legacy-Auth.json   Sample Conditional Access policy
    ├── CA-Require-MFA-Admins.json  Admin MFA enforcement
    └── validation_checklist.md     Policy testing procedures
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **MFA Enforcement** | MFA enabled for all users, documented exceptions | ☐ |
| **Conditional Access Policies** | Core policies: block legacy auth, require MFA for admins, location-based access | ☐ |
| **Secure Score Baseline** | Initial score documented, improvement plan defined | ☐ |
| **Defender for Office 365** | Safe Links, Safe Attachments, anti-phishing policies configured | ☐ |
| **Audit Logging** | Unified Audit Log enabled, retention configured, search tested | ☐ |

---

## Decision Log Topics

- MFA for all users vs. Conditional Access-based enforcement (trade-off: simplicity vs. flexibility)
- Blocking legacy authentication: immediate vs. phased rollout (impact on legacy apps)
- Secure Score prioritization: which recommendations to implement first
- Defender policies: standard vs. strict protection (user friction vs. security)

---

## Operational Context

Security is **not optional**. Every configuration here is chosen to balance protection with usability. This is not about achieving 100% Secure Score — it's about making deliberate, documented decisions on acceptable risk.
