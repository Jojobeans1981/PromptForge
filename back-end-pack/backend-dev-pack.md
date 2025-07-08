## 1. 🔍 API Endpoint Review
"Review the following [BACKEND_FRAMEWORK] REST API endpoint for security, scalability, and code quality. Suggest improvements.

Endpoint code:
[CODE_SNIPPET]"

## 2. 🐞 SQL Query Debugger
"This SQL query is producing an error: [ERROR_MESSAGE]

Query:
[SQL_QUERY]

Analyze the issue and suggest specific fixes."

## 3. 🔒 Security Audit
"Perform a security audit on this backend code, listing potential vulnerabilities and suggesting how to fix/mitigate them.

Code:
[CODE_SNIPPET]"

## 4. 🚦 Input Validation Enhancer
"Review the following backend function and improve all input validation. Explain new checks added.

Function:
[CODE_SNIPPET]"

## 5. 📦 Microservice Refactoring
"Refactor this [LANGUAGE] service to improve modularity, separation of concerns, and ease of testing.

Service code:
[CODE_SNIPPET]"

## 6. 📝 API Documentation Generator
"Generate OpenAPI compatible documentation for this [BACKEND_FRAMEWORK] REST endpoint.

Endpoint code:
[CODE_SNIPPET]"

## 7. 🔐 JWT Security Hardening
"Audit this JWT implementation for vulnerabilities. Check: algorithm confusion, secret strength, token storage, refresh logic. Provide secure implementation.

Current code: [JWT_IMPLEMENTATION]
Requirements: [SECURITY_NEEDS]"

## 8. 🛡️ SQL Injection Scanner
"Scan this code for SQL injection vulnerabilities. Convert all dynamic queries to parameterized statements for [DATABASE_TYPE].

Database code: [DB_QUERIES]
Input sources: [USER_INPUTS]"

## 9. 🔑 OAuth2 PKCE Flow
"Implement OAuth2 with PKCE for [PROVIDER]. Include: state validation, token storage, refresh handling, and error cases.

Provider: [OAUTH_PROVIDER]
App type: [SPA/MOBILE/SERVER]"

## 10. 🚨 Rate Limiter Design
"Design distributed rate limiting using [REDIS/MEMCACHED] with: sliding windows, user tiers, endpoint limits, and burst handling.

Traffic patterns: [EXPECTED_LOAD]
Infrastructure: [SETUP]"

## 11. 🔒 Password Policy Engine
"Implement password validation checking: strength, history, common passwords, breach databases (HaveIBeenPwned).

Requirements: [POLICY_RULES]
Storage: [DATABASE_TYPE]"

## 12. 🛡️ API Key Management
"Build API key system with: secure generation, usage tracking, rate limiting per key, rotation, and revocation.

Key types: [CATEGORIES]
Persistence: [STORAGE]"

## 13. 🔐 Session Security
"Harden session management against: fixation, hijacking, concurrent sessions, and timing attacks.

Current implementation: [SESSION_CODE]
Session store: [REDIS/DB/MEMORY]"

## 14. 🚦 CORS Configuration
"Configure CORS for [SCENARIO] with: origin validation, credentials handling, preflight caching, and security headers.

Allowed origins: [DOMAINS]
API structure: [ENDPOINTS]"

## 15. 🔒 Encryption at Rest
"Implement encryption at rest for [DATA_TYPE] using: key rotation, envelope encryption, and compliance standards.

Compliance: [GDPR/HIPAA/PCI]
Storage: [DATABASE/S3/FILESYSTEM]"

## 16. 📊 Query Performance Analyzer
"Analyze and optimize this slow query using: execution plans, index strategies, query rewriting, and caching.

Query: [SLOW_QUERY]
EXPLAIN output: [EXECUTION_PLAN]
Table sizes: [STATISTICS]"

## 17. 🔄 N+1 Query Resolver
"Fix N+1 queries using: eager loading, batch loading, or DataLoader pattern for [ORM_TYPE].

Models: [ENTITY_RELATIONSHIPS]
Current queries: [QUERY_CODE]"

## 18. 🗄️ Migration Safety Check
"Review database migration for: rollback safety, data integrity, performance impact, and zero-downtime deployment.

Migration: [MIGRATION_SCRIPT]
Current schema: [DATABASE_SCHEMA]"

## 19. ⚡ Index Strategy Builder
"Design indexes for this workload considering: query patterns, write overhead, storage cost, and maintenance.

Queries: [FREQUENT_QUERIES]
Write frequency: [WRITE_PATTERNS]"

## 20. 🔒 Transaction Deadlock Resolver
"Analyze transactions for deadlock potential. Suggest: lock ordering, isolation levels, and retry strategies.

Transaction code: [TRANSACTION_LOGIC]
Concurrency: [EXPECTED_LOAD]"

## 21. 📈 Partition Strategy Designer
"Design partitioning for [TABLE] based on: access patterns, data growth, maintenance windows, and query performance.

Table structure: [SCHEMA]
Data characteristics: [PATTERNS]"

## 22. 🔄 Connection Pool Tuning
"Optimize connection pool for: burst traffic, long queries, health checks, and automatic recovery.

Current config: [POOL_SETTINGS]
Load profile: [TRAFFIC_PATTERN]"

## 23. 📊 Query Cache Optimizer
"Implement query caching strategy using [REDIS/MEMCACHED] with: cache keys, TTL, invalidation, and warming.

Query patterns: [COMMON_QUERIES]
Data volatility: [UPDATE_FREQUENCY]"

## 24. 🗄️ Backup Strategy Design
"Design backup strategy with: incremental backups, point-in-time recovery, testing procedures, and compliance.

RPO/RTO: [REQUIREMENTS]
Data volume: [SIZE]"

## 25. ⚡ Bulk Operation Optimizer
"Optimize bulk insert/update using: batching, parallel processing, temporary tables, and progress tracking.

Operation: [BULK_LOGIC]
Data volume: [RECORD_COUNT]"

## 26. 🏗️ RESTful API Best Practices
"Review API design for: resource modeling, HTTP methods, status codes, filtering, pagination, and HATEOAS.

API spec: [CURRENT_API]
Use cases: [REQUIREMENTS]"

## 27. 🔄 GraphQL Resolver Optimizer
"Optimize GraphQL resolvers for: N+1 queries, batching, caching, and complexity analysis.

Schema: [GRAPHQL_SCHEMA]
Resolvers: [RESOLVER_CODE]"

## 28. 📦 Event-Driven Architecture
"Convert synchronous flow to event-driven using [KAFKA/RABBITMQ/SNS] with delivery guarantees.

Current flow: [SYNC_CODE]
Consistency needs: [REQUIREMENTS]"

## 29. 🌐 API Gateway Setup
"Configure API gateway with: routing, authentication, rate limiting, caching, and monitoring.

Services: [MICROSERVICES]
Gateway: [KONG/APIGEE/AWS]"

## 30. 🔄 Saga Pattern Implementation
"Implement distributed saga with: compensations, timeouts, state persistence, and monitoring.

Business flow: [PROCESS]
Services: [PARTICIPANTS]"

## 31. 📊 Service Mesh Configuration
"Setup service mesh for: mTLS, traffic management, circuit breaking, and observability.

Services: [TOPOLOGY]
Platform: [ISTIO/LINKERD]"

## 32. 🔒 API Versioning
"Design versioning strategy with: URL/header versioning, deprecation notices, and client migration.

Current API: [ENDPOINTS]
Changes planned: [BREAKING_CHANGES]"

## 33. 📦 CQRS Implementation
"Implement CQRS with: command handlers, event sourcing, read models, and eventual consistency.

Domain: [BUSINESS_LOGIC]
Read patterns: [QUERIES]"

## 34. 🔄 Circuit Breaker
"Implement circuit breaker with: failure thresholds, timeout handling, fallbacks, and monitoring.

Dependencies: [EXTERNAL_SERVICES]
SLA requirements: [UPTIME_NEEDS]"

## 35. 📈 Load Testing Suite
"Create load tests covering: normal load, spike testing, soak testing, and breakpoint testing.

Endpoints: [API_SURFACE]
Performance goals: [METRICS]"

## 36. 🔒 mTLS Setup
"Implement mutual TLS between services with: certificate management, rotation, and monitoring.

Service map: [ARCHITECTURE]
CA setup: [PKI_INFRASTRUCTURE]"

## 37. 📦 Message Queue Design
"Design message queue architecture with: dead letter queues, retry policies, and monitoring.

Message types: [EVENTS]
Volume: [THROUGHPUT]"

## 38. 🔄 Async Job Processor
"Build async job processor with: priority queues, retries, idempotency, and progress tracking.

Job types: [TASKS]
Processing requirements: [SLA]"

## 39. 📊 Distributed Tracing
"Implement distributed tracing using [JAEGER/ZIPKIN] with: span creation, context propagation, and sampling.

Services: [MICROSERVICES]
Critical paths: [FLOWS]"

## 40. 🔒 Secret Management
"Implement secrets management using [VAULT/AWS_SECRETS] with: rotation, audit, and emergency access.

Secret types: [CREDENTIALS]
Compliance: [REQUIREMENTS]"

## 41. 🚀 Performance Profiling
"Profile application for: CPU usage, memory leaks, I/O bottlenecks, and garbage collection issues.

Application: [CODE_BASE]
Performance goals: [TARGETS]"

## 42. 📝 Error Handling Strategy
"Design error handling with: error types, logging levels, user messages, and recovery strategies.

Service type: [APPLICATION]
Error scenarios: [COMMON_ERRORS]"

## 43. 🔍 Log Aggregation Setup
"Implement centralized logging with: structured logs, correlation IDs, search capabilities, and alerting.

Log sources: [SERVICES]
Volume: [LOGS_PER_SECOND]"

## 44. 📊 Metrics Collection
"Setup metrics collection for: business KPIs, technical metrics, SLIs/SLOs, and dashboards.

Metrics platform: [PROMETHEUS/DATADOG]
Critical metrics: [KPI_LIST]"

## 45. 🔒 Compliance Automation
"Automate compliance checks for [GDPR/HIPAA/SOC2] including: data retention, access logs, and encryption.

Requirements: [COMPLIANCE_NEEDS]
Current gaps: [AUDIT_FINDINGS]"

## 46. 📦 Container Security
"Secure container deployment with: vulnerability scanning, runtime protection, and secret management.

Container platform: [DOCKER/K8S]
Registry: [CONTAINER_REGISTRY]"

## 47. 🔄 Blue-Green Deployment
"Implement blue-green deployment with: health checks, rollback triggers, and database migrations.

Infrastructure: [CLOUD_PLATFORM]
Application: [SERVICE_TYPE]"

## 48. 📈 Capacity Planning
"Create capacity planning model based on: growth projections, peak loads, and resource utilization.

Current metrics: [USAGE_DATA]
Growth rate: [PROJECTIONS]"

## 49. 🔒 Zero Trust Architecture
"Design zero trust security model with: service authentication, least privilege, and continuous verification.

Network topology: [ARCHITECTURE]
Security requirements: [POLICIES]"

## 50. 🚀 Performance Optimization Checklist
"Create comprehensive performance optimization plan covering: database, caching, CDN, and code optimization.

Current bottlenecks: [PERFORMANCE_ISSUES]
Target improvements: [GOALS]"