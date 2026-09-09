# System Design Practice

## Recommended interview flow

### 1. Clarify requirements

Identify the primary users, core workflows, scale, availability expectations, latency targets, data retention, and geographic constraints.

### 2. Establish constraints

State assumptions explicitly. Separate hard requirements from preferences.

### 3. Propose the high-level architecture

Describe the request path and the major components before discussing implementation details.

### 4. Design the data model and APIs

Define the important entities, access patterns, consistency requirements, API boundaries, and idempotency strategy.

### 5. Address reliability

Discuss timeouts, retries, circuit breakers, queues, replication, graceful degradation, failure isolation, and recovery.

### 6. Address security

Cover authentication, authorisation, input validation, secrets, encryption, abuse prevention, and auditability.

### 7. Address observability

Define the logs, metrics, traces, alerts, dashboards, and operational signals needed to diagnose the system.

### 8. Scale deliberately

Identify the first bottleneck and explain how the design evolves as traffic, data, and team size increase.

### 9. State trade-offs

Explain what the design intentionally does not optimise for and why.

## Practice scenarios

Use the existing architecture questions as prompts:

- Real-time notification system
- URL shortening service
- Distributed file storage
- High-volume social media feed
- E-commerce product catalogue and search

For each scenario, produce a one-page design before expanding into implementation details.
