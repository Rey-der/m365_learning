# Resources

## Purpose

This folder centralizes all visual assets, screenshots, and supporting materials for the Microsoft 365 Learning & Operations Lab. It provides a single point of reference for images, diagrams, and visual evidence used across domain-specific README files.

---

## Structure

```
resources/
│
├── README.md                           This file - overview and organization
├── tenant_setup_screenshots/           Tenant baseline configuration screenshots
├── identity_screenshots/               Entra ID and user lifecycle screenshots
├── security_basics_screenshots/        MFA, Conditional Access, Secure Score screenshots
├── exchange_online_screenshots/        Mail flow, policies, shared mailbox screenshots
├── teams_sharepoint_screenshots/       Teams, SharePoint, collaboration screenshots
├── endpoint_management_screenshots/    Intune, compliance policies, device screenshots
├── user_experience_screenshots/        Office deployment, settings, user guides screenshots
├── powershell_screenshots/             PowerShell execution, script output screenshots
├── incidents_screenshots/              Incident evidence, error messages, logs
├── documentation_screenshots/          Architecture diagrams, decision logs, runbooks
└── learning_roadmap_screenshots/       Progress tracking, certification materials
```

---

## Guidelines

### Naming Convention

All screenshots should follow this naming pattern:

```
YYYY-MM-DD_[domain]_[description].png
```

**Examples:**
- `2026-03-02_tenant_baseline_configuration.png` - Tenant baseline setup from admin center
- `2026-03-01_identity_mfa_enforcement.png` - MFA policy configuration
- `2026-02-28_security_conditional_access.png` - Conditional Access policy
- `2026-03-02_incidents_error_message.png` - Error message during incident

### Image Quality

- **Minimum resolution**: 1280x720 (720p)
- **Preferred resolution**: 1920x1080 (1080p) or larger
- **Format**: PNG (preferred) or JPG
- **File size**: Keep under 2MB per image (optimize if needed)
- **Privacy**: Ensure no sensitive data (real tenant names, user emails, API keys) is visible

### Content Best Practices

1. **Show context**: Include enough screen to understand the configuration
2. **Highlight key areas**: Circle or arrow important elements if needed
3. **Document state**: Capture both before and after states for significant changes
4. **Include navigation**: Show the path taken to reach the setting (breadcrumb trail visible)
5. **Terminal output**: For PowerShell screenshots, capture both command and output

---

## Folder Descriptions

### tenant_setup_screenshots/
Visual evidence of tenant baseline configuration:
- Security defaults settings
- Admin role assignments
- Regional settings
- Licensing configuration

### identity_screenshots/
Entra ID configuration and user lifecycle:
- User creation and properties
- Group membership and dynamic rules
- Conditional Access policies
- Identity Protection settings
- Multi-factor authentication methods

### security_basics_screenshots/
Foundational security configurations:
- Microsoft Secure Score dashboard
- MFA enforcement policies
- Conditional Access policy evaluation
- Defender for Office 365 settings
- Audit logging configuration

### exchange_online_screenshots/
Mail flow and mailbox management:
- Mail flow connectors
- Shared mailbox creation
- Distribution group configuration
- Retention policies
- Transport rules

### teams_sharepoint_screenshots/
Collaboration platform configuration:
- Team and channel creation
- SharePoint site structure
- External sharing policies
- OneDrive Known Folder Move
- Permission model implementation

### endpoint_management_screenshots/
Intune and device management:
- Device enrollment process
- Compliance policy assignment
- Configuration profile deployment
- Autopilot setup (if applicable)
- Security baseline application

### user_experience_screenshots/
End-user services and configuration:
- Microsoft 365 Apps deployment
- Settings roaming
- Self-service password reset
- My Apps portal
- Onboarding documentation

### powershell_screenshots/
Automation and scripting evidence:
- Connection string examples
- Script execution output
- Logging and error handling
- Report generation results
- Bulk operation examples

### incidents_screenshots/
Incident documentation and evidence:
- Error messages and logs
- Timeline of events
- Investigation findings
- Before/after comparisons
- Alert and notification screenshots

### documentation_screenshots/
Architecture and planning visuals:
- Tenant architecture diagrams
- Data flow diagrams
- Authentication flows
- Decision log supporting materials
- Runbook process flows

### learning_roadmap_screenshots/
Progress tracking and certification:
- Milestone completion evidence
- Certification exam preparation
- Skill assessment results
- Project completion screenshots
- Portfolio evidence

---

## Usage Instructions

### Adding Screenshots

1. Take screenshot of the relevant configuration
2. Ensure no sensitive data is visible
3. Save with naming convention: `YYYY-MM-DD_[domain]_[description].png`
4. Move to appropriate subfolder
5. Reference in the corresponding domain README

### Linking in Documentation

In your domain-specific markdown files, reference images like this:

```markdown
![Description of image](../../resources/tenant_setup_screenshots/2026-03-02_tenant_baseline_configuration.png)

Or for inline reference:
See the screenshot in [resources/tenant_setup_screenshots/](../../resources/tenant_setup_screenshots/)
```

### Organizing by Date

Within each subfolder, organize screenshots chronologically:
- Group by month if many screenshots
- Keep related screenshots together
- Update links if reorganizing

---

## Maintenance

- **Review monthly**: Delete outdated or duplicate screenshots
- **Update regularly**: Add new screenshots as configurations change
- **Keep consistent**: Maintain naming and folder structure
- **Archive old**: Move very old screenshots to an archive folder if needed

---

## Version Control Notes

These image files are tracked in git. For large screenshot collections:
- Consider using `.gitignore` for archived folders if storage becomes an issue
- Keep current screenshots for operational reference
- Document which screenshots are essential vs. archival

---

## Related Documentation

- Domain-specific README files reference appropriate screenshots from this folder
- Each domain folder has a `screenshots/` subdirectory for inline organization
- This `resources/` folder serves as the central archive and organization point

---

**Last Updated:** 2026-03-02  
**Status:** Framework Ready  
**Next Steps:** Begin populating subfolders with evidence screenshots as configurations are documented

---

---

# Ressourcen (Deutsch)

## Zweck

Dieser Ordner zentralisiert alle visuellen Vermögenswerte, Screenshots und unterstützende Materialien für das Microsoft 365 Learning & Operations Lab. Er bietet einen zentralen Anlaufpunkt für Bilder, Diagramme und visuelle Beweise, die in domänenspezifischen README-Dateien verwendet werden.

---

## Struktur

```
resources/
│
├── README.md                           Diese Datei - Übersicht und Organisation
├── tenant_setup_screenshots/           Screenshots der Mandanten-Basis-Konfiguration
├── identity_screenshots/               Entra ID und Benutzer-Lebenszykl-Screenshots
├── security_basics_screenshots/        MFA, Conditional Access, Secure Score-Screenshots
├── exchange_online_screenshots/        Mailfluss, Richtlinien, freigegebene Postfach-Screenshots
├── teams_sharepoint_screenshots/       Teams, SharePoint, Zusammenarbeit-Screenshots
├── endpoint_management_screenshots/    Intune, Compliance-Richtlinien, Geräte-Screenshots
├── user_experience_screenshots/        Office-Bereitstellung, Einstellungen, Benutzerhandbuch-Screenshots
├── powershell_screenshots/             PowerShell-Ausführung, Skript-Output-Screenshots
├── incidents_screenshots/              Vorfall-Beweise, Fehlermeldungen, Protokolle
├── documentation_screenshots/          Architektur-Diagramme, Entscheidungsprotokolle, Runbooks
└── learning_roadmap_screenshots/       Fortschritts-Verfolgung, Zertifizierungsmaterialien
```

---

## Richtlinien

### Namenskonvention

Alle Screenshots sollten diesem Muster folgen:

```
YYYY-MM-DD_[domain]_[beschreibung].png
```

**Beispiele:**
- `2026-03-02_mandant_baseline_konfiguration.png` - Mandanten-Basis-Setup aus Admin Center
- `2026-03-01_identitaet_mfa_durchsetzung.png` - MFA-Richtlinien-Konfiguration
- `2026-02-28_sicherheit_conditional_access.png` - Conditional Access-Richtlinie
- `2026-03-02_vorfaelle_fehlermeldung.png` - Fehlermeldung während eines Vorfalls

### Bildqualität

- **Mindestauflösung**: 1280x720 (720p)
- **Bevorzugte Auflösung**: 1920x1080 (1080p) oder größer
- **Format**: PNG (bevorzugt) oder JPG
- **Dateigröße**: Unter 2MB pro Bild halten (falls nötig optimieren)
- **Datenschutz**: Sicherstellen, dass keine sensiblen Daten (echte Mandantennamen, Benutzer-E-Mails, API-Schlüssel) sichtbar sind

---

## Verwendungsanweisung

### Screenshots hinzufügen

1. Screenshot der relevanten Konfiguration aufnahmen
2. Sicherstellen, dass keine sensiblen Daten sichtbar sind
3. Mit Namenskonvention speichern: `YYYY-MM-DD_[domain]_[beschreibung].png`
4. In entsprechenden Unterordner verschieben
5. In der entsprechenden Domänen-README referenzieren

### In Dokumentation verlinken

In deinen domänenspezifischen Markdown-Dateien, referenziere Bilder wie folgt:

```markdown
![Beschreibung des Bildes](../../resources/tenant_setup_screenshots/2026-03-02_mandant_baseline_konfiguration.png)

Oder für Inline-Referenz:
Siehe Screenshot in [resources/tenant_setup_screenshots/](../../resources/tenant_setup_screenshots/)
```

---

**Zuletzt aktualisiert:** 2026-03-02  
**Status:** Framework Bereit  
**Nächste Schritte:** Unterordner mit Beweise-Screenshots ausfüllen, während Konfigurationen dokumentiert werden
