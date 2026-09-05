---
name: specialization-backend-development
description: "Backend Development is a specialization focused on building robust, maintainable backend services, APIs, and domain-driven systems. It covers the full spectrum of server-side engineering: from designing clean domain models and hexagonal architectures to implementing test-driven workflows that…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: backend-development
  process-count: 1
---

# specialization-backend-development

## Overview

Backend Development is a specialization focused on building robust, maintainable backend services, APIs, and domain-driven systems. It covers the full spectrum of server-side engineering: from designing clean domain models and hexagonal architectures to implementing test-driven workflows that deliver sub-second feedback.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/backend-development/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `backend-service-delivery` (`backend-development/backend-service-delivery`) | Flagship end-to-end backend service delivery process: requirements+domain |

## Subcategories

- `skills/`

## Usage

Use this skill to route work into the `backend-development` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
