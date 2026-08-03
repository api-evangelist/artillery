# Artillery (artillery)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
