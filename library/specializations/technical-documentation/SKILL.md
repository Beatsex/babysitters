---
name: specialization-technical-documentation
description: "Technical documentation specialization focuses on creating clear, accurate, and accessible documentation for technical products, systems, and processes. This discipline bridges the gap between complex technical concepts and the audiences that need to understand them, whether developers, end users,…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: technical-documentation
  process-count: 21
---

# specialization-technical-documentation

## Overview

Technical documentation specialization focuses on creating clear, accurate, and accessible documentation for technical products, systems, and processes. This discipline bridges the gap between complex technical concepts and the audiences that need to understand them, whether developers, end users, system administrators, or business stakeholders.

## Available Processes (21)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/technical-documentation/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `adr-docs` (`technical-documentation/adr-docs`) | Complete Architecture Decision Records (ADR) documentation lifecycle with decision analysis, alternatives research, template-based… |
| `api-doc-generation` (`specializations/technical-documentation/api-doc-generation`) | Automated process to generate comprehensive API documentation from OpenAPI/Swagger specifications |
| `api-reference-docs` (`specializations/technical-documentation/api-reference-docs`) | API Reference Documentation with Code Examples - Comprehensive process for creating complete API reference |
| `arch-docs-c4` (`technical-documentation/arch-docs-c4`) | Complete C4 Model architecture documentation process for technical documentation with focus on clarity, accessibility, and multiple… |
| `content-strategy` (`specializations/technical-documentation/content-strategy`) | Content Strategy and Information Architecture Design process for planning and organizing technical documentation with user journey… |
| `data-model-docs` (`specializations/technical-documentation/data-model-docs`) | Data Model and Schema Documentation - Comprehensive process for documenting entity relationships, |
| `docs-as-code-pipeline` (`specializations/technical-documentation/docs-as-code-pipeline`) | Docs-as-Code CI/CD Pipeline Setup - Implement comprehensive documentation-as-code workflow with version control, |
| `docs-audit` (`specializations/technical-documentation/docs-audit`) | Documentation Audit and Quality Assessment process with comprehensive analysis, scoring, accessibility review, and actionable… |
| `docs-localization` (`specializations/technical-documentation/docs-localization`) | Documentation Localization and Translation Management - Comprehensive process for internationalizing |
| `docs-pr-workflow` (`specializations/technical-documentation/docs-pr-workflow`) | Automated workflow for reviewing documentation pull requests with style validation, automated checks, and approval gates |
| `docs-testing` (`specializations/technical-documentation/docs-testing`) | Comprehensive documentation testing and validation process including accuracy verification, link checking, code example validation,… |
| `docs-versioning` (`specializations/technical-documentation/docs-versioning`) | Documentation Versioning and Release Coordination - Automated process for managing documentation |
| `how-to-guides` (`technical-documentation/how-to-guides`) | Task-oriented how-to guide development process with task analysis, goal-oriented content structure, step-by-step instructions, validation,… |
| `incident-docs` (`technical-documentation/incident-docs`) | Incident Response and Post-Mortem Documentation process with incident analysis, timeline reconstruction, root cause analysis, impact… |
| `interactive-tutorials` (`technical-documentation/interactive-tutorials`) | Complete interactive tutorial and learning content creation process with code playgrounds, executable notebooks, and step-by-step… |
| `knowledge-base-setup` (`specializations/technical-documentation/knowledge-base-setup`) | Knowledge Base Setup and Content Organization process with information architecture design, content structure creation, taxonomy… |
| `runbook-docs` (`technical-documentation/runbook-docs`) | Runbook and Operational Procedure Documentation process with service overview, deployment procedures, incident response, troubleshooting… |
| `sdk-doc-generation` (`specializations/technical-documentation/sdk-doc-generation`) | SDK and Client Library Documentation Generation - Automated generation of comprehensive SDK |
| `style-guide-enforcement` (`specializations/technical-documentation/style-guide-enforcement`) | Style Guide Creation and Enforcement process with style guide development, automated enforcement rules, quality checks, and continuous… |
| `terminology-management` (`specializations/technical-documentation/terminology-management`) | Terminology Management and Consistency Checking - Process for managing terminology databases, |
| `user-guide-docs` (`technical-documentation/user-guide-docs`) | User Guide and Getting Started Documentation process with content discovery, structure design, progressive tutorial creation, quality… |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `technical-documentation` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
