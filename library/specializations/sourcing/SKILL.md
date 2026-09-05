---
name: specialization-sourcing
description: "This single-process specialization was folded into the `research` specialization per the process-library placement policy. `news-intelligence-pipeline.js` is an end-to-end scanning/monitoring pipeline (discover -> dedupe -> filter signal -> per-portfolio impact assessment -> synthesize -> route…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: sourcing
  process-count: 1
---

# specialization-sourcing

## Overview

This single-process specialization was folded into the `research` specialization per the process-library placement policy. `news-intelligence-pipeline.js` is an end-to-end scanning/monitoring pipeline (discover -> dedupe -> filter signal -> per-portfolio impact assessment -> synthesize -> route alerts -> track follow-through) — a natural sibling of the research scanner point-tasks (novelties-scanner, vendor-researcher, evangelist).

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/sourcing/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `news-intelligence-pipeline` (`specializations/sourcing/news-intelligence-pipeline`) | (no description) |

## Usage

Use this skill to route work into the `sourcing` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
