---
title: Power Electronics Foundation
date: 2026-07-02
tags:
  - ee/power-electronics
  - type/roadmap
description: Converters, inverters, rectifiers, and drives — the interface between electrical machines, the grid, and distributed energy resources.
draft: true
---

# Power Electronics Foundation

Power electronics is the discipline of converting and controlling electrical power using semiconductor switching devices. It is the enabling technology for renewable energy, electric vehicles, motor drives, and modern grid infrastructure.

---

## Core Topics

### Semiconductor Switching Devices
Diodes, MOSFETs, IGBTs, thyristors — their characteristics, switching behavior, and thermal management.

### DC-DC Converters
Buck, boost, buck-boost, Cuk, SEPIC. Duty cycle, voltage conversion ratio, continuous vs. discontinuous conduction mode.

$$V_{out} = D \cdot V_{in} \quad \text{(buck)} \qquad V_{out} = \frac{V_{in}}{1-D} \quad \text{(boost)}$$

### AC-DC Rectifiers
Half-wave, full-wave, controlled rectifiers, power factor correction (PFC). THD and harmonic content.

### DC-AC Inverters
Single-phase and three-phase inverters. PWM techniques: SPWM, SVPWM. Grid-tied vs. standalone inverters.

### AC-AC Converters
Cycloconverters, matrix converters, AC voltage controllers.

### Motor Drives
Variable frequency drives (VFDs), V/f control, vector control (FOC), direct torque control (DTC).

### Power Electronics for Grid Applications
FACTS devices: STATCOM, SVC, UPFC. HVDC transmission. Grid-forming inverters.

### Magnetics in Power Electronics
Inductors, transformers, core materials, saturation, losses. Design of magnetic components.

---

## Key Questions These Notes Answer

- How does a switching converter achieve voltage conversion without resistive losses?
- How does an inverter synthesize a sinusoidal AC waveform from a DC source?
- How does a variable frequency drive control motor speed?
- What is the difference between a grid-following and grid-forming inverter?
- How do FACTS devices provide reactive power support?

---

## Prerequisites
- [[00-foundations/engineering/_index|Engineering Foundations]] — circuit theory
- [[00-foundations/mathematics/_index|Mathematical Foundations]] — Laplace transforms, Fourier analysis

## Connects To
- [[../renewable-energy-der/_index|Renewable Energy & DER]] — inverter-based resources
- [[../control-systems/_index|Control Systems]] — converter control loops
- [[../power-systems/_index|Power Systems]] — FACTS, HVDC
