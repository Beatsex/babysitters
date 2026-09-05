---
name: specialization-internationalization
description: "The first **internationalization / i18n** specialization in the library. It owns the full agentic localization pipeline — carrying a source codebase from hardcoded strings through per-locale translation to a policy-gated production release — with per-locale parallel fan-out and human approval on…"
---

# specialization-internationalization

The first **internationalization / i18n** specialization in the library. It owns the full agentic localization pipeline — carrying a source codebase from hardcoded strings through per-locale translation to a policy-gated production release — with per-locale parallel fan-out and human approval on every action that commits spend or ships a locale to users. No i18n specialization existed anywhere in `library/` before this one.

This skill is the entry point for the `internationalization` specialization in the babysitter process library. Full process/skill/agent inventory, descriptions, and exact invocation commands live in the canonical file:

`library/specializations/internationalization/SKILL.md`

Read that file before acting - it lists every available process (with the `babysitter run:create` command to run it), and any sub-skills or sub-agents defined under this category. Do not duplicate or re-derive that inventory here; treat it as the source of truth and this file only as the trigger/pointer.
