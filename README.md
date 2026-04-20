# Artillery (artillery)
Artillery is an open source load testing and performance testing platform for APIs, microservices, and web applications. Built with Node.js and available as an npm package, Artillery supports HTTP/1, HTTP/2, WebSocket, Socket.IO, gRPC, and custom protocols through plugins. It includes a YAML-based test scenario definition language, a plugin ecosystem for extending functionality, and Artillery Cloud for distributed load testing, CI/CD integration, and centralized reporting. Artillery is used by developers, QA engineers, and SREs to run load tests, performance benchmarks, Playwright-based synthetic monitoring, and end-to-end tests at scale. The project is licensed under MPL-2.0 and maintained by Artilleryio.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/artillery/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Load Testing, Performance Testing, Open Source, Testing, DevOps, Node.js

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-04-19

## APIs

### Artillery Cloud API
Artillery Cloud provides a hosted platform for running distributed load tests at scale, storing test results, team collaboration, and integrating with CI/CD pipelines. The Artillery Cloud API enables programmatic triggering of test runs, retrieval of test results, and management of test configurations.

**Human URL:** [https://www.artillery.io/docs/reference/cli/run-test](https://www.artillery.io/docs/reference/cli/run-test)

#### Tags:

 - Load Testing, Cloud, CI/CD, Performance

#### Properties

- [Documentation](https://www.artillery.io/docs/reference/cli/run-test)
- [GettingStarted](https://www.artillery.io/docs/get-started/get-artillery)

## Common Properties

- [Artillery Website](https://www.artillery.io/)
- [Documentation](https://www.artillery.io/docs)
- [Artillery GitHub Organization](https://github.com/artilleryio)
- [Artillery Source Repository](https://github.com/artilleryio/artillery)
- [Changelog](https://github.com/artilleryio/artillery/blob/main/CHANGELOG.md)
- [Pricing](https://www.artillery.io/pricing)

## Features

| Name | Description |
|------|-------------|
| HTTP Load Testing | Load test HTTP/1 and HTTP/2 REST APIs, GraphQL endpoints, and web applications with configurable virtual users, arrival rates, and scenario definitions. |
| WebSocket and Socket.IO Testing | Test real-time applications with WebSocket and Socket.IO protocol support, enabling load testing of chat, notifications, and streaming applications. |
| Playwright Integration | Run Playwright browser-based end-to-end scenarios under load, enabling realistic user simulation and synthetic monitoring from the same test framework. |
| Plugin Ecosystem | Extensible plugin system with official plugins for gRPC, Kafka, AWS Lambda, Kinesis, and community plugins for many other protocols. |
| Artillery Cloud | Hosted cloud platform for running distributed load tests at massive scale across multiple cloud regions, with centralized results and team collaboration features. |
| YAML Test Scenarios | Human-readable YAML test scenario definitions supporting think time, loops, conditional logic, data CSV files, and custom JavaScript functions. |

## Use Cases

| Name | Description |
|------|-------------|
| API Load Testing | Backend developers and QA engineers run load tests against REST and GraphQL APIs to identify performance bottlenecks and ensure stability under expected traffic volumes. |
| CI/CD Performance Gates | Engineering teams integrate Artillery into CI/CD pipelines to run performance tests on every pull request, failing builds that exceed latency or error rate thresholds. |
| Synthetic Monitoring | SREs use Artillery with Playwright to run synthetic monitors that continuously validate critical user journeys from multiple cloud regions. |
| Pre-Launch Stress Testing | Product teams run stress tests before major launches or sales events to identify the maximum capacity of their infrastructure. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | Official Artillery GitHub Action for running load tests in CI/CD pipelines with automatic reporting and performance gate enforcement. |
| Datadog | Artillery publishes metrics to Datadog for real-time monitoring and alerting during load test runs. |
| AWS Lambda | Artillery can run distributed load tests using AWS Lambda as the execution backend, enabling serverless-scale testing. |
| Playwright | Native Playwright integration for browser-based load testing and synthetic monitoring scenarios. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
