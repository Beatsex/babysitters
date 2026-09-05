---
name: specialization-mlops
description: "Flagship model-lifecycle for the library: dataset governance intake (parallel per-dataset lineage/consent/retention checks) -> eval-harness design -> executed training/eval runs -> an adversarial eval-review gate that RE-RUNS a sampled eval and diffs metrics -> a policy-gated model promotion with…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: mlops
  process-count: 1
---

# specialization-mlops

## Overview

Flagship model-lifecycle for the library: dataset governance intake (parallel per-dataset lineage/consent/retention checks) -> eval-harness design -> executed training/eval runs -> an adversarial eval-review gate that RE-RUNS a sampled eval and diffs metrics -> a policy-gated model promotion with an executed serving smoke -> drift-monitoring setup with an executed drift-detection stub -> an adversarial drift-review gate -> a drift path with severity-routed escalation and a policy-gated rollback/retirement -> kip-backed model-registry memory. This is a brand-new specialization directory (verified: no prior `mlops` dir anywhere in `library/`).

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/mlops/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `model-lifecycle` (`mlops/model-lifecycle`) | Flagship end-to-end model lifecycle: dataset governance intake (parallel |

## Usage

Use this skill to route work into the `mlops` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
