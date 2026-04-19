# Amazon AppSync

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
