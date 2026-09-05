---
name: specialization-internationalization
description: "The first **internationalization / i18n** specialization in the library. It owns the full agentic localization pipeline — carrying a source codebase from hardcoded strings through per-locale translation to a policy-gated production release — with per-locale parallel fan-out and human approval on…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: internationalization
  process-count: 1
---

# specialization-internationalization

## Overview

The first **internationalization / i18n** specialization in the library. It owns the full agentic localization pipeline — carrying a source codebase from hardcoded strings through per-locale translation to a policy-gated production release — with per-locale parallel fan-out and human approval on every action that commits spend or ships a locale to users. No i18n specialization existed anywhere in `library/` before this one.

## Available Processes (1)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/internationalization/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `localization-lifecycle` (`internationalization/localization-lifecycle`) | Flagship extraction-to-release localization lifecycle with per-locale |

## Usage

Use this skill to route work into the `internationalization` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
