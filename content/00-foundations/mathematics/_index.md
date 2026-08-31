---
title: Mathematical Foundations
date: 2026-07-02
tags:
  - foundations/math
  - type/roadmap
description: The mathematical language of engineering — calculus, linear algebra, differential equations, probability, and discrete math.
draft: false
---

# Mathematical Foundations

Mathematics is the shared language of every technical domain in this vault. These notes are not abstract exercises — every concept here connects directly to power systems analysis, control theory, machine learning, or signal processing.

---

## Core Topics

### [[Precalculus]]
College algebra, Trigonometry.

### Calculus
Limits, derivatives, integrals, multivariable calculus, vector calculus. The language of rates of change and accumulation.

$$\frac{d}{dt}\int_a^{g(t)} f(x)\,dx = f(g(t)) \cdot g'(t)$$

### Linear Algebra
Vectors, matrices, eigenvalues, eigenvectors, decompositions. The language of systems and transformations.

$$A\mathbf{x} = \lambda\mathbf{x}$$

### Differential Equations
ODEs, PDEs, Laplace transforms, state-space methods. The language of dynamic systems.

$$\mathcal{L}\{f(t)\} = \int_0^\infty f(t)e^{-st}\,dt$$

### Probability & Statistics
Probability spaces, distributions, expectation, hypothesis testing, Bayesian inference.

### Discrete Mathematics
Logic, set theory, combinatorics, graph theory, number theory. The language of algorithms and computation.

### Complex Analysis
Complex numbers, phasors, Fourier analysis, frequency domain methods. Essential for AC power and signals.

$$e^{j\theta} = \cos\theta + j\sin\theta$$

---

## Key Questions These Notes Answer

- How do I model a dynamic system mathematically?
- What does an eigenvalue mean physically in a power system?
- How does a Fourier transform connect time and frequency domains?
- How do I quantify uncertainty in an engineering measurement?

---

## Prerequisites
High school algebra and trigonometry.

## Connects To
- [[01-electrical-engineering/control-systems/_index|Control Systems]] — differential equations, Laplace transforms
- [[01-electrical-engineering/power-systems/_index|Power Systems]] — complex analysis, phasors, linear algebra
- [[02-software-systems/data-science-ai/_index|Data Science & AI]] — linear algebra, probability, statistics
- [[04-credentials/fe-exam/_index|FE Exam]] — mathematics is the largest section
