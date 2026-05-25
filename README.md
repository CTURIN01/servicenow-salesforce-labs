# ServiceNow & Salesforce Labs

Personal lab projects building hands-on experience with **ServiceNow** (ITSM) and **Salesforce** (CRM) — focused on workflows a Technical Support Engineer uses daily.

The goal is to document small, realistic exercises that justify listing these platforms on a resume with concrete examples instead of just tool names.

---

## Planned Labs

| Lab | Platform | Status |
|-----|----------|--------|
| Incident Workflow & Flow Designer Automation | ServiceNow | In Progress |
| Support Demo Org — Custom Objects & Reports | Salesforce | Planned |
| ServiceNow ⇄ Salesforce REST Integration | Both | Planned |

---

## Lab 1 — ServiceNow ITSM Incident Workflow

**Objective:** Practice core ITSM concepts and basic automation using a ServiceNow Personal Developer Instance.

**Planned work:**
- Customize the Incident form with additional troubleshooting fields.
- Practice full incident lifecycle: New → In Progress → On Hold → Resolved → Closed.
- Build a Flow Designer automation to auto-assign P1 incidents and send notifications.
- Write a short runbook documenting how a TSE would use this workflow.

**Artifacts (to be added):**
- `/servicenow/incident-workflow-notes.md`
- `/servicenow/screenshots/`

---

## Lab 2 — Salesforce Support Demo Org

**Objective:** Use a Salesforce Developer Edition org to model a small support process.

**Planned work:**
- Configure custom objects, fields, and validation rules for a support case workflow.
- Build reports and dashboards tracking open cases by priority and owner.
- Build a simple Flow automation for follow-up tasks or status updates.

**Artifacts (to be added):**
- `/salesforce/support-demo-notes.md`
- `/salesforce/screenshots/`

---

## Lab 3 — ServiceNow ⇄ Salesforce Integration (Future)

**Objective:** Mirror high-priority Salesforce cases into ServiceNow incidents via REST and sync status back.

**Artifacts (planned):**
- `/integration/architecture-notes.md`
- Example request/response payloads.

---

## Why This Repo Exists

Many TSE and DevOps/Support roles require familiarity with ServiceNow and Salesforce. Rather than listing tool names without experience, this repo documents real hands-on lab work so every resume claim has a concrete example behind it.

