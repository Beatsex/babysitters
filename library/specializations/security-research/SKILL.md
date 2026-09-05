---
name: specialization-security-research
description: "Security Research and Vulnerability Analysis is a specialized discipline focused on discovering, analyzing, and responsibly reporting security vulnerabilities in software, hardware, and systems. This specialization encompasses the full spectrum of offensive security techniques used for defensive…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: security-research
  process-count: 32
---

# specialization-security-research

## Overview

Security Research and Vulnerability Analysis is a specialized discipline focused on discovering, analyzing, and responsibly reporting security vulnerabilities in software, hardware, and systems. This specialization encompasses the full spectrum of offensive security techniques used for defensive purposes, including vulnerability detection, reverse engineering, exploit development, penetration testing, and bug bounty participation.

## Available Processes (32)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/security-research/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `ai-ml-security-research` (`specializations/security-research/ai-ml-security-research`) | Security research for AI/ML systems including adversarial attacks, model extraction, |
| `api-security-research` (`specializations/security-research/api-security-research`) | Security research focused on REST, GraphQL, and gRPC APIs covering authentication, |
| `binary-reverse-engineering` (`specializations/security-research/binary-reverse-engineering`) | Systematic analysis of compiled binaries without source code access. Covers static disassembly, |
| `bug-bounty-workflow` (`specializations/security-research/bug-bounty-workflow`) | End-to-end workflow for participating in bug bounty programs from scope review through |
| `capture-the-flag-challenges` (`specializations/security-research/capture-the-flag-challenges`) | Creation of Capture The Flag (CTF) challenges for security training and competitions. |
| `cloud-security-research` (`specializations/security-research/cloud-security-research`) | Security research for cloud infrastructure and services covering AWS, Azure, GCP |
| `container-security-research` (`specializations/security-research/container-security-research`) | Security research for containerized environments including Docker and Kubernetes. |
| `dynamic-analysis-runtime-testing` (`specializations/security-research/dynamic-analysis-runtime-testing`) | Security testing of running applications through debugging, instrumentation, and interactive |
| `exploit-development` (`specializations/security-research/exploit-development`) | Development of proof-of-concept exploits to demonstrate vulnerability impact and validate |
| `firmware-analysis` (`specializations/security-research/firmware-analysis`) | Security analysis of embedded device firmware including extraction, file system analysis, |
| `fuzzing-campaign` (`specializations/security-research/fuzzing-campaign`) | Automated vulnerability discovery through coverage-guided fuzzing. Includes target preparation, |
| `hardware-security-research` (`specializations/security-research/hardware-security-research`) | Security research for hardware systems including side-channel attacks, fault injection, |
| `malware-analysis` (`specializations/security-research/malware-analysis`) | Systematic analysis of malicious software to understand capabilities, behavior, indicators |
| `mobile-app-security-research` (`specializations/security-research/mobile-app-security-research`) | Security research for Android and iOS applications including static analysis, dynamic |
| `network-penetration-testing` (`specializations/security-research/network-penetration-testing`) | Authorized security assessment of network infrastructure including reconnaissance, |
| `protocol-reverse-engineering` (`specializations/security-research/protocol-reverse-engineering`) | Analysis of network protocols and communication formats to understand message structures, |
| `purple-team-exercise` (`specializations/security-research/purple-team-exercise`) | Collaborative security exercise combining red team attack simulation with blue team |
| `red-team-operations` (`specializations/security-research/red-team-operations`) | Full-scope adversarial simulation mimicking real threat actors to test organizational |
| `responsible-disclosure` (`specializations/security-research/responsible-disclosure`) | Managed process for ethical vulnerability disclosure to vendors with proper timeline |
| `security-advisory-writing` (`specializations/security-research/security-advisory-writing`) | Creation of professional security advisories and vulnerability disclosures following |
| `security-research-lab-setup` (`specializations/security-research/security-research-lab-setup`) | Setup and configuration of isolated security research environments including virtual |
| `security-research-publication` (`specializations/security-research/security-research-publication`) | Process for conducting and publishing security research including methodology |
| `security-tool-development` (`specializations/security-research/security-tool-development`) | Development of custom security tools including scanners, exploit frameworks, detection |
| `shellcode-development` (`specializations/security-research/shellcode-development`) | Creation of position-independent payload code for exploit delivery. Includes shellcode |
| `smart-contract-auditing` (`specializations/security-research/smart-contract-auditing`) | Security audit of blockchain smart contracts on Ethereum, Solana, and other platforms. |
| `static-code-analysis` (`specializations/security-research/static-code-analysis`) | Manual and automated source code analysis to identify security vulnerabilities including |
| `supply-chain-security` (`specializations/security-research/supply-chain-security`) | Analysis of software supply chain security including dependency analysis, build system |
| `threat-intelligence-research` (`specializations/security-research/threat-intelligence-research`) | Collection and analysis of threat intelligence including APT tracking, malware campaigns, |
| `variant-analysis` (`specializations/security-research/variant-analysis`) | Systematic search for similar vulnerabilities across a codebase or related projects after |
| `vulnerability-research-workflow` (`specializations/security-research/vulnerability-research-workflow`) | Comprehensive process for systematic vulnerability discovery in target applications or systems. |
| `vulnerability-root-cause-analysis` (`specializations/security-research/vulnerability-root-cause-analysis`) | Deep technical analysis to understand the root cause of discovered vulnerabilities, |
| `web-app-vuln-research` (`specializations/security-research/web-app-vuln-research`) | Comprehensive web application security research covering OWASP Top 10, modern web |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `security-research` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
