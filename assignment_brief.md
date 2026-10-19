# Operations Analyst Practice Assignment

**Scenario:** Quarter-End Client Reporting Exception  
**Platforms:** Practifi CRM practice + Tamarac Reporting practice  
**Target time:** 45–60 minutes  
**Difficulty:** Early-career / intermediate beginner  
**Case:** C-2047  

## Business request

You work on the operations team at a **fictional** independent wealth management firm. Client Advisory is preparing quarterly reporting for the Anderson Family, but the expected assets under management recorded in Practifi CRM do not match the current value of the associated Tamarac reporting group. The client report is due to be distributed the following day.

**Objective:** Diagnose the discrepancy, record your findings, prevent inaccurate report distribution, and route the appropriate correction to the responsible operations team for approval. Do not directly modify custodial values or represent an unapproved correction as complete.

## Tasks

1. **Triage** — In the Practifi practice application, read Service Case C-2047 and the linked household record. Record the requested deadline and values you need to compare.
2. **Investigate** — In Tamarac, inspect reporting groups, account ownership, account market values, and reconciliation status. Identify the cause and affected account.
3. **Document** — In Case C-2047, select the correct root-cause category and affected account. Write a concise note covering evidence, quantification, client/reporting impact, and proposed correction/verification.
4. **Escalate** — Assign the case to the correct team and move it to a review/escalation state. Do **not** mark the underlying case resolved before authorized verification.
5. **Protect reporting** — In the Report Studio simulation, place any impacted quarterly report packets on hold and save an internal explanation for each.
6. **Conclude the investigation** — Mark the investigation task T-084 complete only when appropriate controls and escalation are in place.
7. **Evaluate** — Return to the **Assignment & Grading** tab and click **Check my work**. Aim for 8/8. Optionally export the practice account CSV and case summary.

## What a manager would evaluate

- Cross-system tracing between CRM household ownership and reporting-group membership.
- Correct quantification of mismatches, without confusing price movements with structural mapping errors.
- Distinguishing **custodial reconciliation** from **household/reporting-group accuracy**.
- Appropriate escalation, separation of duties and audit trail.
- Communication that states the issue, evidence, impact, next step and who owns it.
- Avoiding premature report distribution or case resolution.

## Bonus exercise

Find a **separate** exception related to data freshness in the Reconciliation Workbench. Describe why it is different from an incorrect reporting-group assignment and what you would verify next.

## Suggested interview debrief (2 minutes)

Explain what happened as if answering: **“Tell me about a time you found a data problem that affected another team's work. How would you investigate and prevent recurrence?”**

Structure your response around identifying the exception, tracing sources, protecting the customer, coordinating with system owners, and adding an automated exception check for future daily reporting.

---

### How to use the file

Download `wealth_operations_simulator.html`, double-click it, and use a current browser. The simulator runs locally without sign-in or internet access and keeps progress in the browser's local storage when available. **Reset practice** clears your simulated case updates and restarts the lab. The **Reveal instructor solution** button within the Assignment tab contains spoilers.

### Accuracy note

This is original educational practice software, not a product build or authorized depiction of a specific employer's implementation. Practifi and Tamarac interfaces, permissions, mappings, and processes vary by deployment. The simulated report hold is an educational workflow control, not an assertion that Tamarac uses that exact status or action. No data is sent to Practifi, Envestnet Tamarac, Freestone, custodians or any other third party.
