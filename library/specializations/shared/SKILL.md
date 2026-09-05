---
name: specialization-shared
description: "`shared/` is the home for cross-domain library assets — skills, and eventually agents and processes, that are useful across many specializations rather than belonging to any single domain. Per the library placement policy, only assets with genuine cross-domain applicability live here."
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: shared
  process-count: 0
---

# specialization-shared

## Overview

`shared/` is the home for cross-domain library assets — skills, and eventually agents and processes, that are useful across many specializations rather than belonging to any single domain. Per the library placement policy, only assets with genuine cross-domain applicability live here.

## Subcategories

- `skills/`

## Usage

Use this skill to route work into the `shared` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
