---
name: specialization-research
description: "Processes for systematic research analysis, standards comparison auditing, and extraction verification, plus a flagship end-to-end research-publication pipeline that composes the scanner point-tasks below."
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: research
  process-count: 7
---

# specialization-research

## Overview

Processes for systematic research analysis, standards comparison auditing, and extraction verification, plus a flagship end-to-end research-publication pipeline that composes the scanner point-tasks below.

## Available Processes (7)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/research/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `evangelist` (`specializations/research/evangelist`) | Evangelist persona. Scans recent project activity (commits, PRs, docs, |
| `news-intelligence-pipeline` (`specializations/research/news-intelligence-pipeline`) | End-to-end sourcing + intelligence workflow: discover → monitor → dedupe → filter-signal → per-portfolio impact-assess → synthesize →… |
| `novelties-scanner` (`specializations/research/novelties-scanner`) | Novelties Scanner persona — detects, analyzes, and reports on novel |
| `patentable-novelties` (`specializations/research/patentable-novelties`) | Patentable Novelties persona — extends the novelties scanner with |
| `research-publication-workflow` (`specializations/research/research-publication-workflow`) | Flagship research-publication pipeline: frame the question -> plan gathering |
| `standards-gap-audit` (`standards-gap-audit`) | Generic gap audit process for standards research documents. |
| `vendor-researcher` (`specializations/research/vendor-researcher`) | Vendor-researcher persona. Discover candidate vendors → analyse each in |

## Usage

Use this skill to route work into the `research` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
