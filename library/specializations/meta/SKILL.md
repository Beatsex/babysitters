---
name: specialization-meta
description: "The Meta Specialization is a self-referential specialization focused on the creation and management of the Babysitter SDK's organizational structures: domains, specializations, processes, skills, and agents. This specialization codifies the methodology for building and extending the SDK's…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: meta
  process-count: 7
---

# specialization-meta

## Overview

The Meta Specialization is a self-referential specialization focused on the creation and management of the Babysitter SDK's organizational structures: domains, specializations, processes, skills, and agents. This specialization codifies the methodology for building and extending the SDK's capability library.

## Available Processes (7)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/meta/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `agent-creation` (`meta/agent-creation`) | Create a new agent with AGENT.md and README.md including role definition, expertise, and prompt templates |
| `library-enrichment` (`meta/library-enrichment`) | Reusable batch enrichment of the process library: survey backlogs and |
| `plugin-creation` (`meta/plugin-creation`) | Create a new babysitter plugin package with install/uninstall/configure instructions, optional process files, migrations, and marketplace… |
| `process-creation` (`meta/process-creation`) | Create a new process JS file from requirements with task definitions, quality gates, and breakpoints |
| `skill-creation` (`meta/skill-creation`) | Create a new skill with SKILL.md, README.md, and supporting files |
| `specialization-creation` (`meta/specialization-creation`) | Create a new specialization with all 7 phases in sequence - from research to integration |
| `specialization-validator` (`meta/specialization-validator`) | Validate a specialization for completeness across all 7 phases |

## Subcategories

- `agents/`
- `assimilation/`
- `atlas/`
- `harnesses/`
- `skills/`

## Usage

Use this skill to route work into the `meta` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
