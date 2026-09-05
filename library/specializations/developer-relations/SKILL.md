---
name: specialization-developer-relations
description: "The **first developer-relations specialization** in the library. Before it, the only devrel artifact anywhere was a single stub agent ([`../sdk-platform-development/agents/devrel/AGENT.md`](../sdk-platform-development/agents/devrel/AGENT.md), marked *implementation pending*) — referenced here as…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: developer-relations
  process-count: 1
---

# specialization-developer-relations

## Overview

The **first developer-relations specialization** in the library. Before it, the only devrel artifact anywhere was a single stub agent ([`../sdk-platform-development/agents/devrel/AGENT.md`](../sdk-platform-development/agents/devrel/AGENT.md), marked *implementation pending*) — referenced here as the seed, left in place, never edited. This specialization is additive: its personas are new `devrel-*` agents defined inline in the flagship process. It carries one product change end-to-end — from API-change intake through executed sample apps, adversarially verified content, policy-gated external publishing, and community engagement — with routed human approval on every action that leaves the org boundary.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/developer-relations/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `devrel-campaign` (`developer-relations/devrel-campaign`) | Flagship end-to-end governed developer-relations campaign carrying one |

## Usage

Use this skill to route work into the `developer-relations` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
