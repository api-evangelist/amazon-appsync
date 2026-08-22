# Amazon AppSync

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon AppSync creates serverless GraphQL and Pub/Sub APIs that simplify application development through a single endpoint to securely query, update, or publish data.

## Overview

The Amazon AppSync management API provides programmatic control over GraphQL APIs, data sources, resolvers, functions, types, schemas, API keys, and custom domain names. It enables building scalable real-time and offline applications backed by multiple data sources.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/appsync/latest/APIReference/Welcome.html
- **Base URL:** https://appsync.us-east-1.amazonaws.com

## Features

- Managed GraphQL API hosting with automatic scaling
- Multiple authentication modes including API key, IAM, Cognito, and Lambda
- Real-time subscriptions via WebSocket connections
- Pipeline resolvers for composing multi-step data access patterns
- Direct Lambda resolvers with APPSYNC_JS runtime support
- Built-in caching for improved performance
- Conflict detection and resolution for offline sync use cases
- Custom domain names with ACM certificate integration
- X-Ray tracing and CloudWatch logging integration
- Merged APIs for combining multiple GraphQL APIs

## Use Cases

- Build mobile and web applications with a unified GraphQL data layer
- Implement real-time features like live notifications and chat with subscriptions
- Create a unified data access layer across multiple microservices
- Build offline-capable mobile apps with automatic conflict resolution
- Expose DynamoDB tables, Lambda functions, and OpenSearch as GraphQL APIs
- Implement federated GraphQL across multiple teams with Merged APIs

## Artifacts

### OpenAPI Specification
`openapi/amazon-appsync-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all AppSync management API paths.

### Spectral Rules
`rules/amazon-appsync-spectral-rules.yml`

### Naftiko Capabilities
- `capabilities/shared/appsync-api.yaml` — Shared per-API capability definition
- `capabilities/graphql-api-management.yaml` — Workflow capability for GraphQL API management

### Vocabulary
`vocabulary/amazon-appsync-vocabulary.yaml`

### JSON Schemas
`json-schema/` — 73 JSON Schema files for all objects.

### JSON Structures
`json-structure/` — 73 JSON Structure files.

### JSON-LD Context
`json-ld/amazon-appsync-context.jsonld`

### Examples
`examples/` — 73 example JSON files.

## Integrations

- Amazon DynamoDB
- AWS Lambda
- Amazon OpenSearch Service
- Amazon RDS
- Amazon EventBridge
- Amazon Cognito
- AWS IAM
- AWS WAF
- Amazon CloudWatch
- AWS X-Ray
- AWS Certificate Manager
- Amazon Route 53

## Tags

Amazon AppSync, GraphQL, API Management, Serverless, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
