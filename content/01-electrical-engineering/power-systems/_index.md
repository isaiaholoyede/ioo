---
title: Power Systems Engineering
date: 2026-07-02
tags:
  - ee/power-systems
  - type/roadmap
description: Generation, transmission, and delivery of bulk electric power — load flow, fault analysis, protection, stability, and grid operations.
draft: false
---

# Power Systems Engineering

Power systems engineering deals with the generation, transmission, and delivery of electrical energy at scale. These notes build from fundamentals through to modern grid analysis and operation.

---

## Core Topics

### Per-Unit System
Normalization of voltages, currents, impedances, and power across transformer boundaries. Essential for any multi-voltage system analysis.

$$Z_{pu} = \frac{Z_{actual}}{Z_{base}} \qquad S_{base} = V_{base} \cdot I_{base}$$

### Load Flow Analysis
Solving the steady-state operating point of a power network. Newton-Raphson and Gauss-Seidel methods.

$$P_i = \sum_{k=1}^{n} |V_i||V_k||Y_{ik}|\cos(\theta_{ik} + \delta_k - \delta_i)$$

### Fault Analysis
Symmetrical and unsymmetrical faults. Sequence networks, zero/positive/negative sequence components. Basis for protection system design.

### Power System Protection
Relaying principles, overcurrent, distance, differential protection. Coordination of fuses, reclosers, and relays.

### Stability Analysis
Transient stability, voltage stability, frequency response. Equal area criterion, swing equation.

$$M\frac{d^2\delta}{dt^2} = P_m - P_e$$

### Economic Dispatch & OPF
Optimal power flow, economic dispatch, unit commitment, locational marginal pricing.

### Power System Modeling
Bus admittance matrix (Y-bus), network equivalents, transformer models, transmission line models.

---

## Key Questions These Notes Answer

- How do I calculate power flows across a transmission network?
- What happens when a fault occurs and how do protection systems respond?
- How does the grid maintain frequency and voltage stability?
- How are generators dispatched economically across a grid?

---

## Prerequisites
- [[00-foundations/engineering/_index|Engineering Foundations]] — circuit theory, electromagnetics
- [[00-foundations/mathematics/_index|Mathematical Foundations]] — complex analysis, linear algebra

## Connects To
- [[distribution/_index|Distribution Power Systems]] — downstream of transmission
- [[../power-electronics/_index|Power Electronics]] — converter interfaces at the grid
- [[../control-systems/_index|Control Systems]] — AGC, voltage regulation
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]]
- [[04-credentials/pe-exam/_index|PE Exam — Power]]
