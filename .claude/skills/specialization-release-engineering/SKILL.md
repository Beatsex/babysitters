---
name: specialization-release-engineering
description: "Flagship release lifecycle for the library: release cut and versioning -> parallel changelog + pre-flight verification -> an adversarial release-readiness gate that EXECUTES the built artifact -> a policy-gated production deploy -> staged rollout (canary -> partial -> full) with stage-promotion…"
---

# specialization-release-engineering

Flagship release lifecycle for the library: release cut and versioning -> parallel changelog + pre-flight verification -> an adversarial release-readiness gate that EXECUTES the built artifact -> a policy-gated production deploy -> staged rollout (canary -> partial -> full) with stage-promotion approvals and per-stage verification -> an adversarial post-release gate -> a regression path with severity-routed escalation and a policy-gated rollback -> kip-backed release memory. This is a brand-new specialization directory.

This skill is the entry point for the `release-engineering` specialization in the babysitter process library. Full process/skill/agent inventory, descriptions, and exact invocation commands live in the canonical file:

`library/specializations/release-engineering/SKILL.md`

Read that file before acting - it lists every available process (with the `babysitter run:create` command to run it), and any sub-skills or sub-agents defined under this category. Do not duplicate or re-derive that inventory here; treat it as the source of truth and this file only as the trigger/pointer.
