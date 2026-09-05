---
name: specialization-release-engineering
description: "Flagship release lifecycle for the library: release cut and versioning -> parallel changelog + pre-flight verification -> an adversarial release-readiness gate that EXECUTES the built artifact -> a policy-gated production deploy -> staged rollout (canary -> partial -> full) with stage-promotion…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: release-engineering
  process-count: 1
---

# specialization-release-engineering

## Overview

Flagship release lifecycle for the library: release cut and versioning -> parallel changelog + pre-flight verification -> an adversarial release-readiness gate that EXECUTES the built artifact -> a policy-gated production deploy -> staged rollout (canary -> partial -> full) with stage-promotion approvals and per-stage verification -> an adversarial post-release gate -> a regression path with severity-routed escalation and a policy-gated rollback -> kip-backed release memory. This is a brand-new specialization directory.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/release-engineering/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `release-lifecycle` (`release-engineering/release-lifecycle`) | Flagship end-to-end release lifecycle with policy-gated production deploy, |

## Usage

Use this skill to route work into the `release-engineering` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
