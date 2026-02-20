# Endpoint Management

## Purpose

This folder documents Microsoft Intune configuration: device enrollment, compliance policies, configuration profiles, application management, and security baselines. Focus is on securing and managing devices accessing Microsoft 365 resources.

---

## Goals

- Enroll devices into Intune (Windows, iOS, Android)
- Implement compliance policies and enforce conditional access
- Deploy configuration profiles (security, Wi-Fi, VPN, email)
- Apply Microsoft security baselines

---

## Planned Structure

```
endpoint_management/
│
├── enrollment_strategy.md          Device enrollment methods (Autopilot, manual, bulk)
├── compliance_policies.md          Device compliance requirements, conditional access integration
├── configuration_profiles.md       Settings catalog, templates, platform-specific configs
├── security_baselines.md           Microsoft security baselines for Windows, Edge
├── application_management.md       App deployment, protection policies, mobile app management
├── device_lifecycle.md             Enrollment, monitoring, retirement, wipe
└── policies/
    ├── compliance-windows.json     Sample Windows compliance policy
    ├── config-bitlocker.json       BitLocker configuration profile
    └── baseline-windows11.json     Windows 11 security baseline
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **Device Enrollment** | Enrollment methods tested, Autopilot configured (if applicable) | ☐ |
| **Compliance Policies** | Device compliance requirements defined and enforced | ☐ |
| **Configuration Profiles** | Security settings, Wi-Fi, VPN, email profiles deployed | ☐ |
| **Security Baselines** | Microsoft security baselines applied to Windows devices | ☐ |
| **App Management** | App deployment, MAM policies, app protection configured | ☐ |

---

## Decision Log Topics

- Enrollment method: Autopilot vs. manual (cost vs. user experience)
- Compliance enforcement: block non-compliant devices vs. mark as non-compliant (security vs. productivity)
- Configuration profiles: settings catalog vs. templates (flexibility vs. simplicity)
- Security baselines: standard vs. customized (default security vs. organizational needs)

---

## Operational Context

Endpoint management is **critical** for Zero Trust. Every device accessing corporate resources must be managed and compliant. This is not about enrolling devices for visibility — it's about enforcing security policies and conditional access based on device health.
