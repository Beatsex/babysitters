---
name: specialization-product-management
description: "The Product Management and Product Strategy specialization equips AI agents and development teams with frameworks, methodologies, and best practices for building successful products. This specialization focuses on customer-centric product development, strategic decision-making, and data-driven…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: product-management
  process-count: 20
---

# specialization-product-management

## Overview

The Product Management and Product Strategy specialization equips AI agents and development teams with frameworks, methodologies, and best practices for building successful products. This specialization focuses on customer-centric product development, strategic decision-making, and data-driven prioritization.

## Available Processes (20)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/product-management/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `beta-program` (`specializations/product-management/beta-program`) | Beta Program Planning and Execution - Comprehensive process for planning, launching, and managing |
| `competitive-analysis` (`product-management/competitive-analysis`) | Comprehensive competitive analysis and market positioning framework with competitor identification, feature comparison, SWOT analysis,… |
| `conversion-funnel-analysis` (`product-management/conversion-funnel-analysis`) | Conversion Funnel Analysis - Comprehensive process for analyzing user conversion funnels, |
| `customer-advisory-board` (`product-management/customer-advisory-board`) | Customer Advisory Board (CAB) Setup process with program purpose definition, member selection criteria, program structure design, meeting… |
| `feature-definition-prd` (`product-management/feature-definition-prd`) | Complete Feature Definition and PRD Creation process with problem statement analysis, user story generation, acceptance criteria… |
| `jtbd-analysis` (`product-management/jtbd-analysis`) | Jobs-to-be-Done (JTBD) Analysis - Structured process for understanding customer jobs, |
| `metrics-dashboard` (`specializations/product-management/metrics-dashboard`) | Product Metrics Dashboard Setup - Comprehensive dashboard implementation process including |
| `moscow-prioritization` (`product-management/moscow-prioritization`) | MoSCoW prioritization framework implementation for product requirements with stakeholder engagement, Must/Should/Could/Won't… |
| `prd-to-spec` (`product-management/prd-to-spec`) | Orchestrate conversion of an approved PRD into a phase-gated implementation SPEC. Stack-agnostic. Self-contained — the prd-to-spec skill… |
| `product-council-review` (`product-management/product-council-review`) | Product Council and Review Process with council charter definition, membership structure, review cadence establishment, decision criteria… |
| `product-launch-gtm` (`specializations/product-management/product-launch-gtm`) | Product Launch Checklist and Go-To-Market (GTM) Plan - Comprehensive process for planning and |
| `product-lifecycle-e2e` (`product-management/product-lifecycle-e2e`) | Product lifecycle end-to-end — parallel discovery gathering (user-research |
| `product-market-fit` (`product-management/product-market-fit`) | Product-Market Fit Assessment process with PMF survey (40% rule), retention metrics, NPS analysis, growth indicators, qualitative signals,… |
| `product-vision-strategy` (`product-management/product-vision-strategy`) | Product Vision and Strategy Development process with vision statement crafting, strategic pillars definition, 3-year roadmap planning,… |
| `quarterly-roadmap` (`specializations/product-management/quarterly-roadmap`) | Quarterly Roadmap Planning - Comprehensive quarterly planning process including OKR review, |
| `retention-cohort-analysis` (`product-management/retention-cohort-analysis`) | Retention Analysis and Cohort Analysis - Comprehensive process for analyzing user retention patterns, |
| `rice-prioritization` (`product-management/rice-prioritization`) | RICE Prioritization Framework - Structured process for prioritizing features and initiatives |
| `stakeholder-alignment` (`product-management/stakeholder-alignment`) | Stakeholder Interview and Alignment process with stakeholder mapping, interview guide creation, expectation alignment, decision-making… |
| `task-to-prd` (`product-management/task-to-prd`) | Orchestrate conversion of a raw task (tracker ticket / file / inline text) into a fully characterized PRD via interactive clarification,… |
| `user-story-mapping` (`product-management/user-story-mapping`) | User Story Mapping process with user activity identification, task breakdown, story creation, prioritization, and release planning for… |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `product-management` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
