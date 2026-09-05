---
name: specialization-accessibility
description: "The **first accessibility specialization** in the library (verified: none existed anywhere under `library/`). It carries a real product through a full agentic WCAG audit-to-conformance lifecycle with routed human approvals on every action that commits engineering effort or leaves the org boundary.…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: accessibility
  process-count: 1
---

# specialization-accessibility

## Overview

The **first accessibility specialization** in the library (verified: none existed anywhere under `library/`). It carries a real product through a full agentic WCAG audit-to-conformance lifecycle with routed human approvals on every action that commits engineering effort or leaves the org boundary. It **consolidates the previously scattered near-misses** by referencing them as seeds rather than duplicating their content, and **supersedes** the pre-bar `web-development/accessibility-audit-remediation.js` (now `@deprecated`).

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/accessibility/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `wcag-audit-remediation` (`accessibility/wcag-audit-remediation`) | Flagship end-to-end WCAG audit & remediation lifecycle: scope definition -> |

## Usage

Use this skill to route work into the `accessibility` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
