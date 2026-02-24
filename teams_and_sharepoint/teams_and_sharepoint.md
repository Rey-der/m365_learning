# Teams & SharePoint

## Purpose

This folder documents Microsoft Teams and SharePoint Online configuration: collaboration architecture, permission models, governance policies, and external sharing controls. Focus is on controlled collaboration with clear security boundaries.

---

## Goals

- Design Teams and SharePoint architecture for scalability
- Define permission models (site owners, members, visitors)
- Implement external sharing policies with security controls
- Configure OneDrive for Business with governance policies

---

## Planned Structure

```
teams_and_sharepoint/
│
├── architecture.md                 Site hierarchy, Teams structure, naming standards
├── permission_model.md             Role definitions, inheritance, external access
├── governance_policies.md          Lifecycle, guest access, retention, DLP
├── external_sharing.md             External user policies, anonymous links, expiration
├── onedrive_governance.md          Sync policies, retention, known folder move
├── teams_policies.md               Meeting policies, messaging policies, app policies
├── screenshots/                    Configuration evidence
└── scripts/
    ├── New-Team.ps1                Standardized Team creation
    ├── Set-SitePermissions.ps1     SharePoint permission automation
    └── Get-ExternalSharingReport.ps1  External sharing audit
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **Collaboration Architecture** | Site structure, Teams hierarchy, naming conventions documented | ☐ |
| **Permission Model** | Clear role definitions, inheritance rules, external access controls | ☐ |
| **External Sharing Policies** | Controlled external access, link expiration, auditing enabled | ☐ |
| **OneDrive Governance** | Sync policies, retention, known folder move configured | ☐ |
| **Teams Policies** | Meeting, messaging, and app policies defined and applied | ☐ |

---

## Decision Log Topics

- Site architecture: hub sites vs. flat structure (trade-off: navigation vs. complexity)
- External sharing: default deny vs. controlled allow (security vs. collaboration friction)
- Teams lifecycle: permanent vs. expiration policies (storage cost vs. user experience)
- OneDrive sync: allow all vs. domain-joined only (BYOD vs. security)

---

## Operational Context

Collaboration tools are **high-risk** due to external sharing capabilities. Every configuration here balances productivity with security. This is not about enabling every sharing option — it's about defining clear boundaries for controlled collaboration.
