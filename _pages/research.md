---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Research Interests

### Scalable Robot Manipulation

- Data efficiency and generalization in manipulation
- Learning across heterogeneous data distributions
- Sim-Real-Generated data integration

### Representation-Centric Learning

- Action-defining representations instead of policy learning
- Progress-based, articulation-aware representations
- Scale-invariant and structure-preserving embeddings

### Articulated Object Manipulation

- Drawer, door, cabinet, articulated tools
- Metric goals (e.g., "open 5cm", "30% progress")
- Joint state, articulation constraints, motion limits

### Simulation as a Data Engine

- Simulation for supervision, not realism
- Joint values, articulation progress, motion constraints
- Sim-and-Real Co-Training paradigms

### Video & Synthetic Data

- Video generation for observation diversity
- In-the-wild visual distribution expansion
- Limits of generated video for action supervision

### 3D Object Flow & Part-level Motion

- Part-level motion over absolute pose
- Allowed motion subspace modeling
- Flow-based articulation reasoning

---

## Research Themes

### Theme 1: Sim-Real-Generated Data as a Unified Distribution

Simulation data improves real-world performance even when visually mismatched. The key factor is structured, action-relevant supervision. The focus is on distribution expansion, not gap minimization.

### Theme 2: Quantitative Articulation Representation

Current models cannot execute metric language goals. I propose articulation progress as a learnable target. Simulation enables otherwise impossible annotations.

### Theme 3: Video as Observation Augmentation

Generated video cannot provide reliable action labels. It is used to expand visual and environmental diversity. Action is inferred via structured constraints, not direct regression.

### Theme 4: Flow-based Motion Understanding

Articulated objects are defined by motion constraints. Flow provides relative, constraint-aware motion cues. It is used as auxiliary signal, not primary supervision.

---

## Research Statement

My research focuses on scalable robot manipulation by shifting the learning target from end-to-end policies to structured representations that define action. I study how simulation, real-world data, and generated observations can be integrated into a unified learning distribution through articulation-aware, metric, and scale-invariant representations. By treating simulation as a source of structured supervision rather than visual realism, and video generation as a tool for observation diversity rather than action labeling, my work aims to enable robust manipulation of articulated objects under diverse and previously unseen conditions.

---

## Selected Topics

- Sim-and-Real Co-Training
- Diffusion Policies (data-centric view)
- Articulated Progress Estimation
- Representation Design for Action
- Synthetic Data Pipelines

