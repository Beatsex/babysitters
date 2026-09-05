---
name: specialization-communication
description: "Processes for communication work: channel management (Slack/Discord), content production and validation, and governed multi-audience announcements. The specialization layers a flagship orchestrated pipeline over four Style-B persona point files."
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: communication
  process-count: 5
---

# specialization-communication

## Overview

Processes for communication work: channel management (Slack/Discord), content production and validation, and governed multi-audience announcements. The specialization layers a flagship orchestrated pipeline over four Style-B persona point files.

## Available Processes (5)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/communication/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `content-validator` (`specializations/communication/content-validator`) | Content-validator persona. Scans text as devil's advocate → flags issues |
| `content-writer` (`specializations/communication/content-writer`) | Content-writer persona. Brief (audience/purpose/channel/KPIs) → plan (structure, |
| `discord-manager` (`specializations/communication/discord-manager`) | Discord-manager persona. Scan server/unanswered-mentions → classify each |
| `multi-audience-announcement-pipeline` (`communication/multi-audience-announcement-pipeline`) | Flagship end-to-end governed announcement pipeline: source-material |
| `slack-manager` (`specializations/communication/slack-manager`) | Slack-manager persona. Scan channels/unanswered-mentions → classify each |

## Usage

Use this skill to route work into the `communication` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
