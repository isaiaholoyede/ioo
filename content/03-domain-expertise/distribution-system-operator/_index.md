---
title: Distribution System Operator
date: 2026-07-02
tags:
  - domain/dso
  - type/roadmap
description: The role, responsibilities, tools, and decisions involved in operating a modern electric distribution system.
---

# Distribution System Operator (DSO)

The Distribution System Operator role sits at the center of the modern grid transition. A DSO must simultaneously operate a safe and reliable distribution system, integrate unprecedented levels of distributed energy resources, respond to outages, coordinate with transmission operators, and increasingly manage two-way power flows that traditional distribution systems were never designed to handle.

These notes document the operational knowledge, tools, decisions, and emerging frameworks of this role.

---

## Core Topics

### DSO Role & Responsibilities
Traditional utility operations vs. the emerging DSO model. Functions: real-time operations, outage management, DER coordination, planning, customer interface.

### Outage Management
Outage Management System (OMS), storm operations, crew dispatch, switching procedures, restoration strategies. FLISR automation.

### Real-Time Grid Operations
SCADA for distribution, switching orders, abnormal operating conditions, voltage management, load balancing.

### ADMS — Advanced Distribution Management System
Core capabilities: DSSE (state estimation), VVC (volt-var control), FLISR, DER management, network topology processing. Integration with OMS, GIS, AMI.

### DER Coordination & DERMS
Distributed Energy Resource Management Systems. Visibility into customer-side resources. Forecasting, dispatch, curtailment. Virtual power plants.

### Distribution Planning & Grid Modernization
Load growth forecasting, hosting capacity analysis, grid hardening, automation investment planning, non-wires alternatives (NWA).

### Regulatory & Market Context
FERC Order 2222, state utility regulation, distribution tariffs, DER compensation frameworks, the evolving role of the DSO in wholesale markets.

### Operational Metrics
SAIDI, SAIFI, CAIDI, MAIFI. How reliability metrics drive investment and operations. Benchmarking and regulatory reporting.

---

## Key Questions These Notes Answer

- What does a distribution operator actually do during a major outage event?
- How does an ADMS differ from a traditional SCADA system?
- How does a DSO coordinate with a transmission system operator during a contingency?
- What is the DSO model and how does it differ from the traditional vertically integrated utility?
- How does DERMS provide visibility and control over distributed resources?
- How do hosting capacity maps inform where DER can be interconnected?

---

## Prerequisites
- [[01-electrical-engineering/power-systems/distribution/_index|Distribution Power Systems]]
- [[01-electrical-engineering/communications-networking/_index|Communications & Networking]]
- [[02-software-systems/information-systems/_index|Information Systems]]

## Connects To
- [[01-electrical-engineering/renewable-energy-der/_index|Renewable Energy & DER]]
- [[02-software-systems/cybersecurity/_index|Cybersecurity]] — OT security for DSO
- [[03-domain-expertise/technical-product-management/_index|Technical Product Management]] — ADMS/DERMS product context
- [[04-credentials/pe-exam/_index|PE Exam — Power]]
