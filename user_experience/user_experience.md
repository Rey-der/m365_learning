# User Experience

## Purpose

This folder documents end-user facing services and configurations: Microsoft 365 Apps deployment, user settings management, self-service capabilities, and training/communication strategies. Focus is on balancing user productivity with security and manageability.

---

## Goals

- Deploy and manage Microsoft 365 Apps (Office applications)
- Configure user settings and preferences (roaming, OneDrive Known Folder Move)
- Enable self-service capabilities (password reset, group management)
- Document user training and communication approaches

---

## Planned Structure

```
user_experience/
│
├── office_deployment.md            Microsoft 365 Apps deployment methods, update channels
├── user_settings.md                Settings roaming, personalization, OneDrive KFM
├── self_service.md                 SSPR, My Apps portal, group self-service
├── training_strategy.md            User onboarding, documentation, support resources
├── communication_plan.md           Change management, rollout communication
├── productivity_tools.md           Power Automate, Forms, Planner, To Do
└── guides/
    ├── onboarding_checklist.md     New user onboarding steps
    ├── office_quick_start.md       Microsoft 365 Apps quick start guide
    └── self_service_guide.md       Password reset, profile update instructions
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **Office Apps Deployment** | Microsoft 365 Apps deployed, update channel configured | ☐ |
| **User Settings Management** | Settings roaming, Known Folder Move configured | ☐ |
| **Self-Service Capabilities** | SSPR enabled, My Apps portal configured, group self-service enabled | ☐ |
| **User Training Materials** | Onboarding guides, quick start documentation, support resources | ☐ |
| **Communication Plan** | Rollout communication templates, change management process | ☐ |

---

## Decision Log Topics

- Office deployment: Click-to-Run vs. web-based (flexibility vs. control)
- Update channel: current vs. monthly enterprise (stability vs. latest features)
- Known Folder Move: forced vs. optional (data protection vs. user autonomy)
- Self-service: enabled vs. IT-controlled (user empowerment vs. support burden)

---

## Operational Context

User experience is **often overlooked** in technical projects. Every configuration here considers the end-user impact. This is not about enforcing IT policies — it's about enabling productivity while maintaining security and manageability.
