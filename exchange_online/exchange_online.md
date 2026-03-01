# Exchange Online

## Purpose

This folder documents Exchange Online configuration: mail flow, mailbox policies, shared mailboxes, distribution lists, and email security. It focuses on operational reliability and security rather than feature exploration.

---

## Goals

- Establish reliable mail flow (inbound, outbound, internal)
- Configure mailbox policies and retention
- Implement shared mailboxes and distribution groups
- Document email security policies (anti-spam, anti-malware, transport rules)

---

## Planned Structure

```
exchange_online/
│
├── mail_flow.md                    Inbound/outbound connectors, mail flow rules
├── mailbox_policies.md             Retention, archiving, litigation hold
├── shared_resources.md             Shared mailboxes, room mailboxes, equipment
├── distribution_groups.md          Distribution lists, dynamic groups, moderation
├── email_security.md               Anti-spam, anti-malware, transport rules
├── mobile_device_access.md         ActiveSync policies, device management
├── screenshots/                    Configuration evidence
└── scripts/
    ├── New-SharedMailbox.ps1       Shared mailbox creation automation
    ├── Get-MailFlowReport.ps1      Mail flow statistics and diagnostics
    └── Set-RetentionPolicy.ps1     Retention policy configuration
```

---

## Key Deliverables

| Deliverable | Description | Status |
|:------------|:------------|:------:|
| **Mail Flow Configuration** | Connectors, transport rules, mail routing documented | ☐ |
| **Mailbox Policies** | Retention policies, archiving, litigation hold configured | ☐ |
| **Shared Resources** | Shared mailboxes, room mailboxes, equipment mailboxes created | ☐ |
| **Email Security** | Anti-spam, anti-malware, transport rules (DLP, encryption) | ☐ |
| **Mobile Access** | ActiveSync policies, device access rules configured | ☐ |

---

## Decision Log Topics

- Retention policy: archive vs. delete (compliance vs. storage cost)
- Shared mailbox permissions: full access vs. send-as vs. send-on-behalf
- Mail flow rules: when to use transport rules vs. DLP policies
- Mobile device access: allow all vs. conditional access-based restrictions

---

## Operational Context

Email is **mission-critical**. Every configuration here is documented with the understanding that mail flow disruption is unacceptable. This is not about enabling every feature — it's about ensuring reliable, secure email delivery.

---

---

# Exchange Online (Deutsch)

## Zweck

Dieser Ordner dokumentiert die Exchange Online-Konfiguration: Mailfluss, Postfach-Richtlinien, freigegebene Postfächer, Verteilerlisten und E-Mail-Sicherheit. Der Fokus liegt auf operativer Zuverlässigkeit und Sicherheit statt Feature-Erkundung.

---

## Ziele

- Etabliere zuverlässigen Mailfluss (eingehend, ausgehend, intern)
- Konfiguriere Postfach-Richtlinien und Aufbewahrung
- Implementiere freigegebene Postfächer und Verteilungsgruppen
- Dokumentiere E-Mail-Sicherheitsrichtlinien (Anti-Spam, Anti-Malware, Transportregeln)

---

## Schlüssel-Lieferobjekte

| Lieferobjekt | Beschreibung | Status |
|:------------|:------------|:------:|
| **Mailfluss-Konfiguration** | Konnektoren, Transportregeln, Mail-Weiterleitung dokumentiert | ☐ |
| **Postfach-Richtlinien** | Aufbewahrungsrichtlinien, Archivierung, Rechtsbestand konfiguriert | ☐ |
| **Gemeinsame Ressourcen** | Freigegebene Postfächer, Raumpostfächer, Ausrüstungspostfächer erstellt | ☐ |
| **E-Mail-Sicherheit** | Anti-Spam, Anti-Malware, Transportregeln (DLP, Verschlüsselung) | ☐ |
| **Mobiler Zugriff** | ActiveSync-Richtlinien, Gerätezugriffsregeln konfiguriert | ☐ |

---

## Entscheidungsprotokoll-Themen

- Aufbewahrungsrichtlinie: Archivieren vs. Löschen (Compliance vs. Speicherkosten)
- Freigegebene Postfach-Berechtigungen: Vollzugriff vs. Senden als vs. Senden im Auftrag
- Mailflussregeln: wann Transportregeln vs. DLP-Richtlinien verwendet werden
- Mobiler Gerätezugriff: Alle zulassen vs. Conditional Access-basierte Einschränkungen
