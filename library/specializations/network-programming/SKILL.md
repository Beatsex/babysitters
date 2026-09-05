---
name: specialization-network-programming
description: "This specialization encompasses the technical disciplines required to design, implement, and maintain network-based software systems:"
allowed-tools: Read Glob Grep Bash
metadata:
  author: babysitter-sdk
  version: "1.0.0"
  category: network-programming
  process-count: 30
---

# specialization-network-programming

## Overview

This specialization encompasses the technical disciplines required to design, implement, and maintain network-based software systems:

## Available Processes (30)

Each process below is a babysitter SDK process definition. Run one with:

```bash
babysitter run:create --process-id <processId> --entry library/specializations/network-programming/<file>.js#process --inputs <inputs.json> --json
```

| Process | Description |
|---|---|
| `binary-protocol-parser` (`specializations/network-programming/binary-protocol-parser`) | Binary Protocol Parser Development - Design and implement a robust binary protocol parser with framing, |
| `certificate-management` (`specializations/network-programming/certificate-management`) | Certificate Lifecycle Management System - Build a system for managing TLS certificate lifecycle including |
| `connection-pool` (`specializations/network-programming/connection-pool`) | Connection Pool Implementation - Build a connection pool for efficient client-side connection reuse |
| `custom-protocol-design` (`specializations/network-programming/custom-protocol-design`) | Custom Protocol Design and Implementation - Design and implement a complete custom network protocol |
| `event-driven-socket-handler` (`specializations/network-programming/event-driven-socket-handler`) | Event-Driven Socket Handler - Implement a high-performance event-driven socket handler using platform-specific |
| `health-check-system` (`specializations/network-programming/health-check-system`) | Health Check System - Build a comprehensive health checking framework with multiple probe types, |
| `http-client-library` (`specializations/network-programming/http-client-library`) | HTTP Client Library Development - Build a reusable HTTP client library with connection pooling, |
| `http-proxy-server` (`specializations/network-programming/http-proxy-server`) | HTTP Proxy Server - Build a full-featured HTTP proxy with forward/reverse modes, caching, |
| `http-server` (`specializations/network-programming/http-server`) | HTTP/1.1 Server Implementation - Build an HTTP/1.1 compliant server from scratch with request parsing, |
| `http2-server` (`specializations/network-programming/http2-server`) | HTTP/2 Server Implementation - Build an HTTP/2 compliant server with binary framing, multiplexed streams, |
| `layer4-load-balancer` (`specializations/network-programming/layer4-load-balancer`) | Layer 4 Load Balancer Implementation - Build a TCP/UDP load balancer with connection tracking, |
| `layer7-load-balancer` (`specializations/network-programming/layer7-load-balancer`) | Layer 7 Load Balancer Implementation - Build an HTTP-aware load balancer with URL-based routing, |
| `load-testing-tool` (`specializations/network-programming/load-testing-tool`) | Load Testing Tool - Build a high-performance load testing tool with concurrent connections, |
| `message-framing` (`specializations/network-programming/message-framing`) | Message Framing Implementation - Implement message framing strategies for stream-based protocols |
| `mtls-implementation` (`specializations/network-programming/mtls-implementation`) | Mutual TLS (mTLS) Implementation - Implement mutual TLS authentication where both client and server |
| `network-testing-framework` (`specializations/network-programming/network-testing-framework`) | Network Testing Framework - Build a comprehensive network testing library with mock servers, |
| `network-traffic-analyzer` (`specializations/network-programming/network-traffic-analyzer`) | Network Traffic Analyzer - Build a comprehensive traffic analysis tool with flow tracking, |
| `packet-capture-analysis` (`specializations/network-programming/packet-capture-analysis`) | Packet Capture and Analysis Tool - Build a network packet capture tool using libpcap/npcap with |
| `protocol-dissector` (`specializations/network-programming/protocol-dissector`) | Protocol Dissector Development - Build a Wireshark-style protocol dissector that decodes network |
| `protocol-fuzzer` (`specializations/network-programming/protocol-fuzzer`) | Protocol Fuzzer - Build a network protocol fuzzing tool with mutation strategies, |
| `protocol-state-machine` (`specializations/network-programming/protocol-state-machine`) | Protocol State Machine Implementation - Build a formal state machine for protocol connection lifecycle |
| `realtime-messaging-system` (`specializations/network-programming/realtime-messaging-system`) | Real-Time Messaging System - Build a scalable real-time messaging system with pub/sub, presence |
| `rest-api-client-generator` (`specializations/network-programming/rest-api-client-generator`) | REST API Client Generator - Build a code generator that creates type-safe API clients from OpenAPI/Swagger |
| `socks5-proxy` (`specializations/network-programming/socks5-proxy`) | SOCKS5 Proxy Server - Build a SOCKS5 proxy server with authentication, UDP support, |
| `tcp-socket-server` (`specializations/network-programming/tcp-socket-server`) | TCP Socket Server Implementation - Design and implement a high-performance TCP server with proper |
| `tls-integration` (`specializations/network-programming/tls-integration`) | TLS Integration for Socket Server - Add TLS/SSL encryption to an existing socket server with proper |
| `transparent-proxy` (`specializations/network-programming/transparent-proxy`) | Transparent Proxy - Build a transparent/interception proxy using iptables/pf/WFP with |
| `udp-socket-server` (`specializations/network-programming/udp-socket-server`) | UDP Socket Server Implementation - Build a UDP server for datagram-based communication with packet handling, |
| `websocket-client` (`specializations/network-programming/websocket-client`) | WebSocket Client Library - Build a robust WebSocket client with automatic reconnection, heartbeat, |
| `websocket-server` (`specializations/network-programming/websocket-server`) | WebSocket Server Implementation - Build a WebSocket server compliant with RFC 6455 with handshake, |

## Subcategories

- `agents/`
- `skills/`

## Usage

Use this skill to route work into the `network-programming` specialization: identify the relevant process (or subcategory) above, then either invoke it directly via the babysitter CLI as shown, or delegate to it through the `babysit` skill's run lifecycle so breakpoints, artifacts, and run history are tracked consistently.
