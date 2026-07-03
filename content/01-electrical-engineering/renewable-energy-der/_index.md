---
title: Renewable Energy & Distributed Energy Resources
date: 2026-07-02
tags:
  - ee/renewable-der
  - type/roadmap
description: Solar, wind, storage, microgrids, and the integration of distributed generation into the grid.
---

# Renewable Energy & Distributed Energy Resources

The energy transition is reshaping the grid from the generation level down to the meter. These notes cover the technologies, grid impacts, interconnection standards, and market frameworks governing renewable energy and distributed energy resources.

---

## Core Topics

### Solar Photovoltaics
PV cell physics, I-V curves, maximum power point tracking (MPPT), system sizing, shading analysis, utility-scale vs. distributed PV.

$$P_{max} = V_{mp} \cdot I_{mp}$$

### Wind Energy
Wind turbine aerodynamics, power curves, capacity factor, fixed vs. variable speed turbines, offshore considerations.

$$P = \frac{1}{2}\rho A v^3 C_p$$

### Battery Energy Storage Systems (BESS)
Electrochemistry basics, battery chemistries (Li-ion, LFP), state of charge, depth of discharge, round-trip efficiency, degradation, applications.

### Inverter-Based Resources (IBR)
Grid-following vs. grid-forming inverters. Frequency and voltage response. Fault behavior differences from synchronous generation.

### Microgrids
Architecture, islanding detection, control modes, transition between grid-connected and islanded operation, resiliency applications.

### Interconnection Standards
IEEE 1547-2018, UL 1741, Rule 21, FERC Order 2222. Interconnection process and technical requirements.

### Grid Services from DER
Frequency regulation, voltage support, demand response, virtual power plants (VPP), aggregation.

### Resource Adequacy & Planning
Effective load carrying capability (ELCC), capacity value of storage and renewables, planning reserve margins.

---

## Key Questions These Notes Answer

- How does a solar inverter stay synchronized with the grid?
- What is the grid impact of high penetrations of inverter-based resources?
- How does a battery storage system provide frequency regulation?
- What are the interconnection requirements for a distributed solar installation?
- How do microgrids detect islanding and transition to autonomous operation?

---

## Prerequisites
- [[../power-systems/_index|Power Systems Engineering]]
- [[../power-electronics/_index|Power Electronics]]

## Connects To
- [[../power-systems/distribution/_index|Distribution Power Systems]] — DER integration on feeders
- [[../control-systems/_index|Control Systems]] — inverter control, microgrid control
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]]
- [[04-credentials/phd-energy-engineering/_index|PhD — Energy Engineering]]
