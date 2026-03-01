# Identity

## Purpose

This folder covers **Entra ID** (Azure Active Directory) as the identity foundation for Microsoft 365. It includes user lifecycle management, group strategy, access control, and identity risk mitigation.

---

## Goals

- Implement a scalable user provisioning and deprovisioning process
- Design group strategy (security vs. Microsoft 365 groups, dynamic membership)
- Configure identity protection and risk-based policies
- Document access reviews and privileged identity management

---

## Planned Structure

```
identity/
│
├── user_lifecycle.md               Provisioning, modification, offboarding
├── group_strategy.md               Group types, naming, dynamic rules
├── access_control.md               RBAC, Conditional Access foundation
├── identity_protection.md          Risk policies, MFA enforcement
├── privileged_access.md            PIM, emergency access accounts
├── external_identities.md          B2B collaboration, guest policies
├── screenshots/                    Configuration evidence
└── scripts/
    ├── New-StandardUser.ps1        User creation with compliance defaults
    ├── New-DynamicGroup.ps1        Group automation examples
    └── Get-IdentityRiskReport.ps1  Risk detection reporting
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **User Lifecycle Process** | Standardized onboarding, modification, offboarding workflows | ☐ |
| **Group Design Document** | Group types, naming, dynamic membership rules | ☐ |
| **Identity Protection** | Risk-based policies, MFA enforcement, sign-in risk response | ☐ |
| **Privileged Access Management** | PIM configuration, emergency access accounts | ☐ |
| **Access Review Process** | Periodic review of group membership and role assignments | ☐ |

---

## Decision Log Topics

- Why dynamic groups instead of manual membership (trade-off: automation vs. complexity)
- MFA enforcement strategy: security defaults vs. Conditional Access
- Privileged Identity Management: just-in-time access vs. permanent assignments
- External user policies: default deny vs. controlled collaboration

---

## Operational Context

Identity is the **perimeter** in a Zero Trust model. Every decision here impacts authentication, authorization, and auditability. This is not about enabling features — it's about defining who can access what, when, and under which conditions.

---

---

# Identität (Deutsch)

## Zweck

Dieser Ordner behandelt **Entra ID** (Azure Active Directory) als Identitätsfundament für Microsoft 365. Er umfasst Benutzer-Lebenszykl-Management, Gruppenstrategie, Zugriffskontrolle und Identitätsrisiko-Mitigation.

---

## Ziele

- Implementiere einen skalierbaren Benutzer-Bereitstellungs- und Deprovisioning-Prozess
- Entwerfe eine Gruppenstrategie (Sicherheitsgruppen vs. Microsoft 365-Gruppen, dynamische Zugehörigkeit)
- Konfiguriere Identitätsschutz und risikobasierte Richtlinien
- Dokumentiere Zugriff-Überprüfungen und Privileged Identity Management

---

## Schlüssel-Lieferobjekte

| Lieferobjekt | Beschreibung | Status |
|:------------|:------------|:------:|
| **Benutzer-Lebenszykl-Prozess** | Standardisierte Onboarding-, Änderungs- und Offboarding-Workflows | ☐ |
| **Gruppenentwurf-Dokument** | Gruppentypen, Namenskonventionen, dynamische Zugehörigkeitsregeln | ☐ |
| **Identitätsschutz** | Risikobasierte Richtlinien, MFA-Durchsetzung, Anmelde-Risiko-Reaktion | ☐ |
| **Privileged Identity Management** | PIM-Konfiguration, Notfall-Zugangskonten | ☐ |
| **Zugriff-Überprüfungs-Prozess** | Periodische Überprüfung der Gruppenzugehörigkeit und Rollenzuweisungen | ☐ |

---

## Entscheidungsprotokoll-Themen

- Warum dynamische Gruppen anstelle von manueller Zugehörigkeit (Abwägung: Automatisierung vs. Komplexität)
- MFA-Durchsetzungsstrategie: Sicherheitsstandards vs. Conditional Access
- Privileged Identity Management: Just-in-Time-Zugriff vs. permanente Zuweisungen
- Externe Benutzerpolitik: Deny-all vs. kontrollierte Zusammenarbeit
