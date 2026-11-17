# NexaPoint Employee Onboarding Process Improvement

**Project type:** Self-directed project simulation  
**Role:** Project Coordinator / Business Analyst  
**Scenario organisation:** NexaPoint Solutions Ltd. (fictional)  
**Tools:** Jira, Excel, Google Forms, Google Sheets, Zapier, Gmail, Word/Google Docs, Draw.io

## Project overview

This portfolio project explores how a growing technology-services company could improve its employee onboarding process from offer acceptance through the employee's first 30 days.

The fictional scenario assumes that onboarding can be affected by late document submission, unclear ownership, delayed equipment and system access, inconsistent orientation activities and fragmented communication between HR, IT, Procurement, Finance and hiring managers.

The project documents a proposed process improvement and includes a working automation demonstration.

> **Important:** NexaPoint is fictional. The company context and operational problems are scenario assumptions, not verified client findings. No real employees were onboarded and no organisational implementation or measured business improvement is claimed.

## Problem

The proposed current-state process is fragmented. Departments may be engaged late, responsibilities and handoffs may be unclear, and HR may have limited visibility of outstanding preparation tasks. These conditions can contribute to delays in equipment, system access, documentation and orientation.

## Proposed solution

Design a coordinated onboarding workflow that:

- Starts when an offer is accepted and the employee's start date is confirmed.
- Captures consistent onboarding information through a standard request form.
- Makes departmental responsibilities, owners and due dates visible.
- Involves IT, Procurement and Finance early where required.
- Tracks outstanding tasks, risks, issues and onboarding milestones.
- Uses automated notifications to reduce manual follow-up.

## My role

I approached the simulation as a combined Project Coordinator / Business Analyst. My work included:

- Stakeholder identification and discovery questions.
- AS-IS process documentation.
- Gap and root-cause analysis.
- TO-BE process design.
- Project brief, objectives and proposed success measures.
- Six-week implementation plan, task breakdown and schedule.
- Jira Epic, tasks, workflow statuses, timeline and dependencies.
- Proposed RACI matrix.
- Risk register and issue log.
- Monitoring and evaluation approach.
- Zapier automation design and testing.

## Methods and project controls

- Stakeholder discovery and requirements documentation.
- AS-IS / TO-BE process analysis.
- Gap analysis and root-cause exploration.
- Work breakdown and milestone planning.
- Dependency mapping and schedule tracking.
- RACI responsibility assignment.
- Likelihood × impact risk scoring.
- Issue ownership, action tracking and escalation.
- Pilot monitoring and proposed success measures.

## Automation demonstration

### Tools

- **Google Forms:** captures a new employee onboarding request.
- **Google Sheets:** stores form responses through the native Forms-to-Sheets connection.
- **Zapier:** detects a new form response and controls notification routing.
- **Gmail:** sends the departmental notifications.

### Workflow

1. A new Google Forms response triggers the Zap.
2. Google Forms automatically records the response in its linked Google Sheet.
3. Gmail sends an HR notification for every new request.
4. The IT path sends a notification when **equipment is required OR system access is required**.
5. The Procurement path sends a notification when **equipment is required**.

The IT condition uses OR logic because either requirement is enough to involve IT. Procurement is notified only when equipment is required.

### Testing and limitations

The Google Forms trigger and Gmail actions were tested with fictional form submissions. Dynamic form fields were mapped into the email body. A duplicate-row issue was identified and corrected by removing a redundant Google Sheets “Create Spreadsheet Row” action, because Google Forms already writes each response to the linked sheet.

The user's own Gmail address was used to simulate HR, IT and Procurement recipients. This demonstrates the routing logic but does not verify delivery to real departmental mailboxes, organisational permissions, production security or business outcomes. A real rollout would require approved recipient addresses, privacy/security review and end-to-end testing of all decision combinations.

## Tools used

| Tool | Purpose |
|---|---|
| Jira | Epic, task board, statuses, timeline and dependencies |
| Excel | Project tracker, Gantt, milestones, dependencies, resources and risk/issue logs |
| Google Forms | Onboarding request capture |
| Google Sheets | Form response register |
| Zapier | Trigger and conditional automation |
| Gmail | Email notifications |
| Word / Google Docs | Project documentation |
| Draw.io | Process diagrams |

## Deliverables

- Project brief and proposed success measures.
- Stakeholder register and discovery questions.
- AS-IS process documentation.
- Gap and root-cause analysis.
- TO-BE process design.
- Six-week implementation plan.
- Jira project board and timeline.
- RACI matrix.
- Risk register and issue log.
- Project tracker and Gantt workbook.
- Automation prototype and test evidence.
- Final case study.

## Proposed success measures

Potential measures include mandatory onboarding tasks completed on time, equipment readiness by start date, system access readiness, document completion, orientation completion and stakeholder feedback.

A working target such as 90% of mandatory tasks completed on time may be proposed for a pilot, but it is not an achieved result. Baseline and post-implementation data would be required to evaluate improvement.



## Portfolio note

This project is a learning and portfolio simulation. It demonstrates planning, analysis, documentation and a tested automation prototype. It should not be described as a completed client implementation or as having produced measured operational savings.
