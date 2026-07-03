---
title: Agentic AI
date: 2026-07-02
tags:
  - software/agentic-ai
  - type/roadmap
description: AI agents, tool use, multi-agent systems, LLM engineering, and the architecture of autonomous AI systems.
---

# Agentic AI

Agentic AI is the frontier where language models stop being question-answering tools and start being autonomous systems that plan, use tools, and complete multi-step tasks. These notes document the architecture, patterns, and engineering practices behind building reliable agentic systems.

---

## Core Topics

### Large Language Model Fundamentals
Transformer architecture, tokenization, context windows, attention mechanisms, fine-tuning vs. prompting, inference parameters.

### Prompt Engineering
System prompts, few-shot examples, chain-of-thought, structured outputs, XML formatting, prompt injection and defense.

### Tool Use & Function Calling
How LLMs call external tools, structured function schemas, tool result handling, error recovery patterns.

### Agentic Architectures
ReAct (Reasoning + Acting), Plan-and-Execute, Reflexion, and other agent frameworks. When each pattern applies.

### Multi-Agent Systems
Orchestrator-subagent patterns, agent handoffs, shared memory, agent communication, parallelism. Frameworks: LangGraph, AutoGen, Claude MCP.

### Model Context Protocol (MCP)
MCP architecture, server/client model, tool definitions, resource exposure, sampling. Building and consuming MCP servers.

### Memory Systems
In-context memory, external memory (vector databases, knowledge graphs), episodic vs. semantic memory, retrieval-augmented generation (RAG).

### RAG Systems
Chunking strategies, embedding models, vector databases (Pinecone, Chroma, pgvector), retrieval strategies, re-ranking, hybrid search.

### Evaluation & Reliability
Benchmarking agents, failure modes, hallucination mitigation, human-in-the-loop patterns, tracing and observability (LangSmith, Arize).

### Agentic AI in Engineering
Agents for code generation, document analysis, technical report writing, grid data analysis, standards lookup, and engineering workflow automation.

---

## Key Questions These Notes Answer

- What is the difference between a chain and an agent?
- How do I design a multi-agent system that doesn't fail silently?
- How does RAG work and when should I use it vs. fine-tuning?
- How do I build a reliable agent that uses external tools?
- What is MCP and how does it change how agents access capabilities?
- How do I evaluate whether my agent is actually working correctly?

---

## Prerequisites
- [[00-foundations/programming/_index|Programming Foundations]]
- [[../data-science-ai/_index|Data Science & AI]] — LLM foundations
- [[../software-engineering/_index|Software Engineering]] — system design for agent infrastructure

## Connects To
- [[05-consulting/_index|Technical Consulting]] — agentic AI as a consulting capability
- [[03-domain-expertise/technical-product-management/_index|Technical Product Management]] — building AI products
- [[04-credentials/mit-sloan-mba/_index|MIT Sloan MBA]] — AI strategy and business application
