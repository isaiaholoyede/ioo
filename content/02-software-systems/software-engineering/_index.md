---
title: Software Engineering
date: 2026-07-02
tags:
  - software/engineering
  - type/roadmap
description: Designing, building, and maintaining software at scale — architecture, APIs, testing, and DevOps.
---

# Software Engineering

Software engineering is the discipline of building reliable, maintainable, and scalable software systems. These notes go beyond programming syntax to cover the principles, patterns, and practices that make software work in the real world.

---

## Core Topics

### System Design & Architecture
Monoliths vs. microservices, event-driven architecture, layered architecture, domain-driven design (DDD), CAP theorem, scalability patterns.

### APIs & Interfaces
REST, GraphQL, gRPC, WebSockets. API design principles, versioning, authentication, documentation.

### Databases
Relational databases (SQL, normalization, indexing), NoSQL (document, key-value, time-series, graph), query optimization, transactions, ACID vs. BASE.

### Testing & Quality
Unit, integration, end-to-end testing. Test-driven development (TDD), property-based testing, coverage, CI quality gates.

### DevOps & Deployment
CI/CD pipelines, Docker, Kubernetes, infrastructure as code (Terraform), observability (logs, metrics, traces), SLOs and SLAs.

### Software Design Patterns
Creational, structural, behavioral patterns. SOLID principles. Refactoring and technical debt management.

### Distributed Systems
Consistency models, distributed consensus (Raft, Paxos), message queues (Kafka, RabbitMQ), eventual consistency, distributed tracing.

### Performance Engineering
Profiling, benchmarking, caching strategies (Redis, CDN), database query optimization, load testing.

---

## Key Questions These Notes Answer

- How do I design a system that handles 10x the current load?
- When should I use a microservice vs. keeping things in a monolith?
- How do I design an API that is easy to use and hard to misuse?
- How do I ensure software quality without slowing down delivery?
- How does distributed consensus work and why does it matter?

---

## Prerequisites
- [[00-foundations/programming/_index|Programming Foundations]]

## Connects To
- [[../agentic-ai/_index|Agentic AI]] — building the infrastructure AI agents run on
- [[../cybersecurity/_index|Cybersecurity]] — secure software design
- [[../information-systems/_index|Information Systems]] — data layer
- [[03-domain-expertise/technical-product-management/_index|Technical Product Management]]
- [[04-credentials/phd-electrical-engineering/_index|PhD EE]] — software tools for research
