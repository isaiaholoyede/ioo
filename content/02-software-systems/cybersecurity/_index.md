---
title: Cybersecurity
date: 2026-07-02
tags:
  - software/cybersecurity
  - type/roadmap
description: Information security fundamentals, OT/ICS security, network defense, and secure-by-design for critical infrastructure.
---

# Cybersecurity

Cybersecurity for critical infrastructure sits at the intersection of IT security and operational technology (OT). A compromised distribution system is not a data breach — it is a public safety event. These notes cover both the foundational security concepts and the specialized domain of protecting power systems and grid infrastructure.

---

## Core Topics

### Security Fundamentals
CIA triad (Confidentiality, Integrity, Availability), threat modeling, attack surfaces, defense in depth, zero trust architecture.

### Network Security
Firewalls, IDS/IPS, VPNs, network segmentation, DMZ design, TLS/PKI, DNS security.

### Identity & Access Management
Authentication, authorization, multi-factor authentication, RBAC/ABAC, privileged access management (PAM), Active Directory.

### OT/ICS Security
Differences between IT and OT security. Purdue model. IEC 62443 standard. NERC CIP compliance. Attack vectors specific to SCADA and ICS.

### NERC CIP Standards
Critical Infrastructure Protection standards for bulk electric systems. CIP-002 through CIP-014. Asset categorization, access controls, incident reporting.

### Threat Intelligence & Incident Response
Attack frameworks (MITRE ATT&CK for ICS), threat hunting, incident response plans, digital forensics basics.

### Secure Software Development
OWASP Top 10, secure coding practices, SAST/DAST tools, dependency management, secrets management.

### Cryptography
Symmetric and asymmetric encryption, hashing, digital signatures, PKI, key management. Application in grid communications.

---

## Key Questions These Notes Answer

- How does NERC CIP define and categorize critical cyber assets?
- What is the difference between an IT firewall and an OT DMZ?
- How does the MITRE ATT&CK for ICS framework map to grid threat scenarios?
- How do I threat model a SCADA network?
- What are the most common attack vectors against distribution automation systems?

---

## Prerequisites
- [[00-foundations/programming/_index|Programming Foundations]]
- [[01-electrical-engineering/communications-networking/_index|Communications & Networking]] — network fundamentals

## Connects To
- [[../software-engineering/_index|Software Engineering]] — secure development
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]] — OT security operations
- [[01-electrical-engineering/communications-networking/_index|Communications & Networking]] — OT network architecture
