# NexaCore Technologies -- Ticket Lifecycle

**Document Version:** 1.0  
**Last Updated:** May 2026  
**Owner:** IT Administrator (Nishant)

---

## Overview

This document explains how a support ticket moves through the NexaCore helpdesk system from the moment it is submitted by an end user to the moment it is closed by an agent. Understanding the full lifecycle ensures consistent handling and clear communication at every stage.

---

## Ticket Lifecycle Stages

```
User Submits Ticket
        |
        v
  [OPEN] -- Ticket created, SLA timer starts
        |
        v
  [ASSIGNED] -- Agent picks up ticket, reviews issue
        |
        v
  [IN PROGRESS] -- Agent begins troubleshooting, adds internal notes
        |
        v
   Resolved at Tier 1?
      /       \
    YES        NO
     |          |
     v          v
 [RESOLVED] [ESCALATED] -- Passed to Tier 2 (Systems Administration)
     |          |
     v          v
 Agent posts  Tier 2 agent troubleshoots
 resolution   and resolves
 reply            |
     |            v
     v        [RESOLVED]
  [CLOSED]        |
                  v
              [CLOSED]
```

---

## Stage Descriptions

### 1. Open
The ticket has been submitted by the user and is sitting in the queue unassigned. The SLA grace period timer begins the moment the ticket is created. All agents in the assigned department can see it.

### 2. Assigned
An agent has claimed the ticket and is reviewing the details. The agent should acknowledge the user within the SLA grace period by posting a reply or internal note confirming they are looking into it.

### 3. In Progress
Active troubleshooting is underway. The agent must document every step taken in the internal notes. This includes what was checked, what was found, any tools used, and any communication with the user. Internal notes are not visible to the end user.

### 4. Escalated
If the issue cannot be resolved at Tier 1 within the SLA window, the ticket is reassigned to the Systems Administration department (Tier 2). The escalating agent must leave a detailed internal note summarising what was tried before escalation.

### 5. Resolved
The issue has been fixed. The agent posts a resolution reply to the user explaining what was done and confirming the fix. The ticket status is changed to Resolved at this stage.

### 6. Closed
The ticket is marked Closed after the resolution reply has been sent. This stops the SLA timer and logs the final close date and time against the ticket.

---

## Agent Responsibilities at Each Stage

| Stage | Agent Action Required |
|---|---|
| Open | Claim the ticket promptly within SLA window |
| Assigned | Send acknowledgement reply or internal note to confirm pickup |
| In Progress | Log every troubleshooting step in internal notes |
| Escalated | Write full summary note before reassigning to Tier 2 |
| Resolved | Post clear resolution reply to the user |
| Closed | Confirm correct SLA plan, help topic, and department are set |

---

## Key Rules

- No ticket should sit in Open status without being assigned within the SLA grace period
- Internal notes must be written throughout troubleshooting, not just at the end
- Resolution replies must be written in plain language the user can understand
- Agents must never close a ticket without first posting a resolution reply to the user
- If a ticket is escalated, the original agent remains a collaborator and can be consulted
