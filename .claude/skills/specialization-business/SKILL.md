---
name: specialization-business
description: "This single-process specialization was folded into the matching business domain subdomain per the process-library placement policy: domain-specific processes live under `specializations/domains/<domain>`, cross-domain processes under `specializations/shared`. A stand-alone `business/` directory…"
---

# specialization-business

This single-process specialization was folded into the matching business domain subdomain per the process-library placement policy: domain-specific processes live under `specializations/domains/<domain>`, cross-domain processes under `specializations/shared`. A stand-alone `business/` directory holding one revenue process was vestigial.

This skill is the entry point for the `business` specialization in the babysitter process library. Full process/skill/agent inventory, descriptions, and exact invocation commands live in the canonical file:

`library/specializations/business/SKILL.md`

Read that file before acting - it lists every available process (with the `babysitter run:create` command to run it), and any sub-skills or sub-agents defined under this category. Do not duplicate or re-derive that inventory here; treat it as the source of truth and this file only as the trigger/pointer.
