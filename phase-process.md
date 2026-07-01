---
layout: page
title: PHASE Process
permalink: /phase-process.html
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# The PHASE Process

**PHASE** stands for **Process-oriented Hazard Analysis for AI Systems**.

PHASE adapts **System Theoretic Process Analysis (STPA)** for AI systems by focusing on system-level hazards that emerge across AI development, deployment, and operation.

---

## Why PHASE?

Many AI harm analysis methods focus on isolated components such as:

- datasets
- models
- metrics
- user interactions
- deployment contexts

PHASE instead analyzes AI systems as **sociotechnical systems**, where harms can emerge from interactions among technical components, human actors, organizational processes, and institutional constraints.

---

## Step 1: Identify the Purpose of the Analysis

The first step defines:

- losses
- system boundaries
- hazards

In PHASE, losses are broadened beyond traditional safety-critical harms to include:

### Safety-critical losses

Examples:

- loss of life
- injury
- physical harm

### Performance-related losses

Examples:

- loss of efficiency
- loss of quality
- loss of reputation
- loss of money

### Sociotechnical losses

Examples:

- loss of privacy
- loss of autonomy
- loss of creativity
- loss of diversity
- loss of accessibility

PHASE also encourages analysts to define system boundaries around **development and use processes**, rather than around the AI model alone.

---

## Step 2: Create Control Diagrams

The second step maps the system using control structures.

A control diagram includes:

- controllers
- controlled processes
- control actions
- feedback
- inputs
- outputs
- process models
- control algorithms

In AI systems, controllers may include:

- developers
- data scientists
- responsible AI analysts
- product managers
- users
- clinicians
- artists
- AI models
- reinforcement learning agents
- safety filters
- automated decision systems

PHASE treats AI components as **context-dependent**. A model may be a controlled process in one setting and a controller in another.

---

## Step 3: Identify Unsafe Control Actions

The third step identifies control actions that could lead to hazards.

A control action may be unsafe when it is:

1. provided when it should not be provided
2. not provided when it should be provided
3. provided too early, too late, or in the wrong order
4. stopped too soon or applied too long

In PHASE, unsafe control actions often arise from:

### Functional failures

For example, an insulin pump fails to release the required dose.

### Poor design decisions or misuse

For example, a developer chooses an inappropriate safety filter threshold.

### Communication or coordination breakdowns

For example, a model development team receives incomplete safety requirements before deployment.

---

## Step 4: Identify Loss Scenarios

The fourth step identifies the causal scenarios that could lead to unsafe control actions.

Loss scenarios may involve:

- missing feedback loops
- incorrect mental models
- incorrect process models
- poor communication
- inadequate evaluation metrics
- technical malfunction
- changing or emerging model capabilities

PHASE adds special attention to hazards that arise over time as AI systems are retrained, updated, adapted, or used in new contexts.

---

## What PHASE Enables

PHASE supports analysts by enabling:

1. **System-level hazard detection**
2. **Explicit consideration of social factors**
3. **Traceable accountability chains**
4. **Ongoing monitoring of emerging hazards**
