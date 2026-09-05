---
name: specialization-customer-support
description: "The first full agentic **customer-facing workflow** specialization in the library. It closes the census's top customer-facing gap: `domains/business/customer-experience` holds **20 pre-bar point tasks with zero breakpoint routing**, and no customer-support specialization existed anywhere. This…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: customer-support
  process-count: 2
---

# specialization-customer-support

## Overview

The first full agentic **customer-facing workflow** specialization in the library. It closes the census's top customer-facing gap: `domains/business/customer-experience` holds **20 pre-bar point tasks with zero breakpoint routing**, and no customer-support specialization existed anywhere. This specialization carries a real support ticket end-to-end with routed human approvals on every action that leaves the org boundary, while the 20 point tasks remain independently callable utilities (mapped per phase below).

## Available Processes (2)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/customer-support/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `onboarding-lifecycle` (`customer-support/onboarding-lifecycle`) | Flagship gated end-to-end customer-onboarding workflow. Carries one signed |
| `ticket-lifecycle` (`customer-support/ticket-lifecycle`) | Flagship end-to-end support-ticket lifecycle: intake+classification -> |

## Usage

Use this skill to route work into the `customer-support` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
