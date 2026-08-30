---
title: Data Science & Artificial Intelligence
date: 2026-07-02
tags:
  - software/data-science
  - software/ai
  - type/roadmap
description: Statistics, machine learning, deep learning, data pipelines, and AI applied to engineering problems.
draft: true
---

# Data Science & Artificial Intelligence

Data science and AI are transforming engineering — from predictive asset maintenance to load forecasting, grid optimization, and fault detection. These notes cover the theory and practice of extracting insight and building intelligence from data.

---

## Core Topics

### Statistics & Probability
Descriptive statistics, probability distributions, hypothesis testing, confidence intervals, Bayesian inference, regression.

### Data Engineering
Data pipelines, ETL/ELT, data quality, feature engineering, time-series data handling, streaming vs. batch processing.

### Machine Learning — Supervised
Linear and logistic regression, decision trees, random forests, gradient boosting (XGBoost, LightGBM), SVMs, model evaluation and validation.

### Machine Learning — Unsupervised
Clustering (k-means, DBSCAN), dimensionality reduction (PCA, t-SNE, UMAP), anomaly detection.

### Deep Learning
Neural networks, backpropagation, CNNs, RNNs/LSTMs, Transformers, transfer learning, training at scale.

$$\mathcal{L} = -\frac{1}{N}\sum_{i=1}^N \left[y_i \log \hat{y}_i + (1-y_i)\log(1-\hat{y}_i)\right]$$

### Time Series Analysis
ARIMA, seasonal decomposition, Prophet, LSTM for time series. Load forecasting, solar/wind generation forecasting.

### AI in Power Systems & Energy
Load forecasting, fault detection, predictive maintenance, optimal dispatch with ML, DER forecasting, grid anomaly detection.

### MLOps & Model Deployment
Model versioning, experiment tracking (MLflow), deployment patterns, monitoring drift, retraining pipelines.

---

## Key Questions These Notes Answer

- How do I build a load forecasting model for a distribution feeder?
- How does anomaly detection work for detecting equipment faults?
- What is the difference between supervised and unsupervised learning?
- How do I deploy a ML model into a production engineering system?
- How do Transformers work and why are they dominant in AI?

---

## Prerequisites
- [[00-foundations/mathematics/_index|Mathematical Foundations]] — linear algebra, probability, calculus
- [[00-foundations/programming/_index|Programming Foundations]]

## Connects To
- [[../agentic-ai/_index|Agentic AI]] — LLMs are the foundation of modern agents
- [[../information-systems/_index|Information Systems]] — data infrastructure
- [[03-domain-expertise/distribution-system-operator/_index|Distribution System Operator]] — analytics applications
- [[04-credentials/phd-electrical-engineering/_index|PhD EE]] — ML for power systems research
- [[04-credentials/phd-energy-engineering/_index|PhD Energy]] — AI for energy systems
