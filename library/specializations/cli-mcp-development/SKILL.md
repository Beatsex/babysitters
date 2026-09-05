---
name: specialization-cli-mcp-development
description: "This specialization encompasses the design, development, and deployment of command-line interfaces and Model Context Protocol (MCP) implementations that enable AI-powered developer tools. It covers the full spectrum from simple shell scripts to complex interactive terminal applications and…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: cli-mcp-development
  process-count: 30
---

# specialization-cli-mcp-development

## Overview

This specialization encompasses the design, development, and deployment of command-line interfaces and Model Context Protocol (MCP) implementations that enable AI-powered developer tools. It covers the full spectrum from simple shell scripts to complex interactive terminal applications and sophisticated MCP servers that extend AI capabilities.

## Available Processes (30)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/cli-mcp-development/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `argument-parser-setup` (`specializations/cli-mcp-development/argument-parser-setup`) | Argument Parser Setup - Implement comprehensive argument parsing with validation, help generation, |
| `cli-application-bootstrap` (`specializations/cli-mcp-development/cli-application-bootstrap`) | CLI Application Bootstrap - Create a new CLI application with project structure, argument parsing, and basic commands |
| `cli-binary-distribution` (`specializations/cli-mcp-development/cli-binary-distribution`) | CLI Binary Distribution - Set up binary compilation and distribution for CLI tools |
| `cli-command-structure-design` (`specializations/cli-mcp-development/cli-command-structure-design`) | CLI Command Structure Design - Design and implement hierarchical command structure for complex CLI applications |
| `cli-documentation-generation` (`specializations/cli-mcp-development/cli-documentation-generation`) | CLI Documentation Generation - Implement automated documentation generation from CLI command definitions |
| `cli-output-formatting` (`specializations/cli-mcp-development/cli-output-formatting`) | CLI Output Formatting System - Implement flexible output formatting with support for multiple formats |
| `cli-unit-integration-testing` (`specializations/cli-mcp-development/cli-unit-integration-testing`) | CLI Unit and Integration Testing - Implement comprehensive testing strategy for CLI applications |
| `cli-update-mechanism` (`specializations/cli-mcp-development/cli-update-mechanism`) | CLI Update Mechanism - Implement self-update functionality for CLI tools |
| `configuration-management-system` (`specializations/cli-mcp-development/configuration-management-system`) | Configuration Management System - Implement hierarchical configuration loading |
| `cross-platform-cli-compatibility` (`specializations/cli-mcp-development/cross-platform-cli-compatibility`) | Cross-Platform CLI Compatibility - Ensure CLI tools work consistently across |
| `dashboard-monitoring-tui` (`specializations/cli-mcp-development/dashboard-monitoring-tui`) | Dashboard and Monitoring TUI - Build real-time dashboard for monitoring data in terminal with charts, |
| `error-handling-user-feedback` (`specializations/cli-mcp-development/error-handling-user-feedback`) | Error Handling and User Feedback - Implement comprehensive error handling with helpful messages, |
| `interactive-form-implementation` (`specializations/cli-mcp-development/interactive-form-implementation`) | Interactive Form Implementation - Create multi-field interactive forms for complex data entry in terminal |
| `interactive-prompt-system` (`specializations/cli-mcp-development/interactive-prompt-system`) | Interactive Prompt System - Implement interactive prompts for gathering user input when arguments are missing, |
| `mcp-client-implementation` (`specializations/cli-mcp-development/mcp-client-implementation`) | MCP Client Implementation - Build MCP client libraries for connecting to MCP servers |
| `mcp-resource-provider` (`specializations/cli-mcp-development/mcp-resource-provider`) | MCP Resource Provider - Implement MCP resource provider for exposing dynamic content to AI assistants |
| `mcp-server-bootstrap` (`specializations/cli-mcp-development/mcp-server-bootstrap`) | MCP Server Bootstrap - Create a new MCP server with transport configuration, capability declarations, |
| `mcp-server-monitoring-debugging` (`specializations/cli-mcp-development/mcp-server-monitoring-debugging`) | MCP Server Monitoring and Debugging - Implement observability, logging, tracing, |
| `mcp-server-registry-discovery` (`specializations/cli-mcp-development/mcp-server-registry-discovery`) | MCP Server Registry and Discovery - Implement server registration, discovery mechanisms, |
| `mcp-server-security-hardening` (`specializations/cli-mcp-development/mcp-server-security-hardening`) | MCP Server Security Hardening - Implement security measures for MCP servers including sandboxing, |
| `mcp-server-testing-suite` (`specializations/cli-mcp-development/mcp-server-testing-suite`) | MCP Server Testing Suite - Create testing infrastructure for MCP servers including unit tests, |
| `mcp-tool-documentation` (`specializations/cli-mcp-development/mcp-tool-documentation`) | MCP Tool Documentation - Generate comprehensive documentation for MCP tools including |
| `mcp-tool-implementation` (`specializations/cli-mcp-development/mcp-tool-implementation`) | MCP Tool Implementation - Design and implement a new MCP tool with JSON Schema validation, |
| `mcp-transport-layer` (`specializations/cli-mcp-development/mcp-transport-layer`) | MCP Transport Layer Implementation - Implement additional transport layers beyond stdio including HTTP/SSE |
| `package-manager-publishing` (`specializations/cli-mcp-development/package-manager-publishing`) | Package Manager Publishing - Implement publishing workflows for npm, PyPI, crates.io, |
| `plugin-architecture-implementation` (`specializations/cli-mcp-development/plugin-architecture-implementation`) | Plugin Architecture Implementation - Design and implement extensible plugin systems |
| `progress-status-indicators` (`specializations/cli-mcp-development/progress-status-indicators`) | Progress and Status Indicators - Implement progress bars, spinners, and status messages for long-running |
| `shell-completion-scripts` (`specializations/cli-mcp-development/shell-completion-scripts`) | Shell Completion Scripts - Implement tab completion for Bash, Zsh, Fish, and PowerShell |
| `shell-script-development` (`specializations/cli-mcp-development/shell-script-development`) | Shell Script Development - Build robust shell scripts with proper error handling, |
| `tui-application-framework` (`specializations/cli-mcp-development/tui-application-framework`) | TUI Application Framework Setup - Set up terminal user interface framework for interactive applications |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `cli-mcp-development` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
