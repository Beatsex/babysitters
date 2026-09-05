---
name: specialization-observability
description: "The observability specialization is an **SLO-driven reliability practice**. Its flagship, `slo-lifecycle.js`, runs the end-to-end loop — SLO design -> telemetry-pipeline delivery -> alert tuning -> error-budget review cadence — with every production-affecting step closed by an adversarial…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: observability
  process-count: 2
---

# specialization-observability

## Overview

The observability specialization is an **SLO-driven reliability practice**. Its flagship, `slo-lifecycle.js`, runs the end-to-end loop — SLO design -> telemetry-pipeline delivery -> alert tuning -> error-budget review cadence — with every production-affecting step closed by an adversarial *executed-evidence* gate and a policy-gated routed breakpoint. Incident handling (detection -> mitigation -> postmortem) is **not** owned here: it lives in the [incident-management specialization](../incident-management/incident-lifecycle.js). The `sre/` subdirectory holds the cloud-specific SRE point tasks that predate the flagship.

## Available Processes (2)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/observability/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `incident-lifecycle` (`specializations/observability/incident-lifecycle`) | DEPRECATED. The full detection-to-postmortem incident lifecycle that once |
| `slo-lifecycle` (`observability/slo-lifecycle`) | Flagship end-to-end SLO practice for the observability specialization: |

## Subcategories

- `sre/`

## Usage

Use this skill to route work into the `observability` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
