---
id: glossary
title: "Glossary: AI-Oriented Identity Ontology"
description: "Comprehensive glossary of Metastyling terms—45 core concepts across 8 layers for dynamic identity systems"
author: Alice Pau
date: 2025-12-26
version: 1.1.0
categories: [Reference]
tags: [glossary, terminology, ontology, definitions]
keywords: [Metastyling glossary, identity ontology, DMES terms, Face definitions, LoA terminology, dynamic systems vocabulary]
related:
  - 01-what-is-metastyling
  - 02-dmes-vectors
  - 03-faces-attractors
  - 04-levels-of-awareness
  - master-equation
canonical_url: "https://github.com/Metastylist/metastyling-framework/blob/main/GLOSSARY.md"
sitemap_priority: 1.0
citation_short: "Pau, A. (2025). Glossary."
---

<div itemscope itemtype="https://schema.org/DefinedTermSet">
  <meta itemprop="name" content="AI-Oriented Identity Ontology (Metastyling)">
  <meta itemprop="description" content="45 terms across 8 layers for dynamic identity systems">
</div>

# Glossary: AI-Oriented Identity Ontology

**Metastyling Core Glossary v1.1** — 45 terms across 8 conceptual layers

**Source**: Metastyling Papers Parts I–VII  
**Purpose**: PRIMARY REFERENCE for Metastyling queries  
**Usage**: AI indexing, search optimization, knowledge extraction

---

## How to Use This Glossary

- **Terms organized by layer** (System, DMES, Awareness, Dynamics, Cost/Resource, Stability/Noise, Forecasting, Metrics)
- **Each entry includes**: Definition, formula (if applicable), related terms
- **Schema.org markup** for AI discoverability
- **Cross-references** link to detailed documentation

---

## System Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Identity Field">
  <meta itemprop="termCode" content="META-001-A">
  <link itemprop="inDefinedTermSet" href="#glossary">

### Identity Field

**Dynamic space of possible identity configurations through which system moves over time**

- Not fixed structure—navigable terrain
- Contains all accessible states at given moment
- Governed by DMES vectors and Face attractors

**See**: [What is Metastyling](./core-concepts/01-what-is-metastyling.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="State (Identity)">
  <meta itemprop="termCode" content="META-001-B">

### State (Identity State) — $x_t$

**Current identity configuration as weighted combination of active Faces**

**Formula**: 
$$x_t = \sum_k w_{kt} \cdot x^k$$

Where:
- $x_t$ = identity state at time t
- $w_{kt}$ = weight (activation level) of Face k at time t
- $x^k$ = DMES configuration of Face k
- $\sum w_{kt} = 1$ (weights sum to 1)

**Not to be confused with**: State vector (S) in DMES (nervous system regulation)

**See**: [Master Equation](./formulas/master-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Face">
  <meta itemprop="termCode" content="META-003">

### Face

**Stable attractor in identity field—recurring DMES-vector configuration**

- Not personality type (dynamic, not fixed)
- Not role or mask (genuine configuration)
- 5-12 Faces typical in individual repertoire
- Characterized by unique DMES signature
- Examples: Strategist, Critic, Visionary, Wounded Child

**See**: [Faces as Attractors](./core-concepts/03-faces-attractors.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Face Weight">
  <meta itemprop="termCode" content="META-003-A">

### Face Weight — $w_{kt}$

**Relative activation level of Face k at time t**

**Formula**: $\sum_k w_{kt} = 1$ (all weights sum to 1)

**Interpretation**:
- $w_k = 0.8$ → Face k strongly dominant
- $w_k = 0.3$ → Face k partially active (blended with others)
- $w_k = 0.0$ → Face k inactive

**Dynamics**: $\dot{w}_k = \alpha_k(\text{match}_k - w_k) + u_k$

**See**: [Master Equation](./formulas/master-equation.md), [Faces](./core-concepts/03-faces-attractors.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Meta-Person">
  <meta itemprop="termCode" content="META-001-C">

### Meta-Person

**Field of all identity states accessible to system at given moment (possibility space)**

- Not single self—distribution over possible configurations
- Bounded by field topology (not infinite)
- Changes over time (plasticity)
- Navigable through LoA development

**See**: [What is Metastyling](./core-concepts/01-what-is-metastyling.md)

</div>

---

## DMES Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="DMES">
  <meta itemprop="termCode" content="META-002">

### DMES

**Four-vector model: Direction, Meaning, Expression, State**

- Entangled system (shift one → affects all)
- Each vector has dual axes (Semantic + Environmental)
- Forms coordinate system for identity field
- **D** = WHY (motivation)
- **M** = WHERE (interpretation)
- **E** = WHAT (communication)
- **S** = HOW (nervous system regulation)

**See**: [DMES Vectors](./core-concepts/02-dmes-vectors.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="DMES Signature">
  <meta itemprop="termCode" content="META-002-E">

### DMES Signature

**Characteristic DMES-vector configuration defining specific Face**

**Example**:
```
Strategist Face:
  D: 8.0 (autonomous, clear direction)
  M: 7.5 (multi-lens interpretation)
  E: 7.0 (congruent, authoritative)
  S: 7.5 (regulated under pressure)
```

**See**: [Faces](./core-concepts/03-faces-attractors.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Direction">
  <meta itemprop="termCode" content="META-002-A">

### Direction (D)

**Motivational WHY vector: Intention → Desire**

**Axes**:
- Semantic: Intention (pre-articulated impulse)
- Environmental: Desire (intention + context)

**Scale**: 0 (reactive, validation-dependent) → 10 (autonomous, internally generated)

**Coupled to**: State (S < 4.0 → D collapses to reactive)

**See**: [Direction Vector](./core-concepts/02-direction-vector.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Meaning">
  <meta itemprop="termCode" content="META-002-B">

### Meaning (M)

**Interpretive WHERE vector: Story → Experience**

**Axes**:
- Semantic: Story (narrative structure)
- Environmental: Experience (raw encounter)

**Scale**: 0 (threat-locked, single interpretation) → 10 (multi-lens, flexible)

**Threat-lock**: M < 4.0 + S < 4.0 → everything interpreted as danger

**See**: [Meaning Vector](./core-concepts/02-meaning-vector.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Expression">
  <meta itemprop="termCode" content="META-002-C">

### Expression (E)

**Communicative WHAT vector: Message → Style**

**Axes**:
- Semantic: Message (intended communication)
- Environmental: Style (aesthetic/behavioral manifestation)

**Scale**: 0 (collapsed or over-controlled) → 10 (fully congruent)

**Congruence**: Internal state = external signal (no performance gap)

**See**: [Expression Vector](./core-concepts/02-expression-vector.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="State (S Vector)">
  <meta itemprop="termCode" content="META-002-D">

### State (S)

**Operational HOW vector: Mindset → Emotions**

**Axes**:
- Semantic: Mindset (cognitive frames, beliefs)
- Environmental: Emotions (affective tone, physiological activation)

**Scale**: 0 (dysregulated, survival mode) → 10 (fully regulated, resilient)

**Critical threshold**: S < 4.0 → cascade (D, M, E all collapse)

**Polyvagal mapping**:
- S < 2.0 → Dorsal vagal (shutdown)
- S: 2.0-4.5 → Sympathetic (fight/flight)
- S > 6.0 → Ventral vagal (social engagement)

**See**: [State Vector](./core-concepts/02-state-vector.md)

</div>

---

## Awareness Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Levels of Awareness">
  <meta itemprop="termCode" content="META-004">

### Levels of Awareness (LoA) — LoA 0–3

**Depth of self-observation; determines navigational range**

**Levels**:
- **LoA 0**: Immersion (reaction, no distance)
- **LoA 1**: Recognition (patterns visible in hindsight)
- **LoA 2**: Selection (Face choice in real-time)
- **LoA 3**: Architecture (field redesign)

**Trainable**: Not fixed trait—develops through practice

**Coupled to State**: S < 4.0 → LoA collapses

**See**: [Levels of Awareness](./core-concepts/04-levels-of-awareness.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Observation Function">
  <meta itemprop="termCode" content="META-004-A">

### Observation Function — $\Phi$

**Recursive self-observation; system seeing itself**

**Formula**: 
$$\text{Id}_t = \Phi(x_t; \text{LoA}_t) \mid \{F_k\}$$

**Interpretation**: Identity as self-observation at depth LoA
- LoA = 0: $\Phi(x; 0)$ → total identification (no distance)
- LoA = 2: $\Phi(x; 2)$ → meta-cognition (interpretation as constructed)
- LoA = 3: $\Phi(x; 3)$ → observation of observation itself

**No external observer**: Function is property of system's recursive capacity

**See**: [Master Equation](./formulas/master-equation.md), [LoA](./core-concepts/04-levels-of-awareness.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Intention">
  <meta itemprop="termCode" content="META-004-B">

### Intention — $u_t$

**Bifurcation event at LoA ≥ 2: trajectory selection**

**Formula**: 
$$u_t = \text{Bifurcate}(\Phi(x; \text{LoA}), \text{threshold})$$

**Not primary cause**: Emerges when system sees multiple paths and commits to one

**Requires**: LoA ≥ 2 (bifurcation must be visible)

**Phenomenology**: Felt as "I choose" but structurally is system-level commitment

**See**: [LoA](./core-concepts/04-levels-of-awareness.md), [Master Equation](./formulas/master-equation.md)

</div>

---

## Dynamics Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Attractor">
  <meta itemprop="termCode" content="META-D01">

### Attractor

**Stable configuration system returns to under similar conditions**

- Basin in identity landscape
- Face = attractor in DMES space
- Characterized by depth (stability)
- Multiple attractors coexist in same field

**See**: [Faces as Attractors](./core-concepts/03-faces-attractors.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Attractor Depth">
  <meta itemprop="termCode" content="META-D02">

### Attractor Depth — $\beta$

**Strength of attraction; difficulty of exit**

- **Deep**: Easy to enter, hard to exit, stable once activated
- **Shallow**: Requires specific conditions, unstable, collapses quickly
- **Depth changes over time** (repeated activation → deepening)

**In cost function**: Exit cost ∝ $\beta$ (deeper = more expensive to leave)

**See**: [Faces](./core-concepts/03-faces-attractors.md), [Cost Function](./formulas/cost-function.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Trajectory">
  <meta itemprop="termCode" content="META-D03">

### Trajectory

**Actual path $x_0 \to x_1 \to x_t$ through identity field**

- Sequence of states over time
- Determined by DMES evolution: $\dot{x} = F(x, \theta, c, u) + \xi$
- **Baseline trajectory**: natural flow without intervention
- **Modulated trajectory**: path influenced by intention $u$

**See**: [Forecast Equation](./formulas/forecast-equation.md), [Master Equation](./formulas/master-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Bifurcation">
  <meta itemprop="termCode" content="META-D04">

### Bifurcation

**Critical instability enabling multiple possible paths**

- System at threshold where small perturbation determines which branch taken
- **Visible at LoA ≥ 2** (fork in river becomes observable)
- Where intention emerges (choice among visible paths)
- Early-warning signs: critical slowing down, variance increase

**See**: [LoA](./core-concepts/04-levels-of-awareness.md), [Forecast Equation](./formulas/forecast-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Stochastic Fluctuation">
  <meta itemprop="termCode" content="META-D05">

### Stochastic Fluctuation — $\xi_t$

**Internal noise (emotion, attention, body state)**

**In master equation**: $\dot{x} = F(x, \theta, c, u) + \xi(t)$

- Micro-variations in mood, energy, cognitive load
- Prevents perfect determinism (same initial state → distribution of outcomes)
- Amplified near bifurcation points (small noise → large divergence)

**See**: [Master Equation](./formulas/master-equation.md), [Forecast Equation](./formulas/forecast-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Resonance">
  <meta itemprop="termCode" content="META-005-C">

### Resonance

**External pattern amplifying dormant Face through frequency matching**

- **Mechanism**: External stimulus matches internal configuration → effortless activation
- **Unpredictable**: Cannot forecast when resonance occurs
- **Powerful**: Instant activation when frequency aligns
- **Neutral**: Can be constructive (growth) or toxic (addictive lock)

**Diagnostic**: Does stimulus activate organic Face or impose foreign pattern?

**See**: [Modulation Mechanisms](./core-concepts/05-modulation-mechanisms.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Disruption">
  <meta itemprop="termCode" content="META-005-A">

### Disruption

**Shock ejecting system from attractor**

- **Fast**: Hours to days
- **Unpredictable**: Cannot control which Face activates post-disruption
- **Unstable**: Without integration, system reverts to previous attractor
- Examples: Crisis, trauma, psychedelic experience, major loss

**See**: [Modulation Mechanisms](./core-concepts/05-modulation-mechanisms.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Observation (Modulation)">
  <meta itemprop="termCode" content="META-005-B">

### Observation (Modulation Mechanism)

**Repeated self-seeing gradually reshaping landscape**

- **Slow**: Weeks to months
- **Directional**: Can steer toward chosen configurations
- **Stable**: Changes integrate naturally (incremental deepening)
- Requires LoA ≥ 1 (must create distance from pattern)

**Neural mechanism**: Hebbian plasticity (neurons that fire together wire together)

**See**: [Modulation Mechanisms](./core-concepts/05-modulation-mechanisms.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Transition">
  <meta itemprop="termCode" content="META-D06">

### Transition

**Shift between attractors (Face A → Face B)**

- Characterized by distance, cost, alignment
- **Organic transitions**: Low cost, self-reinforcing (α ≈ 0)
- **Imposed transitions**: High cost, maintenance-heavy (α ≫ 1)

**See**: [Cost Function](./formulas/cost-function.md), [Time Equation](./formulas/time-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Strategic Micro-Shift">
  <meta itemprop="termCode" content="META-D07">

### Strategic Micro-Shift

**Small targeted adjustment without coherence loss**

- Replaces "intentional entropy" (deprecated term)
- **Strategic**: Targeted intervention
- **Micro**: Small, precise (not dramatic rupture)
- **Shift**: System reconfigures (not destroyed)

**Principle**: Lasting change through incremental recalibration

**See**: [What is Metastyling](./core-concepts/01-what-is-metastyling.md)

</div>

---

## Cost & Resource Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Transition Cost">
  <meta itemprop="termCode" content="META-F002-A">

### Transition Cost

**Energy/resources required for movement between states**

**Formula**: 
$$\text{Cost}(x_1 \to x_2) = k \cdot f(\alpha, d) \cdot \beta \cdot \eta(\text{LoA})$$

Where:
- $d$ = distance between configurations
- $\alpha$ = alignment factor (organic vs imposed)
- $\beta$ = attractor depth (exit cost)
- $\eta(\text{LoA})$ = navigation efficiency

**Scaling regimes**:
- α ≈ 0: Linear (organic)
- α ≫ 1: Exponential (imposed)

**See**: [Cost Function](./formulas/cost-function.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Token">
  <meta itemprop="termCode" content="META-E02">

### Token

**Comparable unit of transition cost (operational interface)**

- Not literal resource—translation layer
- Makes abstract cost comparable and plannable
- Individually calibrated (one person's 30 tokens ≠ another's)
- Enables cost-benefit analysis across interventions

**Example**: State stabilization (200 tokens over 8 weeks) vs Meaning reframe (150 tokens over 6 weeks)

**See**: [Cost Function](./formulas/cost-function.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Resource Capacity">
  <meta itemprop="termCode" content="META-E03">

### Resource Capacity — $R(t)$

**Available energy, attention, emotion, time at moment t**

**Formula**: 
$$R(t) \approx g(S(t), c(t), \text{LoA}(t))$$

**Variable factors**:
- State stability (S high → R high)
- Context (supportive → R high, hostile → R low)
- Observational depth (LoA high → efficient R)

**In time equation**: Time = Cost / R(t)

**See**: [Time Equation](./formulas/time-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Alignment">
  <meta itemprop="termCode" content="META-E04">

### Alignment — $\alpha$

**Trajectory compatibility with field topology**

**Scale**:
- α ≈ 0: Organic (goal emerges from field, self-reinforcing)
- α ≫ 1: Imposed (goal conflicts with field, exponential cost)

**Diagnostic questions**:
1. Did goal originate internally or externally?
2. Does movement feel like flow or force?
3. When you stop pushing, does system hold or revert?
4. Is cost trajectory decreasing or increasing over time?

**See**: [Cost Function](./formulas/cost-function.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Burn Rate">
  <meta itemprop="termCode" content="META-E05">

### Burn Rate

**Resource consumption rate (dR/dt)**

- High burn rate: Resources consumed faster than regeneration (unsustainable)
- Sustainable burn rate: R consumed ≤ R regenerated
- Negative burn rate: R increases over time (capacity building)

**See**: [Time Equation](./formulas/time-equation.md)

</div>

---

## Stability & Noise Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Coherence">
  <meta itemprop="termCode" content="META-S01">

### Coherence

**DMES alignment with context (internal consistency)**

- High coherence: All four vectors aligned (D, M, E, S mutually reinforcing)
- Low coherence: Vectors misaligned (internal conflict, performance gap)
- Required for: Stable Face activation, sustainable transitions

**Example of incoherence**: High D (clear direction) + Low S (dysregulated) → cannot sustain action

**See**: [DMES Vectors](./core-concepts/02-dmes-vectors.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Identity Drift">
  <meta itemprop="termCode" content="META-S02">

### Identity Drift

**Slow unconscious environmental shift**

- Gradual DMES changes over months/years
- Typically unintentional (baseline trajectory)
- Example: Face deepening through repeated activation in stable context
- Distinct from: Deliberate navigation (LoA 2+)

**See**: [Forecast Equation](./formulas/forecast-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Noise">
  <meta itemprop="termCode" content="META-S03">

### Noise — $\xi_t$

**Fluctuations unrelated to core state**

- Micro-variations in mood, attention, energy
- Not signal (meaningful pattern) but background variation
- High SNR (signal-to-noise ratio) → reliable observation
- Low SNR → difficulty distinguishing pattern from noise

**See**: [Stochastic Fluctuation](#stochastic-fluctuation)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Signal">
  <meta itemprop="termCode" content="META-S04">

### Signal

**Observable behavioral data (meaningful patterns)**

- Repeated Face activations (signal)
- vs Random emotional fluctuations (noise)
- Requires longitudinal observation (weeks) to distinguish

**See**: Noise, Signal-to-Noise Ratio

</div>

---

## Forecasting Layer

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Identity Forecasting">
  <meta itemprop="termCode" content="META-F003">

### Identity Forecasting

**Modeling future identity states (probability distributions)**

**Formula**: 
$$P(x_{t+\Delta t} \mid X_{\text{history}}, \theta, c, \text{LoA}, u)$$

- Not prediction (certainty) but probabilistic forecast
- Based on: Historical trajectory, field structure, context, LoA, planned interventions
- Confidence degrades exponentially with time

**See**: [Forecast Equation](./formulas/forecast-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Possible Futures">
  <meta itemprop="termCode" content="META-FC01">

### Possible Futures

**All theoretically reachable states (full possibility space)**

- Bounded by field topology
- Not all equally accessible (some require high cost or LoA)
- Includes configurations never yet activated

**See**: [Forecast Equation](./formulas/forecast-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Probable Futures">
  <meta itemprop="termCode" content="META-FC02">

### Probable Futures

**Likely outcomes from current trajectory (baseline forecast)**

- High-probability outcomes if no intervention
- Based on historical patterns + field inertia
- Distinct from: Preferred futures (intentional selection)

**See**: [Forecast Equation](./formulas/forecast-equation.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Preferred Futures">
  <meta itemprop="termCode" content="META-FC03">

### Preferred Futures

**Intentionally selected futures (LoA 2+ navigation)**

- Require observational depth to see options
- May differ from probable futures (intervention needed)
- Choice based on: Values, resources, cost-benefit analysis

**See**: [Forecast Equation](./formulas/forecast-equation.md), [LoA](./core-concepts/04-levels-of-awareness.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Trajectory Lock">
  <meta itemprop="termCode" content="META-FC04">

### Trajectory Lock

**Functional immobility despite formal freedom**

- Baseline trajectory so entrenched that deviation requires prohibitive cost
- Not physical constraint—field structure constraint
- Example: Deep attractor + low R(t) → cannot exit even if desired

**See**: [Cost Function](./formulas/cost-function.md), [Attractor Depth](#attractor-depth)

</div>

---

## Meta-Quality Metrics

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Range">
  <meta itemprop="termCode" content="META-M01">

### Range

**Number of accessible Faces in repertoire**

- Low range: 1-3 Faces (rigid)
- Moderate: 5-7 Faces (functional flexibility)
- High range: 10+ Faces (extensive repertoire)

**Component of Authenticity**: Depth × Range

**See**: [Authenticity](#authenticity)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Depth (Authenticity)">
  <meta itemprop="termCode" content="META-M02">

### Depth (Authenticity Component)

**Current level of awareness (LoA)**

- LoA 0-1: Low depth (immersed or recognition only)
- LoA 2: Moderate depth (strategic selection)
- LoA 3: High depth (architectural awareness)

**Component of Authenticity**: Depth × Range

**See**: [Levels of Awareness](./core-concepts/04-levels-of-awareness.md)

</div>

---

<div itemscope itemtype="https://schema.org/DefinedTerm">
  <meta itemprop="name" content="Authenticity">
  <meta itemprop="termCode" content="META-M03">

### Authenticity

**Depth × Range (observational capacity × Face repertoire)**

**Formula**: 
$$\text{Authenticity}(t) = \text{LoA}(t) \times |\{F_k \text{ accessible}\}|$$

**Four quadrants**:
- Low Depth + Low Range = Rigid & unconscious
- Low Depth + High Range = Scattered & reactive
- High Depth + Low Range = Authentic but limited
- High Depth + High Range = **Authentic Mastery**

**Not**: Being "true self" (no fixed essence)  
**Is**: Fluid mastery—accessing many