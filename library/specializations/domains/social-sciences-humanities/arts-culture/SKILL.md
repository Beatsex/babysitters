---
name: specialization-arts-culture
description: "This specialization bridges creative practice with cultural stewardship, encompassing the production, curation, preservation, and dissemination of artistic and cultural works. It combines aesthetic understanding, historical knowledge, technical skills, and administrative competencies to support…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: arts-culture
  process-count: 24
  skill-count: 15
  agent-count: 10
---

# specialization-arts-culture

## Overview

This specialization bridges creative practice with cultural stewardship, encompassing the production, curation, preservation, and dissemination of artistic and cultural works. It combines aesthetic understanding, historical knowledge, technical skills, and administrative competencies to support vibrant cultural ecosystems that enrich communities and preserve heritage for future generations.

## Available Processes (24)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/domains/social-sciences-humanities/arts-culture/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `arts-advocacy` (`arts-culture/arts-advocacy`) | Arts advocacy process for engaging legislators, building coalitions, and advocating for arts funding and cultural policy at local, state,… |
| `board-governance` (`arts-culture/board-governance`) | Best practices for managing trustee relations, board meetings, committee structures, fiduciary responsibilities, and organizational… |
| `budget-management` (`arts-culture/budget-management`) | Financial planning and management workflow for arts organizations including annual budgeting, cash flow management, variance analysis, and… |
| `collection-management` (`arts-culture/collection-management`) | Systematic approach to managing permanent collections including acquisition, documentation, cataloging, storage, loan coordination, and… |
| `collection-risk-assessment` (`arts-culture/collection-risk-assessment`) | Framework for identifying, evaluating, and mitigating risks to cultural collections including natural disasters, theft, environmental… |
| `community-engagement` (`arts-culture/community-engagement`) | Framework for building meaningful relationships with diverse communities through participatory programming, outreach initiatives, and… |
| `condition-reporting` (`arts-culture/condition-reporting`) | Standardized methodology for documenting the physical state of artworks and cultural objects including terminology, photography, and… |
| `conservation-treatment` (`arts-culture/conservation-treatment`) | Protocol for assessing artwork condition, developing treatment proposals, executing interventions, and documenting conservation activities… |
| `cultural-impact-assessment` (`arts-culture/cultural-impact-assessment`) | Cultural impact assessment process for evaluating social, economic, and cultural effects of projects, programs, and policies on communities |
| `cultural-planning` (`arts-culture/cultural-planning`) | Cultural planning process for municipalities and regions - integrating arts and culture into urban development, placemaking, and community… |
| `curatorial-research` (`arts-culture/curatorial-research`) | Methodology for conducting art historical research, primary source analysis, provenance research, and scholarly interpretation to inform… |
| `donor-cultivation` (`arts-culture/donor-cultivation`) | Systematic approach to identifying, cultivating, soliciting, and stewarding individual donors including major gift strategies and planned… |
| `education-program-development` (`arts-culture/education-program-development`) | Methodology for designing and delivering educational programs for schools, families, and adult learners including curriculum development,… |
| `event-planning` (`arts-culture/event-planning`) | Comprehensive approach to planning cultural events including venue selection, vendor coordination, logistics management, risk assessment,… |
| `exhibition-development` (`arts-culture/exhibition-development`) | Comprehensive workflow for planning, organizing, and installing exhibitions including concept development, artwork selection, loan… |
| `grant-writing` (`arts-culture/grant-writing`) | Structured approach to developing funding proposals for foundations, government agencies, and corporations including prospect research,… |
| `loan-agreement` (`arts-culture/loan-agreement`) | Protocol for negotiating, documenting, and managing incoming and outgoing loans including condition reporting, insurance valuation,… |
| `marketing-campaign` (`arts-culture/marketing-campaign`) | Structured approach to developing and executing marketing strategies for exhibitions, performances, and cultural programs including… |
| `performance-production` (`arts-culture/performance-production`) | End-to-end workflow for producing concerts, theatrical productions, and live events including pre-production planning, creative… |
| `preventive-conservation` (`arts-culture/preventive-conservation`) | Systematic approach to collection preservation including environmental monitoring, integrated pest management, storage protocols, and… |
| `stage-management` (`arts-culture/stage-management`) | Protocol for coordinating rehearsals and performances including scheduling, communication, prompt book management, show calling, and… |
| `strategic-planning` (`arts-culture/strategic-planning`) | Framework for developing organizational vision, mission, goals, and implementation strategies for cultural institutions using balanced… |
| `technical-production` (`arts-culture/technical-production`) | Workflow for managing lighting, sound, set construction, and multimedia elements in performance and exhibition contexts |
| `visitor-experience-design` (`arts-culture/visitor-experience-design`) | Approach to creating engaging visitor journeys including interpretive planning, wayfinding, accessibility accommodations, and experience… |

## Skills (15)

Reusable capabilities under `skills/<name>/SKILL.md`, referenceable from a task as `skill: { name: '<name>' }`:

| Skill | Description |
|---|---|
| `accessibility-compliance` | Ensure cultural programs and facilities meet ADA requirements and universal design principles including accommodations, assistive… |
| `arts-advocacy-communication` | Craft persuasive advocacy messages, coordinate coalition building, and engage with policymakers to advance arts funding and cultural… |
| `audience-analytics` | Analyze visitor data, attendance patterns, and engagement metrics to inform programming decisions and measure organizational impact |
| `collection-documentation` | Create and maintain comprehensive collection records including cataloging, photography, condition documentation, and database management… |
| `conservation-assessment` | Assess condition of artworks and cultural objects, develop treatment proposals, and document conservation interventions following AIC… |
| `cultural-policy-analysis` | Analyze cultural policies, assess community cultural needs, and develop evidence-based recommendations for arts funding and cultural… |
| `curatorial-research` | Conduct art historical research, provenance investigation, and scholarly analysis to inform exhibitions, acquisitions, and publications… |
| `digital-engagement-strategy` | Develop digital content strategies including virtual exhibitions, online programming, social media campaigns, and digital collection access |
| `donor-relationship-management` | Cultivate and steward donor relationships including prospect research, personalized engagement strategies, gift acknowledgment, and impact… |
| `exhibition-design` | Plan and design exhibition layouts including spatial arrangement, object placement, lighting, graphics, and visitor flow optimization for… |
| `grant-proposal-writing` | Develop compelling funding proposals for foundations, government agencies, and corporations including narrative development, budget… |
| `interpretive-writing` | Create accessible interpretive content for diverse audiences including labels, wall text, catalog essays, educational materials, and… |
| `production-coordination` | Coordinate all aspects of live performance production including scheduling, technical requirements, artist contracts, venue logistics, and… |
| `risk-mitigation-planning` | Develop comprehensive risk management plans for collections and cultural venues including disaster preparedness, security protocols, and… |
| `stakeholder-facilitation` | Facilitate meetings, workshops, and community consultations with diverse stakeholders including artists, board members, funders, and… |

## Agents (10)

Persona definitions under `agents/<name>/AGENT.md`, referenceable from a task as `agent: { name: '<name>' }`:

| Agent | Description |
|---|---|
| `arts-administrator-agent` | Arts administration executive agent for nonprofit management, strategic planning, board governance, organizational development, financial… |
| `conservator-agent` | Conservation and preservation specialist agent for condition assessment, treatment planning, preventive conservation, environmental… |
| `cultural-policy-agent` | Cultural policy and planning specialist agent for policy analysis, cultural planning, impact assessment, community consultation, advocacy… |
| `curator-agent` | Curatorial specialist agent for art historical research, exhibition development, collection interpretation, scholarly writing, provenance… |
| `development-officer-agent` | Fundraising and development specialist agent for grant writing, donor cultivation, major gift solicitation, foundation relations,… |
| `education-outreach-agent` | Education and community engagement specialist agent for curriculum development, program design, community partnerships, accessibility… |
| `exhibition-designer-agent` | Exhibition design and installation specialist agent for spatial design, visitor experience, lighting design, graphic design, ADA… |
| `marketing-communications-agent` | Marketing and audience development specialist agent for campaign strategy, audience segmentation, digital marketing, brand management,… |
| `production-manager-agent` | Performance production manager agent for stage management, technical production, event coordination, artist relations, venue operations,… |
| `registrar-agent` | Museum registrar and collections manager agent for collection documentation, loan administration, insurance coordination, database… |

## Usage

Use this skill to route work into the `arts-culture` domain (visual/performing/media arts, cultural heritage, and arts administration): pick the relevant process, skill, or agent above, then either invoke the process directly via the babysitter CLI as shown, reference the skill/agent from a task definition, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
