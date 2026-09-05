---
name: specialization-data-science-ml
description: "The Data Science and Machine Learning (DS/ML) specialization encompasses the complete lifecycle of developing, deploying, and maintaining machine learning systems in production environments. This specialization combines statistical analysis, algorithm development, software engineering, and…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: data-science-ml
  process-count: 18
---

# specialization-data-science-ml

## Overview

The Data Science and Machine Learning (DS/ML) specialization encompasses the complete lifecycle of developing, deploying, and maintaining machine learning systems in production environments. This specialization combines statistical analysis, algorithm development, software engineering, and operational practices to build intelligent systems that learn from data and make predictions or decisions.

## Available Processes (18)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/data-science-ml/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `ab-testing-ml` (`specializations/data-science-ml/ab-testing-ml`) | A/B Testing Framework for ML Models - Comprehensive framework for designing, executing, and analyzing |
| `automl-pipeline` (`specializations/data-science-ml/automl-pipeline`) | AutoML Pipeline Orchestration - Automated machine learning workflows with algorithm selection, |
| `data-collection-validation` (`data-science-ml/data-collection-validation`) | Orchestrate data ingestion from multiple sources with validation, quality checks, and versioning |
| `distributed-training` (`specializations/data-science-ml/distributed-training`) | Distributed Training Orchestration - Design and execute distributed training strategies for large-scale ML models |
| `eda-pipeline` (`data-science-ml/eda-pipeline`) | Automated Exploratory Data Analysis (EDA) pipeline with quality gates |
| `experiment-planning` (`specializations/data-science-ml/experiment-planning`) | Experiment Planning and Hypothesis Testing - Design ML experiments with clear hypotheses, |
| `feature-engineering` (`data-science-ml/feature-engineering`) | Feature engineering design and implementation with quality gates and validation |
| `feature-store` (`specializations/data-science-ml/feature-store`) | Feature Store Implementation and Management - Design, implement, and operationalize a feature store |
| `ml-architecture-design` (`specializations/data-science-ml/ml-architecture-design`) | ML Architecture Design and Model Selection - Design system architecture for ML pipelines, |
| `ml-integration-testing` (`specializations/data-science-ml/ml-integration-testing`) | ML System Integration Testing - Validate end-to-end ML pipeline integration across data ingestion, |
| `ml-observability` (`specializations/data-science-ml/ml-observability`) | ML System Observability and Incident Response - Comprehensive monitoring, anomaly detection, |
| `ml-project-scoping` (`specializations/data-science-ml/ml-project-scoping`) | ML Project Scoping and Requirements Analysis - Define business objectives, success metrics, |
| `model-deployment-canary` (`specializations/data-science-ml/model-deployment-canary`) | Model Deployment Pipeline with Canary Release - Progressive rollout strategy with automated |
| `model-evaluation` (`specializations/data-science-ml/model-evaluation`) | Model Evaluation and Validation Framework - Comprehensive model assessment across multiple dimensions |
| `model-interpretability` (`specializations/data-science-ml/model-interpretability`) | Model Interpretability and Explainability Analysis - Comprehensive model interpretation pipeline with |
| `model-monitoring-drift` (`specializations/data-science-ml/model-monitoring-drift`) | Model Performance Monitoring and Drift Detection - Continuously monitor prediction accuracy, |
| `model-retraining` (`data-science-ml/model-retraining`) | ML Model Retraining Pipeline - Detect model staleness, automatically retrain on updated data, |
| `model-training-pipeline` (`specializations/data-science-ml/model-training-pipeline`) | Model Training Pipeline with Experiment Tracking - Execute model training with hyperparameter tuning, |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `data-science-ml` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
