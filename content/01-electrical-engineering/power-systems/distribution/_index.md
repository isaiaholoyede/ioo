---
title: Distribution Power Systems Engineering
date: 2026-07-02
tags:
  - ee/distribution
  - type/roadmap
description: The last mile of the grid — systems that deliver power to customers and integrate distributed resources.
draft: true
---

# Distribution Power Systems Engineering

Distribution systems are where the grid meets the customer. These notes cover the design, analysis, operation, and modernization of the distribution network — from substations to meters, and increasingly from meters back to the grid via distributed energy resources.

---

## Core Topics

### Distribution System Architecture
Radial, loop, and meshed topologies. Primary and secondary distribution. Substation design. Feeder configuration.

### Distribution Load Flow
Backward-forward sweep methods. Unbalanced three-phase analysis. Modeling of loads, capacitors, regulators, and DER.

### Voltage Regulation
Voltage profiles along feeders. Capacitor banks, voltage regulators, LTC transformers. Conservation voltage reduction (CVR).

### Distribution Protection
Overcurrent coordination, fuses, reclosers, sectionalizers. Fault location, isolation, and service restoration (FLISR).

### Distribution Automation (DA)
SCADA for distribution, automated switching, self-healing grid capabilities, ADMS.

### DER Integration
Impact of solar PV, storage, EVs, and microgrids on distribution systems. Hosting capacity analysis, interconnection standards (IEEE 1547).

### Distribution Planning
Load forecasting, capacity planning, reliability metrics (SAIDI, SAIFI, CAIDI), infrastructure investment decisions.

### Advanced Metering Infrastructure (AMI)
Smart meters, two-way communication, demand response, data analytics applications.

---

## Key Questions These Notes Answer

- How does a distribution feeder maintain acceptable voltage along its length?
- How does protection coordination work in a radial distribution system?
- What happens to protection and voltage when DERs are added to a feeder?
- How do distribution operators use SCADA and ADMS to manage their systems?
- How is hosting capacity calculated for a feeder?

---

## Prerequisites
- [[../_index|Power Systems Engineering]]
- [[00-foundations/engineering/_index|Engineering Foundations]]

## Connects To
- [[../../renewable-energy-der/_index|Renewable Energy & DER]]
- [[../../power-electronics/_index|Power Electronics]] — inverter-based DER
- [[../../control-systems/_index|Control Systems]] — FLISR, VVC
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]]
- [[04-credentials/pe-exam/_index|PE Exam — Power]]
