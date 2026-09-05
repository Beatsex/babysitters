---
name: specialization-authoring
description: "Written-artifact production and maintenance: getting prose from nothing to published, and keeping already-published prose true to the code it describes."
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: authoring
  process-count: 2
---

# specialization-authoring

## Overview

Written-artifact production and maintenance: getting prose from nothing to published, and keeping already-published prose true to the code it describes.

## Available Processes (2)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/authoring/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `documenter` (`specializations/authoring/documenter`) | Documenter persona. Scans existing docs → detects drift vs current code → |
| `editorial-lifecycle` (`specializations/authoring/editorial-lifecycle`) | Full editorial lifecycle for long-form written work: outline → draft → self-edit → fact-check → developmental-edit (via breakpoint) →… |

## Usage

Use this skill to route work into the `authoring` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
