---
name: specialization-mlops
description: "Flagship model-lifecycle for the library: dataset governance intake (parallel per-dataset lineage/consent/retention checks) -> eval-harness design -> executed training/eval runs -> an adversarial eval-review gate that RE-RUNS a sampled eval and diffs metrics -> a policy-gated model promotion with…"
---

# specialization-mlops

Flagship model-lifecycle for the library: dataset governance intake (parallel per-dataset lineage/consent/retention checks) -> eval-harness design -> executed training/eval runs -> an adversarial eval-review gate that RE-RUNS a sampled eval and diffs metrics -> a policy-gated model promotion with an executed serving smoke -> drift-monitoring setup with an executed drift-detection stub -> an adversarial drift-review gate -> a drift path with severity-routed escalation and a policy-gated rollback/retirement -> kip-backed model-registry memory. This is a brand-new specialization directory (verified: no prior `mlops` dir anywhere in `library/`).

This skill is the entry point for the `mlops` specialization in the babysitter process library. Full process/skill/agent inventory, descriptions, and exact invocation commands live in the canonical file:

`library/specializations/mlops/SKILL.md`

Read that file before acting - it lists every available process (with the `babysitter run:create` command to run it), and any sub-skills or sub-agents defined under this category. Do not duplicate or re-derive that inventory here; treat it as the source of truth and this file only as the trigger/pointer.
