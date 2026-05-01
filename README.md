# NIL Deal Process: How a College Athlete Completes an NIL Deal from Outreach to Payment

A BPMN analysis of the Name, Image, and Likeness (NIL) deal process for college athletes — from initial brand outreach through compliance approval to final payment.

---

## Table of Contents

- [Overview](#overview)
- [The Process](#the-process)
- [Current Inefficiencies](#current-inefficiencies)
- [BPMN Analysis Findings](#bpmn-analysis-findings)
- [Recommendations](#recommendations)

---

## Overview

NIL (Name, Image, and Likeness) has become a major part of college athletics, allowing student-athletes to earn money through brand partnerships, social media, and sponsorships. What was once a multi-billion-dollar marketplace operating under strict NCAA guidelines has rapidly evolved — including recent rule changes that now allow schools themselves to pay NIL money, leading to roster caps on teams.

This project maps the full NIL deal workflow using BPMN (Business Process Model and Notation) to surface inefficiencies and propose improvements. The key stakeholders in this process are:

- **Student-Athlete**
- **Brand / Company**
- **Agent** *(applies to some athletes)*
- **School Compliance Office**

---

## The Process

1. **Identification** — A brand identifies an athlete, or an athlete seeks out an NIL opportunity.
2. **Outreach & Evaluation** — The brand reaches out; the athlete evaluates whether the opportunity is worth pursuing.
3. **Negotiation** — Both parties negotiate terms: payment amount, expectations, and timelines.
4. **Compliance Submission** — The deal is submitted to the school's compliance office to ensure it follows NCAA and institutional rules.
5. **Contract Finalization** — Once approved, the contract is signed and finalized.
6. **Deliverable Completion** — The athlete completes the required deliverables (posts, appearances, content, etc.).
7. **Verification & Payment** — The brand verifies the work and issues payment.
8. **Recording** — The completed deal is officially recorded by compliance.

---

## Current Inefficiencies

### Compliance Approval
- Athletes sometimes complete a deal *before* submitting it for compliance approval.
- Each agreement is often negotiated from scratch, creating variability in contract terms and timelines.
- Unclear submission requirements lead to incomplete or incorrect filings, forcing the process to loop back for revision — especially problematic when deals are time-sensitive.

### Payment Phase
- No standardized system exists for verifying deliverable completion or enforcing payment timelines.
- Poorly defined expectations earlier in the process lead to disputes at the payment stage.
- Communication between athlete and brand often breaks down after deliverables are submitted.

---

## BPMN Analysis Findings

Modeling the NIL process as a BPMN diagram revealed several hidden issues:

- **Athlete as central coordinator** — The athlete bears responsibility for nearly every step: evaluating opportunities, negotiating, submitting to compliance, completing deliverables, and following up on payment. This concentration of responsibility increases the risk of delays and errors, particularly for athletes without business experience.

- **Multiple decision loops** — The negotiation stage loops back if both parties don't agree; the compliance stage loops back if a deal is rejected. These loops are rarely formalized in practice, but modeling them reveals how repetitive and time-consuming the process can become.

- **Invisible wait time** — Delays between steps (e.g., after compliance submission, or between deliverable completion and payment) are not visible in day-to-day operations but become clear when the process is fully mapped. These gaps highlight where efficiency and transparency are lacking.

---

## Recommendations

1. **NIL Education** — Universities should proactively educate athletes on the full NIL process. Many athletes are unaware of compliance requirements until they're already in a deal.

2. **Centralized Digital Platform** — Each school should implement a centralized platform for submitting and tracking NIL deals directly to compliance. This would reduce delays caused by incomplete submissions and give all stakeholders real-time visibility into deal status.

3. **Standardized Contract Templates** — Pre-approved contract templates with clear deliverable definitions and payment timelines would reduce negotiation variability and compliance review time.

These improvements would make the NIL process more efficient, transparent, and manageable for athletes, brands, agents, and compliance offices alike.

---

## Diagram

> BPMN process diagram available in the project files (`Untitled Diagram.drawio.svg`).

---

*Project by Nia Adamuni — May 2025*
