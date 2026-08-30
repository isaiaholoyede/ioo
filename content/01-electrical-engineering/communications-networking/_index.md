---
title: Communications & Networking
date: 2026-07-02
tags:
  - ee/communications
  - type/roadmap
description: Communication protocols, SCADA, IEC 61850, DNP3, fiber and wireless for grid infrastructure.
draft: true
---

# Communications & Networking

Modern power systems are cyber-physical systems — the electrical grid depends on a communication infrastructure for monitoring, control, and protection. These notes cover both the foundational communication theory and the specific protocols and architectures used in grid operations.

---

## Core Topics

### Communication Theory Fundamentals
Shannon's theorem, modulation (AM, FM, QAM, OFDM), channel capacity, noise and error correction.

$$C = B\log_2\left(1 + \frac{S}{N}\right)$$

### Network Fundamentals
OSI model, TCP/IP stack, Ethernet, switching, routing, VLANs, network security basics.

### Grid Communication Protocols
- **DNP3** — SCADA communications between control centers and field devices
- **IEC 61850** — substation automation, GOOSE messaging, sampled values
- **Modbus** — legacy industrial protocol, still widely deployed
- **IEC 60870-5** — telecontrol protocols for power systems
- **IEEE C37.118** — synchrophasor data standard (PMUs)

### SCADA & Energy Management Systems
Architecture of SCADA systems, RTUs, IEDs, historians, HMI. Interfaces to EMS and ADMS.

### Communication Media for Grid Applications
Fiber optic, power line carrier (PLC), cellular (4G/5G), licensed radio, satellite. Trade-offs in latency, bandwidth, and reliability.

### Time Synchronization
GPS-based timing, IEEE 1588 (PTP), IRIG-B. Why precise time matters for protection and synchrophasors.

### OT Network Architecture
IT vs. OT network differences. Purdue model, IEC 62443 zones and conduits. Defense in depth.

---

## Key Questions These Notes Answer

- How does IEC 61850 differ from DNP3 and when is each used?
- How does a SCADA system communicate with a field device?
- What communication latency is required for protection vs. monitoring?
- How is GPS timing used in synchrophasor measurements?
- How do OT networks differ from enterprise IT networks?

---

## Prerequisites
- [[00-foundations/engineering/_index|Engineering Foundations]]
- [[00-foundations/programming/_index|Programming Foundations]] — helps with protocol implementation

## Connects To
- [[../power-systems/_index|Power Systems Engineering]] — EMS, SCADA
- [[../power-systems/distribution/_index|Distribution Power Systems]] — ADMS, DA
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]]
- [[02-software-systems/cybersecurity/_index|Cybersecurity]] — OT security
