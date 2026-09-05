---
name: specialization-qa-testing-automation
description: "QA, Testing, and Test Automation is a critical specialization focused on ensuring software quality through systematic testing methodologies, automation frameworks, and quality assurance practices. This discipline encompasses manual testing, automated test development, continuous testing in CI/CD…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: qa-testing-automation
  process-count: 23
---

# specialization-qa-testing-automation

## Overview

QA, Testing, and Test Automation is a critical specialization focused on ensuring software quality through systematic testing methodologies, automation frameworks, and quality assurance practices. This discipline encompasses manual testing, automated test development, continuous testing in CI/CD pipelines, and quality metrics tracking.

## Available Processes (23)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/qa-testing-automation/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `accessibility-testing` (`specializations/qa-testing-automation/accessibility-testing`) | Accessibility Testing Automation - Implement automated accessibility testing to ensure WCAG 2.1/2.2 compliance, |
| `api-testing` (`specializations/qa-testing-automation/api-testing`) | API Test Automation Suite - Comprehensive API test automation covering REST/GraphQL endpoints, |
| `automation-framework` (`specializations/qa-testing-automation/automation-framework`) | Test Automation Framework Setup - Establish a robust, maintainable test automation framework with |
| `continuous-testing` (`specializations/qa-testing-automation/continuous-testing`) | Continuous Testing Pipeline - Implement automated continuous testing across the entire software delivery lifecycle, |
| `contract-testing` (`specializations/qa-testing-automation/contract-testing`) | Contract Testing Implementation - Consumer-driven contract testing to enable independent service |
| `cross-browser-testing` (`specializations/qa-testing-automation/cross-browser-testing`) | Cross-Browser/Device Testing - Comprehensive cross-browser and cross-device testing to ensure |
| `deployed-route-verify-gate` (`specializations/qa-testing-automation/deployed-route-verify-gate`) | (no description) |
| `diagnostic-first-phase` (`specializations/qa-testing-automation/diagnostic-first-phase`) | Reusable defineTask snippet for the diagnostic-first phase in |
| `e2e-test-suite` (`specializations/qa-testing-automation/e2e-test-suite`) | End-to-End Test Suite Development - Comprehensive E2E test automation for critical user journeys, |
| `environment-management` (`specializations/qa-testing-automation/environment-management`) | Test Environment Management - Establish robust test environment management with |
| `exploratory-testing` (`specializations/qa-testing-automation/exploratory-testing`) | Exploratory Testing Session Framework - Establish structured exploratory testing with session-based testing, |
| `flakiness-elimination` (`specializations/qa-testing-automation/flakiness-elimination`) | Test Flakiness Elimination - Systematically identify, analyze, and eliminate flaky tests to improve |
| `metrics-dashboard` (`specializations/qa-testing-automation/metrics-dashboard`) | Test Automation Metrics Dashboard - Build comprehensive quality metrics dashboard for tracking test execution, |
| `mobile-testing` (`specializations/qa-testing-automation/mobile-testing`) | Mobile App Testing Automation - Comprehensive mobile testing automation for iOS and Android using Appium, |
| `mutation-testing` (`qa-testing-automation/mutation-testing`) | Implement mutation testing to validate quality and effectiveness of unit tests by introducing code mutations and verifying test detection |
| `performance-testing` (`specializations/qa-testing-automation/performance-testing`) | Performance Testing Implementation - Comprehensive performance testing strategy covering load testing, |
| `quality-gates` (`qa-testing-automation/quality-gates`) | Comprehensive quality gate implementation process with gate definition, enforcement, automation, monitoring, and continuous improvement |
| `release-quality-assurance-workflow` (`qa-testing-automation/release-quality-assurance-workflow`) | Flagship release-quality end-to-end workflow: risk-based test strategy -> |
| `security-testing` (`specializations/qa-testing-automation/security-testing`) | Security Testing Automation - Comprehensive security testing framework covering OWASP Top 10, |
| `shift-left-testing` (`qa-testing-automation/shift-left-testing`) | Implement shift-left testing practices to move testing activities earlier in the development lifecycle |
| `test-data-management` (`qa-testing-automation/test-data-management`) | Test Data Management System - Comprehensive solution for test data generation, storage, versioning, |
| `test-strategy` (`qa-testing-automation/test-strategy`) | Comprehensive test strategy development process with requirements analysis, risk assessment, test pyramid definition, automation strategy,… |
| `visual-regression` (`specializations/qa-testing-automation/visual-regression`) | Visual Regression Testing Setup - Comprehensive visual regression testing framework implementing |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `qa-testing-automation` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
