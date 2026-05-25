# ServiceNow ⇄ Salesforce Integration Notes

## Objective
Mirror high-priority Salesforce cases into ServiceNow incidents via REST API and sync status back.

## Planned Architecture
- Salesforce Case (high priority) → REST callout → ServiceNow Incident created
- ServiceNow Incident resolved → REST callout → Salesforce Case status updated

## Steps to Complete
- [ ] Identify REST API endpoints for both platforms
- [ ] Document authentication method (OAuth / API key)
- [ ] Map Salesforce Case fields to ServiceNow Incident fields
- [ ] Build and test payloads
- [ ] Document architecture diagram

## Notes
_(to be filled in during lab)_
