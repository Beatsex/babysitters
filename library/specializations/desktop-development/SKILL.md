---
name: specialization-desktop-development
description: "Desktop product development specialization focuses on creating native and cross-platform desktop applications for Windows, macOS, and Linux operating systems. This discipline encompasses building high-performance, feature-rich applications that leverage native OS capabilities while providing…"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: desktop-development
  process-count: 24
---

# specialization-desktop-development

## Overview

Desktop product development specialization focuses on creating native and cross-platform desktop applications for Windows, macOS, and Linux operating systems. This discipline encompasses building high-performance, feature-rich applications that leverage native OS capabilities while providing excellent user experiences across different desktop environments.

## Available Processes (24)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/desktop-development/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `auto-update-system` (`specializations/desktop-development/auto-update-system`) | Auto-Update System Implementation - Implement automatic application updates using electron-updater |
| `code-signing-setup` (`specializations/desktop-development/code-signing-setup`) | Code Signing and Notarization Setup - Configure code signing for Windows (Authenticode), macOS |
| `cross-platform-app-init` (`specializations/desktop-development/cross-platform-app-init`) | Cross-Platform Desktop App Initialization - Set up new desktop application project with chosen framework |
| `cross-platform-testing` (`specializations/desktop-development/cross-platform-testing`) | Cross-Platform Testing Process - Establish testing strategy across Windows, macOS, and Linux; |
| `desktop-accessibility` (`specializations/desktop-development/desktop-accessibility`) | Desktop Accessibility Implementation - Implement comprehensive accessibility features including |
| `desktop-analytics` (`specializations/desktop-development/desktop-analytics`) | Desktop Analytics and Telemetry Integration - Implement privacy-respecting analytics and crash |
| `desktop-build-pipeline` (`specializations/desktop-development/desktop-build-pipeline`) | Desktop Build Pipeline Setup - Configure CI/CD pipeline for building desktop applications across multiple |
| `desktop-i18n` (`specializations/desktop-development/desktop-i18n`) | Desktop Internationalization (i18n) Implementation - Implement localization including string |
| `desktop-migration` (`specializations/desktop-development/desktop-migration`) | Desktop Application Migration Strategy - Plan and execute migration from legacy desktop frameworks |
| `desktop-ui-implementation` (`specializations/desktop-development/desktop-ui-implementation`) | Desktop UI Implementation Workflow - Design and implement desktop application user interface following |
| `desktop-ui-testing` (`specializations/desktop-development/desktop-ui-testing`) | Desktop UI Testing Workflow - Set up UI/component testing using frameworks like Testing Library, |
| `desktop-unit-testing` (`specializations/desktop-development/desktop-unit-testing`) | Desktop Unit Testing Setup - Configure unit testing for desktop applications using appropriate |
| `file-system-integration` (`specializations/desktop-development/file-system-integration`) | File System Integration Process - Implement file operations including file dialogs, file watching, |
| `incremental-feature-e2e-gate` (`specializations/desktop-development/incremental-feature-e2e-gate`) | Incremental Feature E2E Gate - Ensures E2E tests are updated when new routes, pages, or features |
| `inter-app-communication` (`specializations/desktop-development/inter-app-communication`) | Inter-Application Communication Setup - Implement IPC mechanisms including named pipes, sockets, |
| `linux-packaging` (`specializations/desktop-development/linux-packaging`) | Linux Distribution Packaging - Create distribution packages for Linux including .deb (Debian/Ubuntu), |
| `macos-features` (`specializations/desktop-development/macos-features`) | macOS-Specific Feature Implementation - Implement macOS-specific features including Touch Bar, |
| `mvvm-implementation` (`specializations/desktop-development/mvvm-implementation`) | MVVM Pattern Implementation for Desktop - Implement Model-View-ViewModel architecture pattern; |
| `native-notifications` (`specializations/desktop-development/native-notifications`) | Native Notifications Implementation - Implement platform-native notification systems for Windows |
| `performance-optimization` (`specializations/desktop-development/performance-optimization`) | Desktop Application Performance Optimization - Profile and optimize desktop app for memory usage, |
| `security-hardening` (`specializations/desktop-development/security-hardening`) | Desktop Security Hardening - Implement security measures including content security policy, |
| `system-services-integration` (`specializations/desktop-development/system-services-integration`) | System Services Integration - Integrate with OS-level services including clipboard, global shortcuts, |
| `system-tray-integration` (`specializations/desktop-development/system-tray-integration`) | System Tray and Menu Bar Integration - Implement persistent system tray (Windows/Linux) or menu bar |
| `windows-features` (`specializations/desktop-development/windows-features`) | Windows-Specific Feature Implementation - Implement Windows-specific features including jump lists, |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `desktop-development` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
