---
name: specialization-incident-management
description: "Single owner for incident handling across the library. This specialization carries the flagship detection-to-postmortem lifecycle — severity classification, commander mobilization, parallel mitigation strands, severity-routed policy gates for every externally visible action, an adversarial…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: incident-management
  process-count: 1
---

# specialization-incident-management

## Overview

Single owner for incident handling across the library. This specialization carries the flagship detection-to-postmortem lifecycle — severity classification, commander mobilization, parallel mitigation strands, severity-routed policy gates for every externally visible action, an adversarial postmortem-completeness gate, and kip-backed incident memory across runs.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/incident-management/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `incident-lifecycle` (`incident-management/incident-lifecycle`) | Flagship detection-to-postmortem incident lifecycle with severity-routed |

## Usage

Use this skill to route work into the `incident-management` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
