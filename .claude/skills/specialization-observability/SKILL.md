---
name: specialization-observability
description: "The observability specialization is an **SLO-driven reliability practice**. Its flagship, `slo-lifecycle.js`, runs the end-to-end loop — SLO design -> telemetry-pipeline delivery -> alert tuning -> error-budget review cadence — with every production-affecting step closed by an adversarial…"
---

# specialization-observability

The observability specialization is an **SLO-driven reliability practice**. Its flagship, `slo-lifecycle.js`, runs the end-to-end loop — SLO design -> telemetry-pipeline delivery -> alert tuning -> error-budget review cadence — with every production-affecting step closed by an adversarial *executed-evidence* gate and a policy-gated routed breakpoint. Incident handling (detection -> mitigation -> postmortem) is **not** owned here: it lives in the [incident-management specialization](../incident-management/incident-lifecycle.js). The `sre/` subdirectory holds the cloud-specific SRE point tasks that predate the flagship.

This skill is the entry point for the `observability` specialization in the babysitter process library. Full process/skill/agent inventory, descriptions, and exact invocation commands live in the canonical file:

`library/specializations/observability/SKILL.md`

Read that file before acting - it lists every available process (with the `babysitter run:create` command to run it), and any sub-skills or sub-agents defined under this category. Do not duplicate or re-derive that inventory here; treat it as the source of truth and this file only as the trigger/pointer.
