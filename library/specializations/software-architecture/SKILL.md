---
name: specialization-software-architecture
description: "Software Architecture and Design Patterns is a critical technical specialization focused on designing robust, scalable, and maintainable software systems. This specialization encompasses architectural thinking, design patterns, system trade-offs, and the ability to make informed technical…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: software-architecture
  process-count: 22
---

# specialization-software-architecture

## Overview

Software Architecture and Design Patterns is a critical technical specialization focused on designing robust, scalable, and maintainable software systems. This specialization encompasses architectural thinking, design patterns, system trade-offs, and the ability to make informed technical decisions that align with business goals.

## Available Processes (22)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/software-architecture/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `adr-documentation` (`software-architecture/adr-documentation`) | Architecture Decision Records (ADRs) lifecycle management process with decision analysis, template generation, review workflow, and ADR… |
| `api-design-specification` (`specializations/software-architecture/api-design-specification`) | API Design and Specification - Comprehensive API design process covering REST/GraphQL/gRPC APIs, |
| `atam-analysis` (`software-architecture/atam-analysis`) | Architecture Trade-off Analysis Method (ATAM) for evaluating software architectures against quality attributes |
| `c4-model-documentation` (`software-architecture/c4-model-documentation`) | Complete C4 Model architecture documentation process with hierarchical diagram generation (Context, Container, Component, Code levels) and… |
| `cloud-architecture-design` (`specializations/software-architecture/cloud-architecture-design`) | Cloud-native architecture design process with cloud provider selection, compute/data/network design, security planning, HA design, and… |
| `data-architecture-design` (`specializations/software-architecture/data-architecture-design`) | Data Architecture Design - Design comprehensive data architecture including data models, |
| `ddd-strategic-modeling` (`specializations/software-architecture/ddd-strategic-modeling`) | Domain-Driven Design Strategic Modeling - Identify bounded contexts, define context relationships, create context maps, |
| `devops-architecture-alignment` (`specializations/software-architecture/devops-architecture-alignment`) | DevOps Architecture Alignment - Comprehensive process for aligning software architecture with DevOps practices, |
| `event-storming` (`software-architecture/event-storming`) | Collaborative workshop technique for discovering domain events, commands, aggregates, and bounded contexts |
| `evil-fallback-audit` (`software-architecture/evil-fallback-audit`) | Scan a codebase for silent fallback mechanisms, catch-and-swallow patterns, degraded behavior paths, and configuration cascades that hide… |
| `here-be-dragons-audit` (`software-architecture/here-be-dragons-audit`) | Scan a codebase for unmarked coupling, maintenance hazards, evil fallbacks, hidden caveats, tech debt, and places that need "here be… |
| `iac-review` (`specializations/software-architecture/iac-review`) | Infrastructure as Code Review - Comprehensive IaC validation ensuring best practices, |
| `microservices-decomposition` (`specializations/software-architecture/microservices-decomposition`) | Microservices Decomposition Strategy - Analyze monolithic applications and design optimal microservices architecture |
| `migration-strategy` (`specializations/software-architecture/migration-strategy`) | Migration Strategy Planning - Comprehensive migration strategy development for legacy systems, |
| `observability-implementation` (`specializations/software-architecture/observability-implementation`) | Observability Implementation - Comprehensive process for implementing observability through structured |
| `performance-optimization` (`specializations/software-architecture/performance-optimization`) | Performance Optimization Process - Systematic performance improvement through profiling, bottleneck |
| `quality-attributes-workshop` (`software-architecture/quality-attributes-workshop`) | Facilitated workshop for identifying, prioritizing, and specifying quality attributes (non-functional requirements) with scenario-based… |
| `refactoring-plan` (`software-architecture/refactoring-plan`) | Systematic refactoring plan creation process with technical debt identification, prioritization, test safety net creation, and actionable… |
| `resilience-patterns` (`software-architecture/resilience-patterns`) | Resilience pattern implementation process with failure point analysis, pattern selection, circuit breaker design, bulkhead implementation,… |
| `security-architecture-review` (`specializations/software-architecture/security-architecture-review`) | Security-focused architecture review including threat modeling, security pattern validation, and vulnerability assessment |
| `system-design-review` (`software-architecture/system-design-review`) | Structured system design review process for evaluating software architectures against quality attributes, identifying risks, and ensuring… |
| `tech-stack-evaluation` (`specializations/software-architecture/tech-stack-evaluation`) | Technology Stack Evaluation - Structured process for evaluating and selecting technologies |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `software-architecture` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
