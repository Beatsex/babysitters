---
name: specialization-data-engineering-analytics
description: "The Data Engineering, Analytics, and BI specialization encompasses the end-to-end lifecycle of transforming raw data into actionable insights. This specialization bridges the gap between data collection and business decision-making, combining technical infrastructure (data engineering), analytical…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: data-engineering-analytics
  process-count: 19
---

# specialization-data-engineering-analytics

## Overview

The Data Engineering, Analytics, and BI specialization encompasses the end-to-end lifecycle of transforming raw data into actionable insights. This specialization bridges the gap between data collection and business decision-making, combining technical infrastructure (data engineering), analytical modeling (analytics engineering), and visualization (business intelligence).

## Available Processes (19)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/data-engineering-analytics/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `ab-testing-pipeline` (`specializations/data-engineering-analytics/ab-testing-pipeline`) | A/B Testing Pipeline for Data Engineering - Build end-to-end A/B testing data pipeline with experiment |
| `bi-dashboard` (`data-engineering-analytics/bi-dashboard`) | Comprehensive BI Dashboard Development process covering requirements gathering, data modeling, visualization design, |
| `data-catalog` (`data-engineering-analytics/data-catalog`) | Comprehensive data catalog setup covering metadata management, platform selection (DataHub/Amundsen/Alation), data discovery, lineage… |
| `data-lineage` (`data-engineering-analytics/data-lineage`) | Implement comprehensive data lineage mapping with automated extraction (OpenLineage/SQLLineage), graph visualization, impact analysis, and… |
| `data-product-lifecycle-workflow` (`specializations/data-engineering-analytics/data-product-lifecycle-workflow`) | Flagship data-product lifecycle: requirement + data-contract definition -> |
| `data-quality-framework` (`data-engineering-analytics/data-quality-framework`) | Implement comprehensive data quality framework with dimensions, validation rules, monitoring, alerting, anomaly detection, and data… |
| `data-warehouse-setup` (`data-engineering-analytics/data-warehouse-setup`) | Comprehensive data warehouse setup covering platform selection, architecture design, security, optimization, and cost management |
| `dbt-model-development` (`specializations/data-engineering-analytics/dbt-model-development`) | dbt Model Development - Guide the complete development lifecycle of dbt models from staging through intermediate to marts layers, |
| `dbt-project-setup` (`specializations/data-engineering-analytics/dbt-project-setup`) | dbt Project Setup - Initialize and configure a complete dbt (data build tool) project with proper folder structure, |
| `dimensional-model` (`data-engineering-analytics/dimensional-model`) | Dimensional Model Design - Design comprehensive dimensional data warehouse models including |
| `etl-elt-pipeline` (`specializations/data-engineering-analytics/etl-elt-pipeline`) | ETL/ELT Pipeline Setup - Design and implement a comprehensive data pipeline from source to destination, |
| `feature-store` (`specializations/data-engineering-analytics/feature-store`) | Feature Store Setup for Data Engineering - Design and implement production-ready feature store |
| `incremental-model` (`specializations/data-engineering-analytics/incremental-model`) | Incremental Model Setup - Design and implement incremental models for efficient large-scale data processing, |
| `metrics-layer` (`specializations/data-engineering-analytics/metrics-layer`) | Metrics Layer Implementation - Comprehensive process for designing and implementing a semantic metrics layer |
| `obt-creation` (`data-engineering-analytics/obt-creation`) | One Big Table (OBT) Creation - Design and implement denormalized One Big Table (OBT) structures |
| `pipeline-migration` (`specializations/data-engineering-analytics/pipeline-migration`) | Data Pipeline Migration - Comprehensive workflow for migrating data pipelines with |
| `query-optimization` (`specializations/data-engineering-analytics/query-optimization`) | Query Performance Optimization - Comprehensive query performance analysis and optimization covering profiling, |
| `scd-implementation` (`specializations/data-engineering-analytics/scd-implementation`) | Slowly Changing Dimension (SCD) Implementation - Implement Type 2 SCD patterns for historical tracking in data warehouses, |
| `streaming-pipeline` (`specializations/data-engineering-analytics/streaming-pipeline`) | Streaming Data Pipeline Setup - Complete workflow for designing and implementing |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `data-engineering-analytics` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
