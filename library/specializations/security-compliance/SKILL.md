---
name: specialization-security-compliance
description: "Security, Compliance, and Risk Management is a critical specialization focused on protecting systems, data, and users from threats while ensuring adherence to regulatory requirements and industry standards. This specialization encompasses the entire lifecycle of secure software development, from…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: security-compliance
  process-count: 27
---

# specialization-security-compliance

## Overview

Security, Compliance, and Risk Management is a critical specialization focused on protecting systems, data, and users from threats while ensuring adherence to regulatory requirements and industry standards. This specialization encompasses the entire lifecycle of secure software development, from threat modeling and secure design to vulnerability management, incident response, and continuous compliance monitoring.

## Available Processes (27)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/security-compliance/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `business-continuity` (`specializations/security-compliance/business-continuity`) | Business Continuity Planning - Comprehensive framework for ensuring organizational resilience through |
| `codebase-security-audit` (`specializations/security-compliance/codebase-security-audit`) | Comprehensive Codebase Security Audit - Multi-domain static security assessment with |
| `container-security` (`security-compliance/container-security`) | Container Security Scanning - Comprehensive container security framework covering image scanning, |
| `dast-process` (`security-compliance/dast-process`) | Dynamic Application Security Testing (DAST) Process - Comprehensive black-box security testing for running applications covering OWASP… |
| `data-classification` (`specializations/security-compliance/data-classification`) | Data Classification and Handling Framework - Comprehensive data classification system covering |
| `disaster-recovery-testing` (`specializations/security-compliance/disaster-recovery-testing`) | Disaster Recovery Testing - Comprehensive framework for planning, executing, and validating disaster recovery |
| `encryption-standards` (`specializations/security-compliance/encryption-standards`) | Encryption Standards Implementation - Comprehensive encryption framework covering encryption at rest |
| `gdpr-compliance` (`specializations/security-compliance/gdpr-compliance`) | GDPR Compliance Assessment Process - Comprehensive evaluation of General Data Protection Regulation |
| `hipaa-compliance` (`security-compliance/hipaa-compliance`) | HIPAA Compliance Framework - Comprehensive framework for implementing and validating HIPAA compliance |
| `iac-security-review` (`specializations/security-compliance/iac-security-review`) | Infrastructure as Code Security Review - Comprehensive security analysis of IaC configurations including |
| `iam-access-control` (`specializations/security-compliance/iam-access-control`) | Access Control and IAM Review - Comprehensive identity and access management security assessment covering |
| `incident-response` (`specializations/security-compliance/incident-response`) | Security Incident Response Plan - Comprehensive framework for handling security incidents including classification, |
| `iso27001-implementation` (`specializations/security-compliance/iso27001-implementation`) | ISO 27001 Implementation Process - Comprehensive Information Security Management System (ISMS) |
| `nation-state-trojan-detection` (`specializations/security-compliance/nation-state-trojan-detection`) | LLM-Powered Nation-State Trojan Detection — Semantic code analysis engine that detects |
| `pci-dss-compliance` (`specializations/security-compliance/pci-dss-compliance`) | PCI DSS Compliance Assessment - Comprehensive Payment Card Industry Data Security Standard compliance |
| `penetration-testing` (`security-compliance/penetration-testing`) | Penetration Testing Program - Comprehensive ethical hacking and security assessment framework following |
| `sast-pipeline` (`specializations/security-compliance/sast-pipeline`) | SAST Pipeline Integration - Automated static application security testing integration for CI/CD pipelines. |
| `sca-dependency-management` (`specializations/security-compliance/sca-dependency-management`) | Software Composition Analysis (SCA) and Dependency Management - Comprehensive SCA framework covering |
| `secrets-management` (`specializations/security-compliance/secrets-management`) | Secrets Management Implementation - Enterprise-grade secrets management framework covering secure |
| `security-attestation-workflow` (`specializations/security-compliance/security-attestation-workflow`) | Security certification and attestation end-to-end workflow (SOC 2 / ISO 27001 |
| `security-logging-monitoring` (`security-compliance/security-logging-monitoring`) | Security Logging and Monitoring - Comprehensive SIEM implementation and security log management framework covering |
| `security-policies` (`specializations/security-compliance/security-policies`) | Security Policy Documentation Process - Comprehensive security policy development, documentation, and |
| `security-training` (`security-compliance/security-training`) | Security Awareness Training Program - Comprehensive security training framework covering training content development, |
| `soc2-compliance` (`specializations/security-compliance/soc2-compliance`) | SOC 2 Compliance Preparation Process - Comprehensive SOC 2 audit readiness process covering |
| `stride-threat-modeling` (`specializations/security-compliance/stride-threat-modeling`) | STRIDE Threat Modeling Process - Systematic security threat analysis using Microsoft's STRIDE |
| `third-party-risk` (`specializations/security-compliance/third-party-risk`) | Third-Party Risk Assessment - Comprehensive security due diligence and ongoing monitoring of third-party |
| `vulnerability-management` (`specializations/security-compliance/vulnerability-management`) | Vulnerability Management Lifecycle - Comprehensive end-to-end vulnerability management process covering |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `security-compliance` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
