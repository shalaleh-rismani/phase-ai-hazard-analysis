---
layout: home

---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# PHASE: Process-oriented Hazard Analysis for AI Systems

**From Silos to Systems: Process-Oriented Hazard Analysis for AI Systems**

**Authors:** Shalaleh Rismani, Roel Dobbe, and AJung Moon

**PHASE** is a guideline for applying **System Theoretic Process Analysis (STPA)** to Artificial Intelligence systems.

It supports system-level hazard analysis by helping analysts examine not only models and datasets, but also the broader development and operation processes in which AI systems are situated.

<div class="button-row">
  <a class="button" href="{{ '/assets/paper.pdf' | relative_url }}" target="_blank">Read the Paper</a>
  <a class="button" href="{{ '/assets/supplementary-material.pdf' | relative_url }}" target="_blank">Supplementary Material</a>
  <a class="button" href="{{ '/phase-process.html' | relative_url }}">View PHASE Process</a>
  <a class="button" href="{{ '/case-studies.html' | relative_url }}">Explore Case Studies</a>
  <a class="button" href="{{ '/templates.html' | relative_url }}">Use Templates</a>

</div>
---

## Project Overview

Current AI risk and harm analysis approaches often focus on individual components of an AI system, such as training data or models, in isolation. PHASE takes a system-level view by examining how hazards can emerge from interactions between components, development processes, organizational decisions, users, and deployment contexts.

This project includes:

- the paper, **From Silos to Systems: Process-Oriented Hazard Analysis for AI Systems**
- the **PHASE process** for adapting STPA to AI systems
- three case studies involving:
  - linear regression
  - reinforcement learning
  - transformer-based generative models
- templates for conducting PHASE analyses

---

## The Three Case Studies

<div class="card-grid">

<div class="card">
<h3>Case 1: Early Warning System</h3>
<p>A linear regression-based system for predicting late-onset sepsis in preterm infants.</p>
<a href="{{ '/case-studies.html#case-1-early-warning-system' | relative_url }}">Read more</a>
</div>

<div class="card">
<h3>Case 2: Insulin Injection</h3>
<p>A reinforcement learning-based system for personalized insulin delivery.</p>
<a href="{{ '/case-studies.html#case-2-insulin-injection' | relative_url }}">Read more</a>
</div>

<div class="card">
<h3>Case 3: Storyboarding</h3>
<p>A transformer-based text-to-image generative model case involving creative practice.</p>
<a href="{{ '/case-studies.html#case-3-storyboarding' | relative_url }}">Read more</a>
</div>

</div>

---

## PHASE in Four Steps

1. **Identify the purpose of the analysis**
2. **Create control diagrams**
3. **Identify unsafe control actions**
4. **Identify loss scenarios**

PHASE adapts these STPA steps to address AI-specific challenges such as model opacity, autonomy, capability uncertainty, and output complexity.

---

## Citation

Please cite the paper if you use PHASE in your work.

See the [Citation page]({{ '/citation.html' | relative_url }}) for BibTeX.
