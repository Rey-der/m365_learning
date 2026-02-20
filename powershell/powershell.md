# PowerShell

## Purpose

This folder contains PowerShell scripts for Microsoft 365 administration: automation, reporting, bulk operations, and maintenance tasks. Focus is on repeatable, documented, and testable automation.

---

## Goals

- Automate common administrative tasks (user provisioning, group management)
- Create reporting scripts for operational visibility
- Document script usage, parameters, and dependencies
- Implement error handling and logging

---

## Planned Structure

```
powershell/
│
├── README.md                       Script inventory and usage guidelines
├── connection_scripts/
│   ├── Connect-M365Services.ps1    Connect to all M365 modules
│   └── Test-M365Connection.ps1     Validate service connections
│
├── user_management/
│   ├── New-StandardUser.ps1        Create user with standard settings
│   ├── Set-UserOffboarding.ps1     Disable user, convert to shared mailbox
│   └── Get-InactiveUsers.ps1       Report inactive user accounts
│
├── group_management/
│   ├── New-DynamicGroup.ps1        Create dynamic security groups
│   ├── Get-GroupMembership.ps1     Report group membership
│   └── Sync-GroupOwners.ps1        Ensure groups have active owners
│
├── reporting/
│   ├── Get-TenantReport.ps1        Comprehensive tenant health report
│   ├── Get-LicenseUsage.ps1        License allocation and usage
│   └── Get-SecurityReport.ps1      Security posture summary
│
└── utilities/
    ├── Export-TenantConfig.ps1     Backup tenant configuration
    ├── Test-ConditionalAccess.ps1  Validate CA policy impact
    └── logging_module.psm1         Centralized logging functions
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **Connection Scripts** | Standardized connection to all M365 services | ☐ |
| **User Automation** | User provisioning, offboarding, reporting scripts | ☐ |
| **Group Automation** | Group creation, membership management, reporting | ☐ |
| **Reporting Suite** | Tenant health, license usage, security reports | ☐ |
| **Configuration Backup** | Tenant configuration export and documentation | ☐ |

---

## Script Standards

All scripts in this folder follow these standards:

- **Comment-Based Help**: Every script includes `.SYNOPSIS`, `.DESCRIPTION`, `.PARAMETER`, `.EXAMPLE`
- **Error Handling**: `try/catch` blocks, meaningful error messages
- **Logging**: All actions logged with timestamps
- **Testing**: Script tested in non-production environment before use
- **Versioning**: Script version tracked in header comments

---

## Decision Log Topics

- Script location: local vs. Azure Automation vs. GitHub (portability vs. automation)
- Credential management: stored credentials vs. interactive vs. managed identity (security vs. convenience)
- Module versions: latest vs. pinned (stability vs. features)
- Execution policy: RemoteSigned vs. AllSigned (security vs. ease of use)

---

## Operational Context

Automation is **essential** for consistent operations. Every script here is written with repeatability and auditability in mind. This is not about one-off fixes — it's about building reliable, documented automation that reduces manual effort and human error.
