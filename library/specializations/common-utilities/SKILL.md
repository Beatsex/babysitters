---
name: specialization-common-utilities
description: "Shared composition utilities for babysitter processes. These modules package the current quality bar — routed breakpoints, adversarial evidence-mandatory gates, parallel fan-out, kip recall/assert checkpoints — as importable helpers so processes stop re-implementing the patterns by hand."
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: common-utilities
  process-count: 5
---

# specialization-common-utilities

## Overview

Shared composition utilities for babysitter processes. These modules package the current quality bar — routed breakpoints, adversarial evidence-mandatory gates, parallel fan-out, kip recall/assert checkpoints — as importable helpers so processes stop re-implementing the patterns by hand.

## Available Processes (5)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/common-utilities/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `docx-conversion` (`specializations/common-utilities/docx-conversion`) | Reusable HTML-to-DOCX conversion task using pandoc with graceful fallback |
| `index` (`specializations/common-utilities`) | Common reusable utilities for babysitter process composition |
| `parallel-combinator` (`specializations/common-utilities/parallel-combinator`) | Parallel task combinator - fan-out/fan-in patterns for concurrent task execution with shared dependencies |
| `routed-gate-combinators-demo` (`specializations/common-utilities/routed-gate-combinators-demo`) | Exemplar process exercising the routed-gate combinators end-to-end: |
| `routed-gate-combinators` (`specializations/common-utilities/routed-gate-combinators`) | Routed-gate combinators — reusable quality-bar helpers: routed breakpoints |

## Subcategories

- `skills/`

## Usage

Use this skill to route work into the `common-utilities` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
