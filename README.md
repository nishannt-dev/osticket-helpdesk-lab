# NexaCore IT Helpdesk Lab

![osTicket](https://img.shields.io/badge/osTicket-v1.18-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Windows%2010-lightgrey?style=flat-square)
![Server](https://img.shields.io/badge/Server-XAMPP-orange?style=flat-square)
![Email](https://img.shields.io/badge/Email-Hostinger%20IMAP%2FSMTP-red?style=flat-square)

## Overview

This project documents the design and deployment of a fully functional IT helpdesk environment for a simulated company called **NexaCore Technologies**. I built this from scratch to develop hands-on experience with real helpdesk operations including ticket triage, SLA management, agent workflows, email integration, and technical documentation.

The system was configured on a local server using XAMPP, with a real email pipeline connected through Hostinger using IMAP and SMTP. Every ticket in this project was handled end-to-end: submitted by an end user, picked up by a Tier 1 or Tier 2 agent, documented with internal notes, and resolved with a reply to the user.

---

## Environment

| Component | Details |
|---|---|
| Helpdesk Platform | osTicket v1.18 |
| Local Server | XAMPP (Apache + MySQL + PHP) |
| Operating System | Windows 10 |
| Email Integration | Hostinger (IMAP port 993 / SMTP port 465) |
| Database | MySQL via phpMyAdmin |

---

## What Was Built

- Real email-to-ticket pipeline using Hostinger IMAP/SMTP
- 3 SLA tiers (SEV-1 Critical, SEV-2 High, SEV-3 Low) with defined response and resolution targets
- 2 departments: IT Support (Tier 1) and Systems Administration (Tier 2)
- 4 agents with role-based access across departments
- 5 end users with company email addresses (@nexacore.in)
- 5 custom help topics mapped to real IT issue categories
- 10 tickets resolved end-to-end with full thread documentation
- Internal notes, resolution replies, and SLA tracking on every ticket

---

## Team Structure

### Agents

| Name | Username | Role | Department |
|---|---|---|---|
| Nishant | nishant | Admin / IT Administrator | Systems Administration |
| James Carter | jcarter | Support Agent | IT Support (Tier 1) |
| Maria Lopez | mlopez | Support Agent | IT Support (Tier 1) |
| Tom Baker | tbaker | Support Agent | Maintenance |

### End Users

| Name | Email |
|---|---|
| Sandra Hill | sandra.hill@nexacore.in |
| Tom Baker | tbaker@nexacore.in |
| James Reed | james.reed@nexacore.in |
| Maria Hill | maria.hill@nexacore.in |
| David Patel | david.patel@nexacore.in |

---

## SLA Plans

| Plan | Grace Period | Use Case |
|---|---|---|
| SEV-1 | 1 hour | Critical issues affecting business operations |
| SEV-2 | 4 hours | High priority issues affecting individual productivity |
| SEV-3 | 8 hours | Low priority requests and minor issues |

---

## Help Topics

- Hardware Malfunction
- Network / VPN Issue
- New Employee Setup
- Password Reset
- Software / Application Error

---

## Tickets Resolved

| Ticket | Subject | User | Priority | Agent | Status |
|---|---|---|---|---|---|
| #478022 | Cannot log into my computer | Sandra Hill | SEV-3 | James Carter | Closed |
| #746084 | Office printer showing offline | Tom Baker | SEV-3 | Maria Lopez | Closed |
| #883563 | VPN not connecting from home | James Reed | SEV-2 | James Carter | Closed |
| #724388 | Outlook emails not loading | Maria Hill | SEV-2 | Maria Lopez | Closed |
| #462201 | New employee IT setup required | David Patel | SEV-1 | Nishant | Closed |
| #824799 | Computer running very slowly | Tom Baker | SEV-3 | James Carter | Closed |
| #746836 | Need Adobe Acrobat installed | Sandra Hill | SEV-3 | Maria Lopez | Closed |
| #876541 | Second monitor not working after desk move | James Reed | SEV-2 | Nishant | Closed |
| #465208 | Cannot access shared network drive | Maria Hill | SEV-2 | Nishant | Closed |
| #971697 | Laptop not charging | David Patel | SEV-2 | James Carter | Closed |

---

## Skills Demonstrated

- Helpdesk platform deployment and administration (osTicket)
- Email server integration using IMAP and SMTP protocols
- SLA policy design and enforcement
- Ticket triage, prioritization, and escalation workflows
- Role-based access control and department configuration
- Technical documentation and internal note writing
- End-to-end ticket lifecycle management
- Remote troubleshooting across hardware, software, and network issues

---

## Documentation

- [SLA Policy](./docs/sla-policy.md)
- [Ticket Lifecycle](./docs/ticket-lifecycle.md)
- [New Employee Onboarding Checklist](./docs/onboarding-checklist.md)

---

## Ticket Case Studies

- [#478022 - Cannot log into my computer](./tickets/ticket-478022.md)
- [#746084 - Office printer showing offline](./tickets/ticket-746084.md)
- [#883563 - VPN not connecting from home](./tickets/ticket-883563.md)
- [#724388 - Outlook emails not loading](./tickets/ticket-724388.md)
- [#462201 - New employee IT setup required](./tickets/ticket-462201.md)
- [#824799 - Computer running very slowly](./tickets/ticket-824799.md)
- [#746836 - Need Adobe Acrobat installed](./tickets/ticket-746836.md)
- [#876541 - Second monitor not working after desk move](./tickets/ticket-876541.md)
- [#465208 - Cannot access shared network drive](./tickets/ticket-465208.md)
- [#971697 - Laptop not charging](./tickets/ticket-971697.md)

---

## Screenshots

See the [/screenshots](./screenshots/) folder for full documentation of the live system including the agent dashboard, closed ticket queue, individual ticket threads, SLA configuration, department setup, and the end-user portal.
