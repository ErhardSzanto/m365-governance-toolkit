# Security & Compliance Baseline (M365)

## MFA expectation
- MFA is required for:
  - All admin roles (mandatory)
  - All users (preferred baseline)
- Conditional access / security defaults should enforce MFA wherever possible.

## Privileged access (least privilege)
- Admin roles are assigned minimally and reviewed regularly.
- Use separate admin accounts where practical.
- Time-bound elevation is preferred (where available).

## Logging & auditing
- Audit logging should be enabled.
- Monitor key events:
  - privilege changes
  - external sharing events
  - DLP policy matches
  - risky sign-ins (where available)

## Data classification (labels)
- All important documents should use sensitivity labels:
  - Public / Internal / Confidential / Highly Confidential
- Default label guidance must be published to users.

## DLP principle
- DLP policies reduce accidental leakage by:
  - warning users
  - blocking risky sharing
  - allowing override with justification only where appropriate
- Policies should start “light” and be tuned based on false positives.
