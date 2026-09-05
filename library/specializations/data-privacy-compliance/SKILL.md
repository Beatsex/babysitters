---
name: specialization-data-privacy-compliance
description: "Privacy operations lifecycle for DSAR (data-subject access request), erasure, and DPIA work: intake and identity verification, kip-reconciled data mapping, parallel multi-system retrieval, exemption analysis with mandatory legal bases, policy-gated deletion and disclosure, and deadline-audited…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: data-privacy-compliance
  process-count: 1
---

# specialization-data-privacy-compliance

## Overview

Privacy operations lifecycle for DSAR (data-subject access request), erasure, and DPIA work: intake and identity verification, kip-reconciled data mapping, parallel multi-system retrieval, exemption analysis with mandatory legal bases, policy-gated deletion and disclosure, and deadline-audited closure — all inside statutory clocks. This specialization **complements** `security-compliance` and supersedes nothing.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/data-privacy-compliance/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `dsar-lifecycle` (`data-privacy-compliance/dsar-lifecycle`) | Single-workflow DSAR (data-subject access request) lifecycle with statutory |

## Usage

Use this skill to route work into the `data-privacy-compliance` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
