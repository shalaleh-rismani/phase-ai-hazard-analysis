---
layout: page
title: Templates
permalink: /templates.html
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# PHASE Templates

This page provides lightweight templates for conducting a PHASE analysis.

You can copy these tables into a document, spreadsheet, or repository issue template.

---

## Template 1: Analysis Purpose

| Field | Description |
|---|---|
| AI system name |  |
| Domain |  |
| Intended use |  |
| Stakeholders |  |
| System boundary |  |
| Analyst(s) |  |
| Date |  |

---

## Template 2: Losses

| Loss ID | Loss description | Loss type | Affected stakeholder(s) |
|---|---|---|---|
| L1 |  | Safety-critical / Performance-related / Sociotechnical |  |
| L2 |  | Safety-critical / Performance-related / Sociotechnical |  |
| L3 |  | Safety-critical / Performance-related / Sociotechnical |  |

---

## Template 3: Hazards

| Hazard ID | Hazard description | Related loss(es) | System boundary |
|---|---|---|---|
| H1 |  |  |  |
| H2 |  |  |  |
| H3 |  |  |  |

---

## Template 4: Control Diagram Elements

| Element | Role | Description |
|---|---|---|
| Controller |  |  |
| Controlled process |  |  |
| Control action |  |  |
| Feedback |  |  |
| Input |  |  |
| Output |  |  |
| Process model |  |  |
| Control algorithm |  |  |

---

## Template 5: Unsafe Control Actions

| UCA ID | Controller | Control action | Unsafe type | Context | Related hazard |
|---|---|---|---|---|---|
| UCA1 |  |  | Provided when unsafe / Not provided when needed / Too early or too late / Stopped too soon or applied too long |  |  |
| UCA2 |  |  | Provided when unsafe / Not provided when needed / Too early or too late / Stopped too soon or applied too long |  |  |

---

## Template 6: Loss Scenarios

| Scenario ID | Related UCA | Loss scenario | Causal factor | Possible mitigation |
|---|---|---|---|---|
| LS1 |  |  | Missing feedback loop / Incorrect process model / Technical malfunction / Emerging capability / Coordination issue |  |
| LS2 |  |  | Missing feedback loop / Incorrect process model / Technical malfunction / Emerging capability / Coordination issue |  |

---

## Template 7: Mitigation and Monitoring Plan

| Hazard or scenario | Mitigation | Owner | Monitoring method | Review frequency |
|---|---|---|---|---|
|  |  |  |  |  |
|  |  |  |  |  |

---

## Suggested Workflow

1. Define the AI system and system boundary.
2. Identify losses.
3. Identify hazards.
4. Draw the control diagram.
5. Identify unsafe control actions.
6. Identify loss scenarios.
7. Define mitigations.
8. Assign accountability.
9. Revisit the analysis as the system changes.
