---
name: specialization-devops-sre-platform
description: "This specialization encompasses three interconnected disciplines that focus on the intersection of software development, operations, and reliability:"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: devops-sre-platform
  process-count: 29
---

# specialization-devops-sre-platform

## Overview

This specialization encompasses three interconnected disciplines that focus on the intersection of software development, operations, and reliability:

## Available Processes (29)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/devops-sre-platform/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `auto-scaling` (`specializations/devops-sre-platform/auto-scaling`) | Auto-Scaling Configuration - Comprehensive workflow for implementing production-grade auto-scaling |
| `aws-systems-cost-reduction` (`contrib/devops/aws-systems-cost-reduction`) | End-to-end AWS cost-reduction workflow. All tasks are |
| `aws-systems-discovery` (`contrib/devops/aws-systems-discovery`) | End-to-end AWS account discovery, system attribution, EKS |
| `azure-systems-cost-reduction` (`contrib/devops/azure-systems-cost-reduction`) | Azure cost-reduction workflow. Bootstraps az CLI + auth + sub |
| `azure-systems-discovery` (`contrib/devops/azure-systems-discovery`) | End-to-end Azure subscription discovery, system attribution, AKS |
| `backup-restore-automation` (`specializations/devops-sre-platform/backup-restore-automation`) | Backup and Restore Automation - Comprehensive automated backup and disaster recovery framework covering |
| `cicd-pipeline-setup` (`specializations/devops-sre-platform/cicd-pipeline-setup`) | CI/CD Pipeline Setup - Design and implement a complete CI/CD pipeline from code commit to production deployment, |
| `cloud-chaos-monkey` (`cloud-chaos-monkey`) | Cloud-agnostic chaos monkey process for any cloud provider. |
| `cloud-ha-architecture-plan` (`cloud-ha-architecture-plan`) | Cloud-agnostic high-availability architecture planning process. |
| `container-image-management` (`specializations/devops-sre-platform/container-image-management`) | Container Image Build and Registry Management - Comprehensive container image lifecycle management |
| `cost-optimization` (`specializations/devops-sre-platform/cost-optimization`) | Cost Optimization and FinOps Process - Comprehensive cloud cost optimization framework implementing |
| `disaster-recovery-plan` (`specializations/devops-sre-platform/disaster-recovery-plan`) | Disaster Recovery Plan Creation - Comprehensive process for developing and implementing disaster recovery |
| `error-budget-management` (`specializations/devops-sre-platform/error-budget-management`) | Error Budget Management Process - Comprehensive SLO-based reliability engineering framework covering |
| `gcp-systems-cost-reduction` (`contrib/devops/gcp-systems-cost-reduction`) | End-to-end GCP cost-reduction. All tasks are `kind: 'agent'`; |
| `gcp-systems-discovery` (`contrib/devops/gcp-systems-discovery`) | End-to-end GCP project/organization discovery, system attribution, |
| `iac-implementation` (`specializations/devops-sre-platform/iac-implementation`) | Infrastructure as Code (IaC) Implementation - Complete end-to-end IaC development process |
| `iac-testing` (`specializations/devops-sre-platform/iac-testing`) | IaC Testing and Validation - Comprehensive Infrastructure as Code testing framework covering |
| `idp-setup` (`specializations/devops-sre-platform/idp-setup`) | Internal Developer Platform (IDP) Setup - Complete workflow for building a self-service |
| `incident-response` (`specializations/devops-sre-platform/incident-response`) | Incident Response Process - Structured incident management framework covering detection, triage, investigation, |
| `kubernetes-setup` (`specializations/devops-sre-platform/kubernetes-setup`) | Kubernetes Cluster Setup and Management - Complete workflow for setting up a production-ready |
| `log-aggregation` (`specializations/devops-sre-platform/log-aggregation`) | Log Aggregation and Analysis Pipeline - Comprehensive log collection, aggregation, parsing, |
| `monitoring-setup` (`specializations/devops-sre-platform/monitoring-setup`) | Monitoring and Observability Setup - Comprehensive process for implementing production-grade |
| `oncall-setup` (`devops-sre-platform/oncall-setup`) | Implement on-call rotation and escalation policies for incident management, including schedule design, tooling setup, and team training |
| `pipeline-optimization` (`specializations/devops-sre-platform/pipeline-optimization`) | Pipeline Optimization and Parallelization - Analyze and optimize existing CI/CD pipelines for speed, efficiency, |
| `post-deploy-visual-check` (`specializations/devops-sre-platform/post-deploy-visual-check`) | Post-deploy visual check — after a production deploy, spin up |
| `secrets-management` (`specializations/devops-sre-platform/secrets-management`) | Secrets Management Implementation - Comprehensive framework for implementing enterprise-grade |
| `security-scanning` (`specializations/devops-sre-platform/security-scanning`) | Security Scanning and Compliance Automation - Comprehensive automated security scanning framework covering |
| `service-mesh` (`specializations/devops-sre-platform/service-mesh`) | Service Mesh Implementation - Complete workflow for implementing a production-ready service mesh |
| `slo-sli-tracking` (`specializations/devops-sre-platform/slo-sli-tracking`) | SLO/SLI Definition and Tracking - Comprehensive process for defining Service Level Objectives (SLOs), |

## Subcategories

- `agents/`
- `examples/`
- `skills/`

## Usage

Use this skill to route work into the `devops-sre-platform` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
