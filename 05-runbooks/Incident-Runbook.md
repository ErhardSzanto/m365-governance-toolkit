# Incident Runbook (M365)

## Purpose
Provide a consistent approach to handling incidents affecting Microsoft 365 services.

## Examples
- Users cannot access Teams/SharePoint/OneDrive
- Permission/access failures
- External sharing behaving unexpectedly
- Suspected data leakage or DLP-related user impact

## Roles
- **Service Desk:** first-line triage, user comms, ticket ownership
- **M365 Team:** technical investigation, mitigation, vendor escalation
- **Security/Compliance:** involved for suspected data/security events
- **Product Manager:** informed for major incidents and user impact

## Severity levels
- **Sev 1:** widespread outage or major business impact
- **Sev 2:** partial outage / high impact to key groups
- **Sev 3:** limited impact / workaround exists

## First response checklist (within 15–30 minutes)
1. Confirm scope: who/what/where (service, location, user groups)
2. Check known service health (M365 admin health / internal monitoring)
3. Collect evidence: error messages, screenshots, timestamps, affected user accounts
4. Identify workaround if possible
5. Communicate initial status (use Communication Templates)

## Investigation workflow
1. Reproduce or confirm symptoms
2. Identify whether issue is:
   - Microsoft service incident
   - configuration/policy change
   - identity/access issue
   - user/device-specific
3. Apply mitigation:
   - rollback recent change (if applicable)
   - temporary access change (controlled)
   - switch to workaround process
4. Escalate to Microsoft support if required

## Escalation triggers
- Potential data leakage or security event → Security/Compliance immediately
- Sev 1/2 lasting >60 minutes → management notification + update cadence

## Communication cadence
- Sev 1: every 30 minutes
- Sev 2: every 60 minutes
- Sev 3: as needed

## Resolution & closure
- Confirm service restored
- Notify users
- Document root cause and corrective actions
- If Sev 1/2: schedule a Post-Incident Review (PIR)

## Post-Incident Review (PIR)
- What happened (timeline)
- Root cause
- Impact assessment
- Corrective + preventative actions
- Backlog items created with owners and due dates
