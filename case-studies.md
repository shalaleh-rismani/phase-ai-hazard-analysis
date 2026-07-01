---
layout: page
permalink: /case-studies.html
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# Case Studies

PHASE was applied to three AI system case studies. The cases were selected to span different machine learning paradigms, domains, and interaction modes.

---

## Case 1: Early Warning System

### AI paradigm

Linear regression

### Domain

Medicine

### System description

This case involves an early warning system designed to predict the likelihood of late-onset sepsis in preterm infants before clinical suspicion.

The system is intended to alert clinicians so they can begin early diagnostic testing and provide timely treatment.

### Interaction mode

Human-in-the-loop

A clinician makes the final clinical decision.

### Example losses

- Loss of life or injury to preterm infants
- Loss of time or efficiency
- Loss of physician reputation or credibility
- Loss of patient privacy

### Example hazards

- The system creates a model or output that does not meet performance requirements.
- The clinician misdiagnoses the patient.
- The system provides an alert that is not interpretable or actionable.
- Patient data is handled in ways that threaten privacy.

### PHASE insight

A component-level analysis may evaluate model accuracy or dataset quality, but PHASE reveals hazards that arise from interactions between the model, clinician, clinical workflow, patient data, and institutional constraints.

---

## Case 2: Insulin Injection

### AI paradigm

Reinforcement learning

### Domain

Medicine

### System description

This case involves a reinforcement learning-based system for automated and personalized insulin delivery.

The RL algorithm is designed for use in an artificial pancreas to tailor insulin doses for diabetic patients.

### Interaction mode

Human-out-of-the-loop

The system can autonomously determine insulin delivery during operation.

### Example losses

- Loss of life or injury to the diabetic patient
- Loss of quality of life
- Loss of efficiency
- Loss of money

### Example hazards

- The system delivers too much or too little insulin.
- The reinforcement learning agent learns an unsafe policy.
- The insulin pump fails to release the required amount.
- The system changes over time in ways that outpace safeguards.

### PHASE insight

This case highlights the importance of modeling autonomous AI components as controllers. The reinforcement learning agent is not only a model but part of a control loop that acts on the patient through the insulin pump.

---

## Case 3: Storyboarding

### AI paradigm

Transformer-based and generative models

### Domain

Creative practice

### System description

This case involves text-to-image systems used by machine learning artists as part of creative workflows, such as storyboarding for video creation.

The analysis focuses on text-to-image demo platforms and the broader process through which prompts, generated images, safety filters, users, and dissemination practices interact.

### Interaction mode

Human-as-tool-user

Artists interact with the system by entering prompts, selecting outputs, and deciding how to use or publish generated images.

### Example losses

- Loss of creativity
- Loss of diversity
- Loss of accessibility
- Loss of efficiency
- Loss of quality
- Loss of reputation

### Example hazards

- The system produces harmful or false content.
- A safety filter blocks legitimate creative use.
- A safety filter allows harmful content through.
- The training data or model design reduces diversity in outputs.
- The system changes through updates or retraining, introducing new hazards.

### PHASE insight

This case shows why PHASE draws system boundaries around both upstream development processes and downstream use contexts. For open-ended generative systems, hazards may emerge not only from model behavior but also from prompts, filters, user interpretation, publication decisions, and platform governance.

---

## Cross-case Lessons

Across the three case studies, PHASE showed that:

1. AI hazards can emerge from interactions across the system, not just from individual components.
2. Different AI paradigms place different demands on hazard analysis.
3. AI systems may shift between controller and controlled-process roles depending on context.
4. Social, organizational, and institutional factors are central to understanding AI harms.
5. Monitoring is necessary because hazards may emerge over time as systems evolve.
