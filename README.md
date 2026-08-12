## About Me 👋

# Hi, I'm Arfin Syadziy Bairuha 👋

Senior backend engineer based in Depok, Indonesia, with a strong focus on Java, distributed
systems, high-volume transaction processing, financial reporting, reconciliation, and production-ready service design.

I enjoy turning complex operational requirements into maintainable software that stays observable, use resources efficiently, and reliable under heavy traffic.

## What I do

- Build backend platforms for fraud detection, transaction processing, and financial reporting.
- Designing financial reporting and automated reconciliation systems based on Mastercard,
  ISO 8583, B24, ASPI, and cross-border QR specifications.
- Modernizing high-volume Java applications and improving their performance, reliability, and
  production operability.
- Creating reusable service foundations for security, structured logging, tracing, error handling,
  auditing, scheduling, and alerting.
- Create reusable boilerplates and shared foundations for backend teams.
- Explore modern frameworks and language ecosystems such as Go, NestJS, PHP/Laravel, and AI-assisted development workflows.

## Selected impact

- Scaled transaction processing to **40 million transactions per day** across as many as 20 member
  clients.
- Modernized a QR reporting system from approximately **1 million to 30 million daily
  transactions**.
- Reduced application memory usage from approximately **150 GB to below 1 GB** through query and
  in-memory processing optimization.
- Built automated reconciliation and reporting workflows for domestic and international payment
  networks.

## Technology stack

### Backend

![Java](https://img.shields.io/badge/Java_8--21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Quarkus](https://img.shields.io/badge/Quarkus-4695EB?style=flat-square&logo=quarkus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

### Frontend

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/ReactJS-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)

### Data and messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

### DevOps, collaboration, and API tools

![Microsoft Teams](https://img.shields.io/badge/Microsoft_Teams-6264A7?style=flat-square&logo=microsoftteams&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white)
![GitKraken](https://img.shields.io/badge/GitKraken-179287?style=flat-square&logo=gitkraken&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![OrbStack](https://img.shields.io/badge/OrbStack-000000?style=flat-square&logo=orbstack&logoColor=white)
![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=flat-square&logo=portainer&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

### Development environments

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Atom](https://img.shields.io/badge/Atom-66595C?style=flat-square&logo=atom&logoColor=white)

### AI-assisted development

![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![OpenAI Codex](https://img.shields.io/badge/OpenAI_Codex-412991?style=flat-square&logo=openai&logoColor=white)
![RTK](https://img.shields.io/badge/RTK-Cursor_Workflow-000000?style=flat-square)
![ICM](https://img.shields.io/badge/ICM-Cursor_Workflow-1F6FEB?style=flat-square)
![CaveMan](https://img.shields.io/badge/CaveMan-Cursor_Workflow-000000?style=flat-square)
![QMD](https://img.shields.io/badge/QMD-Cursor_Workflow-1F6FEB?style=flat-square)

### Operating systems

![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)

## Featured projects

Together, these repositories form a multi-tenant operations platform with a single secured API
entry point, asynchronous Kafka-based observability, horizontally scalable workers, and a shared
Spring Boot service foundation.

```text
React Control Room
       |
       v
API Gateway ---- audit events --------> Kafka ----> Audit Log
       |------- request/response logs -> Kafka ----> Centralized Log
       |
       +----> User Management / Scheduler / Centralized Alert
                                      |
                                      +----> STOMP WebSocket notifications
```

### [User Management](https://github.com/syadziy/usermanagement)

Multi-tenant identity and authorization service built with Java. It provides tenant onboarding,
authentication, RBAC/permission control, JWT issuance, and audit-friendly login flows.

### [Control Room Web App](https://github.com/syadziy/web_app)

React-based operations dashboard for identity, scheduler, centralized alerting, and audit log
management through a single API Gateway.

### [API Gateway](https://github.com/syadziy/api_gateway)

Reactive gateway for routing, security enforcement, rate limiting, resilience, and centralized
request/response handling.

### [Centralized Alert](https://github.com/syadziy/centralized_alert)

Alert delivery service for REST and Kafka workflows, built for retry, idempotency, and operational
visibility.

### [Scheduler](https://github.com/syadziy/scheduler)

Task scheduler with durable execution, retry, history, and safe concurrency across replicas.

### [Audit Log](https://github.com/syadziy/audit_log)

Append-only audit service for Kafka-driven user activity tracking and investigation APIs.

### [Centralized Log](https://github.com/syadziy/centralized_log)

Go-based centralized logging service for API gateway traffic and operational events.

### [SDK Util](https://github.com/syadziy/sdk_util)

Shared Java foundation for response standardization, global exception handling, JWT security,
structured logging, trace IDs, and application-wide operational conventions.

<!-- ### [User Management](https://github.com/syadziy/usermanagement)

A multi-tenant identity and authorization service built with Java 21 and Spring Boot. It provides
tenant registration, username/password authentication, tenant-specific token policies, granular
role-based permissions, and RS256 JWT issuance with discovery metadata and public JWKS. It serves
as the primary token issuer for the API Gateway and downstream services. Tenant onboarding creates
an isolated permission catalog and first `SUPERADMIN` owner, while users can hold multiple roles
and custom `resource:action` permissions. JDBC-bound HTTP workloads use Spring Boot virtual
threads, PostgreSQL/Flyway provides durable state, and login auditing is published asynchronously
to Kafka without exposing credentials or tokens.

### [Control Room — Web App](https://github.com/syadziy/web_app)

A responsive ReactJS operations dashboard for managing identity and access, scheduled HTTP tasks,
centralized alerts, and audit events. The application uses reusable UI components, in-memory
authentication state, a domain-oriented service layer, and a single API Gateway entry point for
all backend communication. Its permission-aware interface covers tenant onboarding, user/role/
permission management, scheduler configuration and filtered execution history, recipient setup,
email delivery history, realtime alert notifications, and audit exploration. The dashboard uses
English by default, supports an Indonesian translation alongside light/dark/system themes, and
uses server-side `limit`/`offset` pagination so each page transition retrieves fresh API data.

### [SDK Util](https://github.com/syadziy/sdk_util)

A reusable Spring Boot foundation for consistent API responses, global exception handling, JWT
security and method authorization, OpenAPI, ECS structured logging, trace IDs, MDC propagation,
timezone policy, and operational standards. It provides shared `ResponseHelper` and
`ResponsePagingHelper` envelopes plus conditional auto-configuration so servlet services use the
same error, security, observability, and pagination contracts without duplicating infrastructure
code.

### [Centralized Alert](https://github.com/syadziy/centralized_alert)

A horizontally scalable alert-delivery service accepting idempotent requests through REST or
Kafka. It supports database-managed global/per-source recipients, TO/CC/BCC delivery, TEXT/HTML
messages, scheduled and manual dispatch, attachment metadata, exponential retry, Kafka DLT, and
email delivery history. PostgreSQL leases and safe claims coordinate multiple replicas, while
SMTP dispatch uses bounded Java virtual-thread concurrency. Successful events can be delivered to
the dashboard through authenticated STOMP over WebSocket.

### [Scheduler](https://github.com/syadziy/scheduler)

A scalable HTTP task scheduler with durable executions, retries, execution history, parallel and
serial groups, and nested task groups. PostgreSQL occurrence records, leases, and
`FOR UPDATE SKIP LOCKED` make execution safe across replicas and recover abandoned work. Bounded
Java virtual threads execute HTTP tasks without allowing unbounded downstream concurrency, while
history can be filtered by date/range, task, group, and threshold breach. Threshold and terminal
errors are sent to Centralized Alert, and API activity is audited once at the gateway to avoid
duplicate events.

### [Audit Log](https://github.com/syadziy/audit_log)

An append-only Java audit service that validates and consumes user-activity events from Kafka,
persists them idempotently in PostgreSQL JSONB, and exposes authenticated read-only investigation
APIs with server-side filters and pagination. Record acknowledgement follows durable persistence;
transient failures are retried and exhausted events go to a DLT. Consumer groups and unique event
IDs allow horizontal scaling without duplicate rows, while HTTP and terminal Kafka failures can
notify Centralized Alert. Production business code is protected by a 90% JaCoCo coverage gate.

### [API Gateway](https://github.com/syadziy/api_gateway)

A stateless reactive edge service built with Spring Cloud Gateway, WebFlux, and Reactor Netty. It
validates issuer/audience/expiry and granular JWT scopes, applies Redis rate limits, circuit
breakers, bulkheads, request deadlines, safe idempotent retries, exact-origin CORS, secure headers,
and platform/VIP load balancing. Downstream outages are normalized as service-unavailable gateway
responses. Audit and centralized request/response logging are independently controlled by
environment flags and published asynchronously to Kafka; sensitive fields are sanitized, actor
identity uses the JWT username, and WebSocket traffic is intentionally excluded from audit events.

### [Centralized Log](https://github.com/syadziy/centralized_log)

A horizontally scalable Go service for centralized API Gateway request and response logging. It
consumes events through a Kafka consumer group, stores them idempotently in PostgreSQL, and moves
records older than 30 days into an archive table using batch-based, concurrency-safe housekeeping.
Goroutines run Kafka consumption, health endpoints, and housekeeping independently; PostgreSQL
advisory locking and `FOR UPDATE SKIP LOCKED` ensure only one replica archives a batch while all
other replicas continue consuming. Logging stays outside the synchronous request path, and body/
header sanitization prevents credentials, tokens, cookies, and other secrets from being retained. -->

## Boilerplates

These repositories are built as learning and starter templates:

- [Java Boilerplate](https://github.com/syadziy/java_boilerplate)
- [Go Boilerplate](https://github.com/syadziy/go_boilerplate)
- [NestJS Boilerplate](https://github.com/syadziy/nest_boilerplate)
- [PHP / Laravel Boilerplate](https://github.com/syadziy/php_boilerplate)

Each boilerplate is designed to show a practical service structure with real features such as
validation, repository/service layering, caching, messaging, containerization, seed data, and demo
documentation.

## Platform engineering highlights

- **Security:** multi-tenant RS256 JWT, issuer/audience validation, granular permissions, and
  permission-aware frontend navigation and actions.
- **Concurrency:** Reactor Netty event loops at the gateway, Java virtual threads with database or
  semaphore bounds for identity, scheduling, and alert I/O, Kafka consumer groups for audit
  ingestion, and Go goroutines for centralized logging.
- **Horizontal scaling:** stateless gateway routing, PostgreSQL lease/claim patterns, Kafka
  partition ownership, idempotency keys, unique event IDs, and concurrency-safe housekeeping.
- **Observability:** trace propagation, ECS logs, Prometheus metrics, append-only user auditing,
  sanitized request/response logging, realtime notifications, and standardized error envelopes.
- **Operational safety:** graceful shutdown, health probes, retry/DLT policies, bounded connection
  pools, database migrations, and feature flags for audit and centralized logging integrations.

## Engineering interests

`High-throughput systems` · `High-volue transactions` · `Performance optimization` · `Distributed systems` ·
`Financial technology` · `Fraud detection` · `Observability` · `Developer platforms`

# Focus areas

- High-volume transaction processing
- Reconciliation and financial reporting
- Fraud detection and clustering workflows
- Service templates and reusable engineering foundations
- Production observability and operational readiness

## Currently learning

- Building consistent, reusable foundations for Java, Go, Kafka, and PostgreSQL microservices.
- Developing a permission-aware multi-tenant operations platform with centralized auditing,
  request/response logging, scheduling, alert delivery, and realtime monitoring.
- Expanding my backend engineering experience into Go, NestJS, PHP, NoSQL data stores and cloud-native service development.
- Expand AI-assisted development workflows.

---

## Contact

- GitHub: [syadziy](https://github.com/syadziy)
- Location: Depok, Indonesia

If you are visiting this profile, feel free to explore the featured repositories and boilerplates.
