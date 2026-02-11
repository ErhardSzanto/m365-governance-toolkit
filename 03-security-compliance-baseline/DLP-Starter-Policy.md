# DLP Starter Policy

## What we protect
Focus on common sensitive data types:
- Personal data (PII) such as IDs, bank details (where applicable)
- Health-like data (in healthcare contexts)
- Financial/contractual data where leakage would cause harm

## Where policies apply
- SharePoint Online
- OneDrive for Business
- Microsoft Teams
- Exchange Online (where applicable)

## Actions (starter approach)
Start with a staged rollout:
1. **Pilot mode (learning)**
   - Show policy tips (user education)
   - Log matches (measure false positives)
2. **Warn mode**
   - Warn users when sharing externally or storing in risky locations
   - Allow override with justification for Confidential only
3. **Block mode (high risk)**
   - Block external sharing for Highly Confidential content
   - Block anonymous links for sensitive content

## Tuning plan
- Review alerts weekly in the first month
- Identify top false positives and adjust conditions
- Update user guidance based on real incidents
- Move from Warn → Block only after stable results
