# Salesforce Lab — Support_Request__c Custom Object

## Environment
- Salesforce Developer Edition org (free)
- Org: orgfarm-6753f10b73-dev-ed.develop.salesforce.com
- Created: May 2026

## Custom Object: Support_Request__c
- API Name: `Support_Request__c`
- Record Name: Auto Number format `SR-{0000}`
- Deployment Status: Deployed

## Custom Fields
| Field Label | API Name | Data Type |
|---|---|---|
| Priority | Priority__c | Picklist (High, Medium, Low) |
| Environment | Environment__c | Text(255) |
| Status | Status__c | Picklist (Open, In Progress, Resolved) |

## Next Steps
- [ ] Create 5 sample Support Request records
- [ ] Walk each record through status lifecycle: Open → In Progress → Resolved
- [ ] Build a report: open requests grouped by priority

## Troubleshooting Notes
### "We've hit a snag" on list view
- **Cause:** Custom object has no Tab created, so it can't be added to app navigation
- **Fix:** Setup → Tabs → Custom Object Tabs → New → Select Support Request → Save
- Then add to app nav via App Launcher → pencil icon → Add More Items

### "Support Requests" not appearing in Add Nav Items search
- **Cause:** Tab doesn't exist yet — Salesforce requires a Tab before an object appears in nav search
- **Fix:** Create the Tab first (see above), then the object appears in nav search
