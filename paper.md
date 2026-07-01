---
layout: page
title: Paper
permalink: /paper.html
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# Paper

## From Silos to Systems: Process-Oriented Hazard Analysis for AI Systems

**Authors:** Shalaleh Rismani, Roel Dobbe, AJung Moon

This paper translates **System Theoretic Process Analysis (STPA)** for analyzing AI development and operation processes. It introduces **PHASE**, a process-oriented hazard analysis guideline for AI systems.

<div class="button-row">
  <a class="button" href="{{ '/assets/paper.pdf' | relative_url }}">Download PDF</a>
  <a class="button" href="{{ '/citation.html' | relative_url }}">Citation</a>
</div>

---

## Abstract

To effectively address potential harms from Artificial Intelligence (AI) systems, it is essential to identify and mitigate system-level hazards. Current analysis approaches focus on individual components of an AI system, like training data or models, in isolation, overlooking hazards from component interactions or how they are situated within a company's development process. To this end, we draw from the established field of system safety, which considers safety as an emergent property of the entire system. In this work, we translate System Theoretic Process Analysis (STPA) - a recognized system safety framework - for analyzing AI development and operation processes. We focus on systems that rely on machine learning algorithms and conduct STPA on three case studies involving linear regression, reinforcement learning, and transformer-based generative models.

Our analysis explored how STPA's control and system-theoretic perspectives apply to AI systems and whether unique AI traits - such as model opacity, capability uncertainty, and output complexity - necessitate modifications to the framework. We find that the key concepts and steps of conducting an STPA apply to AI systems but require targeted adaptations to address AI-specific challenges that arise to differing degrees across three case studies.

We present the Process-oriented Hazard Analysis for AI Systems (PHASE) as a guideline that adapts STPA concepts for AI. Applying and interpreting STPA using the PHASE guidelines enables four key affordances for analysts responsible for managing AI system harms: detection of system-level hazards, acknowledgment of social factors, traceable accountability chains, and ongoing monitoring and mitigation of new hazards.

---

## Contributions

This work contributes:

1. **PHASE guidelines** that adapt STPA to AI systems.
2. **Three case studies** illustrating hazard analysis across different AI paradigms.
3. **Four affordances** of applying a system-theoretic perspective to AI harms:
   - system-level hazard detection
   - accounting for social factors
   - traceable accountability chains
   - monitoring emergent hazards over time
