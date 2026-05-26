# Salesforce Support Demo Org — Lab Notes

## Environment
- Salesforce Developer Edition org (free — developer.salesforce.com)
- Signed up: May 2026

## What I Built

### Custom Object: Support_Request__c
- Created a custom object to model incoming support requests.
- Added fields:
  - `Priority__c` — Picklist (High, Medium, Low)
  - `Environment__c` — Text (Production, Staging, Development)
  - `Status__c` — Picklist (Open, In Progress, Resolved)
- Configured page layout to display all fields clearly.

### Sample Records
- Logged 5 mock support requests with varying priority and environment.
- Manually walked each record through status transitions: Open → In Progress → Resolved.
- Simulates the kind of case lifecycle a TSE manages daily.

### Reports & Dashboards
- Built a report showing open support requests grouped by Priority.
- Confirmed High priority cases surface at the top of the queue.

## Key Takeaways
- Salesforce custom objects map closely to how support teams model ticket data.
- Status lifecycle and priority fields mirror ITSM concepts from ServiceNow.
- Reports make it easy to surface a "queue view" similar to a fraud review queue in SQL.

## Next Steps
- [ ] Build a Flow automation for follow-up task creation on High priority records.
- [ ] Add a dashboard component for open vs. resolved case counts.
- [ ] Explore connecting Salesforce Cases to ServiceNow Incidents via REST.
