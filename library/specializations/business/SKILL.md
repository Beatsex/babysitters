---
name: specialization-business
description: "This single-process specialization was folded into the matching business domain subdomain per the process-library placement policy: domain-specific processes live under `specializations/domains/<domain>`, cross-domain processes under `specializations/shared`. A stand-alone `business/` directory…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: business
  process-count: 1
---

# specialization-business

## Overview

This single-process specialization was folded into the matching business domain subdomain per the process-library placement policy: domain-specific processes live under `specializations/domains/<domain>`, cross-domain processes under `specializations/shared`. A stand-alone `business/` directory holding one revenue process was vestigial.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/business/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `revenue` (`specializations/business/revenue`) | (no description) |

## Usage

Use this skill to route work into the `business` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
