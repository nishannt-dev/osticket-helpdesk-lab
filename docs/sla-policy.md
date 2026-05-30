# NexaCore Technologies -- IT SLA Policy

**Document Version:** 1.0  
**Last Updated:** May 2026  
**Owner:** IT Administrator (Nishant)  
**Applies To:** All IT support tickets raised through the NexaCore helpdesk

---

## Purpose

This document defines the Service Level Agreements (SLAs) for all IT support requests handled by the NexaCore Technologies IT department. The goal is to ensure that all staff receive timely, consistent, and well-documented support regardless of issue type.

---

## Scope

This policy applies to all tickets submitted through the NexaCore IT helpdesk portal. It covers hardware issues, software problems, network and connectivity faults, access requests, and onboarding tasks.

---

## SLA Tiers

| Priority | Label | Grace Period | Typical Use Case |
|---|---|---|---|
| Critical | SEV-1 | 1 hour | Issues affecting business operations or a new hire start date |
| High | SEV-2 | 4 hours | Issues blocking individual productivity (VPN, monitor, network drive) |
| Low | SEV-3 | 8 hours | Non-urgent requests and minor issues (password reset, slow PC, printer) |

---

## SLA Definitions

### SEV-1 -- Critical
Reserved for issues that directly impact business continuity or are time-sensitive to a fixed deadline. Examples include new employee setup before a start date, complete system outages, or security incidents.

- Grace Period: 1 hour
- Assigned To: Systems Administration (Tier 2) by default
- Escalation: Immediate -- no Tier 1 handling

### SEV-2 -- High
Used for issues that prevent an individual employee from completing their core responsibilities. Examples include VPN failures, inaccessible network drives, and hardware failures at the workstation.

- Grace Period: 4 hours
- Assigned To: IT Support (Tier 1) with escalation path to Systems Administration
- Escalation: If unresolved within 2 hours, escalate to Tier 2

### SEV-3 -- Low
Applied to non-urgent requests that do not block the user from working entirely. Examples include password resets, software installation requests, slow computer performance, and printer issues.

- Grace Period: 8 hours
- Assigned To: IT Support (Tier 1)
- Escalation: If unresolved within 6 hours, flag to team lead

---

## Escalation Rules

- SEV-3 unresolved after 6 hours: flag to team lead
- SEV-2 unresolved after 2 hours: escalate to Tier 2 (Systems Administration)
- SEV-1: bypass Tier 1, assign directly to Tier 2 on creation
- Any ticket with a breach of SLA grace period must include a written explanation in the internal notes

---

## Business Hours

Monday to Friday, 9:00 AM to 6:00 PM  
After-hours support is available for SEV-1 issues only

---

## SLA Breach Procedure

If a ticket breaches its SLA grace period the following steps must be taken:

1. Agent must add an internal note explaining the reason for the breach
2. Team lead must be notified within 30 minutes of breach
3. Ticket must be escalated to the next tier if not already done
4. A post-resolution review note must be added before closing

---

## Ticket Closure Requirements

Before closing any ticket the agent must confirm:

- The user has been notified via a resolution reply
- The root cause has been documented in internal notes
- Any follow-up actions have been logged
- The correct SLA plan and help topic are assigned
