---
name: specialization-sourcing
description: "This single-process specialization was folded into the `research` specialization per the process-library placement policy. `news-intelligence-pipeline.js` is an end-to-end scanning/monitoring pipeline (discover -> dedupe -> filter signal -> per-portfolio impact assessment -> synthesize -> route…"
---

# specialization-sourcing

This single-process specialization was folded into the `research` specialization per the process-library placement policy. `news-intelligence-pipeline.js` is an end-to-end scanning/monitoring pipeline (discover -> dedupe -> filter signal -> per-portfolio impact assessment -> synthesize -> route alerts -> track follow-through) — a natural sibling of the research scanner point-tasks (novelties-scanner, vendor-researcher, evangelist).

This skill is the entry point for the `sourcing` specialization in the babysitter process library. Full process/skill/agent inventory, descriptions, and exact invocation commands live in the canonical file:

`library/specializations/sourcing/SKILL.md`

Read that file before acting - it lists every available process (with the `babysitter run:create` command to run it), and any sub-skills or sub-agents defined under this category. Do not duplicate or re-derive that inventory here; treat it as the source of truth and this file only as the trigger/pointer.
