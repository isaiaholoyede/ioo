---
title: Software & Information Systems
date: 2026-07-02
tags:
  - software/information-systems
  - type/roadmap
description: Data modeling, enterprise systems, systems integration, and information architecture.
draft:
---

# Software & Information Systems

Information systems is the discipline of managing, modeling, and delivering data and processes across an organization. In an engineering context, it bridges operational technology (OT) and information technology (IT) — connecting field devices, operational systems, and business intelligence.

---

## Core Topics

### Data Modeling
Entity-relationship (ER) modeling, relational schema design, normalization (1NF–3NF, BCNF), UML class diagrams.

### Enterprise Systems
ERP, asset management (EAM), work order management, GIS for utilities, customer information systems (CIS), billing.

### Systems Integration
APIs, ETL pipelines, middleware, enterprise service bus (ESB), event streaming (Kafka). Integrating OT and IT systems.

### Information Architecture
Master data management (MDM), data governance, metadata, taxonomy, ontologies.

### Common Information Model (CIM)
IEC CIM for power systems — the semantic standard for grid data exchange between EMS, ADMS, DER management, and market systems.

### Data Warehousing & BI
Data warehouses, data lakes, OLAP vs. OLTP, dimensional modeling (star schema), BI tools and dashboards.

### Geographic Information Systems (GIS)
Spatial data, coordinate systems, network topology, GIS for utility asset management and planning.

---

## Key Questions These Notes Answer

- How do I model a power utility's assets in a relational database?
- What is the IEC CIM and why does it matter for grid modernization?
- How do I integrate a SCADA historian with an analytics platform?
- How does a utility GIS support distribution system planning?
- What is master data management and why does it break down?

---

## Prerequisites
- [[00-foundations/programming/_index|Programming Foundations]]
- [[../software-engineering/_index|Software Engineering]] — database foundations

## Connects To
- [[../data-science-ai/_index|Data Science & AI]] — analytics on top of information systems
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]] — ADMS, OMS, GIS
- [[01-electrical-engineering/communications-networking/_index|Communications & Networking]] — SCADA, historians
