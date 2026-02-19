# Microsoft 365 Engineer – Learning Roadmap

**Zielrolle:** Junior Microsoft 365 Engineer  
**Zielzustand:** Betriebsfähig, sicherheitsbewusst, dokumentationsstark  
**Zeithorizont:** ca. 8–10 Wochen (neben Job realistisch)

Diese Roadmap fokussiert sich auf **Betrieb, Identität, Security und Troubleshooting** – nicht auf reine Toolbedienung.

---

## Phase 0 – Fundament & Umgebung (Woche 1)

### Ziel
Kontrolle über die eigene Microsoft-365-Lernumgebung gewinnen.

### Inhalte
- Tenant-Grundlagen
- Admin-Rollen & Verantwortlichkeiten
- Secure Defaults verstehen
- Naming Conventions & Dokumentation

### Praxis
- Eigenen Tenant dokumentieren
- Global Admin vs. Helpdesk Admin abgrenzen
- Secure Defaults bewusst bewerten (nicht blind aktiv)

### Microsoft Learn
- Microsoft 365 Fundamentals  
  https://learn.microsoft.com/training/paths/microsoft-365-fundamentals/
- Describe cloud concepts  
  https://learn.microsoft.com/training/paths/describe-cloud-concepts/

### Deliverables
- `tenant_setup/README.md`
- Diagramm: Rollen & Zugriffe

---

## Phase 1 – Identity & Access Management (Woche 2–3)

### Ziel
Identität als Sicherheitskern von Microsoft 365 verstehen und steuern.

### Inhalte
- Entra ID (Azure AD) Grundlagen
- Benutzer-, Gruppen- und Lizenzmanagement
- MFA-Strategien
- Conditional Access (Einführung)
- Break-Glass-Accounts

### Praxis
- 5 Test-User anlegen
- Gruppenbasierte Lizenzvergabe
- MFA für externe Zugriffe erzwingen
- Legacy Authentication blockieren
- 1 Login absichtlich brechen und analysieren

### Microsoft Learn
- Manage identities and access in Microsoft Entra ID  
  https://learn.microsoft.com/training/paths/manage-identities-and-access/
- Secure your cloud identity  
  https://learn.microsoft.com/training/paths/secure-cloud-identity/

### Deliverables
- `identity/`
- Incident-Dokument: gesperrter Benutzer

---

## Phase 2 – Core Services: Exchange, Teams & SharePoint (Woche 4)

### Ziel
Produktivitätsdienste als Infrastruktur verstehen.

### Exchange Online
- Benutzer- & Shared Mailboxes
- Kalenderfreigaben
- Mail Flow Rules
- Spam- & Phishing-Grundlagen

### Teams & SharePoint
- Teams ↔ SharePoint Zusammenhang
- Berechtigungsmodelle
- Externes Sharing
- OneDrive Restore

### Microsoft Learn
- Manage and troubleshoot Microsoft Teams  
  https://learn.microsoft.com/training/paths/manage-troubleshoot-microsoft-teams/
- Configure SharePoint and OneDrive  
  https://learn.microsoft.com/training/paths/configure-sharepoint-onedrive/

### Deliverables
- `exchange_online/`
- `teams_and_sharepoint/`

---

## Phase 3 – Security & Governance (Woche 5)

### Ziel
Kein Risiko darstellen – sondern Risiken erkennen und reduzieren.

### Inhalte
- Microsoft Secure Score
- Defender for Office 365 (Grundlagen)
- Audit Logs
- Security Defaults vs. Custom Policies

### Praxis
- Secure Score analysieren
- 3 gezielte Verbesserungen umsetzen
- Vorher/Nachher dokumentieren

### Microsoft Learn
- Implement security in Microsoft 365  
  https://learn.microsoft.com/training/paths/implement-security-microsoft-365/
- Protect against threats with Microsoft Defender  
  https://learn.microsoft.com/training/paths/protect-against-threats-microsoft-365-defender/

### Deliverables
- `security_basics/secure_score_case.md`

---

## Phase 4 – Endpoint & Intune Management (Woche 6)

### Ziel
Geräte als Zugriffs- und Sicherheitsfaktor steuern.

### Inhalte
- Intune Enrollment
- Compliance vs. Configuration Policies
- BitLocker
- OneDrive Known Folder Move
- Device Non-Compliance

### Praxis
- 1 Gerät compliant
- 1 Gerät absichtlich blockieren
- Zugriff analysieren

### Microsoft Learn
- Manage devices with Microsoft Intune  
  https://learn.microsoft.com/training/paths/manage-devices-with-microsoft-intune/

### Deliverables
- `endpoint_management/`

---

## Phase 5 – Automation & PowerShell (Woche 7)

### Ziel
Administrative Effizienz steigern – nicht „skripten um des Skriptens willen“.

### Inhalte
- Microsoft Graph PowerShell
- Bulk-User-Anlage
- Lizenz- & Gruppenreports
- MFA-Status auslesen

### Praxis
- Mindestens 3 produktionsnahe Skripte
- Lesbare Struktur + Kommentare

### Microsoft Learn
- Automate Microsoft 365 administration with PowerShell  
  https://learn.microsoft.com/training/paths/automate-microsoft-365-administration/

### Deliverables
- `powershell/README.md`
- Skripte mit Use-Case-Beschreibung

---

## Phase 6 – Incident Simulation & Troubleshooting (Woche 8)

### Ziel
Arbeiten wie im echten Betrieb.

### Simulierte Incidents
- Benutzer kann sich nicht anmelden (CA)
- Teams funktioniert, Mail nicht (Lizenz)
- OneDrive Sync defekt
- Gerät non-compliant

### Struktur pro Incident
1. Ausgangslage  
2. Symptom  
3. Hypothese  
4. Lösung  
5. Prävention  

### Microsoft Learn
- Troubleshoot Microsoft 365 issues  
  https://learn.microsoft.com/training/paths/troubleshoot-microsoft-365/

### Deliverables
- `incidents_and_troubleshooting/`

---

## Phase 7 – Portfolio & Bewerbungsreife (Woche 9–10)

### Ziel
Erfahrung sichtbar machen.

### Inhalte
- Top-3-Projekte auswählen
- Entscheidungsketten dokumentieren
- README auf Recruiter-Niveau

### Bonus
- „Lessons Learned“
- „Was würde ich beim nächsten Mal anders machen?“

---

## Abschlussziel

Nach Abschluss dieser Roadmap kannst du:
- einen Microsoft-365-Tenant betreiben
- Identität und Zugriffe absichern
- typische Incidents analysieren und lösen
- deine Entscheidungen fachlich begründen

Zertifikate sind optional. **Verständnis ist Pflicht.**
