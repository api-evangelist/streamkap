# Streamkap (streamkap)

Streamkap is a real-time streaming ETL and change data capture (CDC) platform built on Apache Kafka and Apache Flink. It streams data from operational databases (PostgreSQL, MySQL, MongoDB, SQL Server, Oracle) to cloud warehouses, lakes, and other destinations with sub-second latency, and its REST API lets teams provision and operate sources, destinations, pipelines, transforms, and Kafka access programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/streamkap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/streamkap/refs/heads/main/apis.yml)

## Tags

- Streaming
- ETL
- CDC
- Kafka
- Flink
- Data Integration
- Real Time

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Streamkap Sources API

Create, configure, deploy, pause, resume, restart, and reset source connectors that capture change data from databases and other systems, plus snapshot control (blocking, incremental, parallel), metrics, config history, and bulk operations.

- **Human URL:** [https://docs.streamkap.com/api-reference/sources](https://docs.streamkap.com/api-reference/sources)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Sources
- CDC
- Connectors
- Snapshots

#### Properties

- [Documentation](https://docs.streamkap.com/sources)
- [API Reference](https://docs.streamkap.com/api-reference/sources)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Destinations API

Manage sink destinations - Snowflake, Databricks, BigQuery, ClickHouse, Redshift, S3, Iceberg, and more - including create, update, deploy, lifecycle control, configuration schemas, metrics, and bulk operations.

- **Human URL:** [https://docs.streamkap.com/api-reference/destinations](https://docs.streamkap.com/api-reference/destinations)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Destinations
- Warehouses
- Connectors
- Sinks

#### Properties

- [Documentation](https://docs.streamkap.com/destinations)
- [API Reference](https://docs.streamkap.com/api-reference/destinations)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Pipelines API

Create and manage end-to-end pipelines that wire a source to a destination (optionally through transforms), with lifecycle management, per-pipeline metrics and logs, and bulk operations.

- **Human URL:** [https://docs.streamkap.com/api-reference/pipelines](https://docs.streamkap.com/api-reference/pipelines)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Pipelines
- Orchestration
- Data Flow

#### Properties

- [Documentation](https://docs.streamkap.com/pipelines)
- [API Reference](https://docs.streamkap.com/api-reference/pipelines)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Connectors API

Discover the catalog of available source and destination connector types and their configuration schemas so sources and destinations can be provisioned programmatically against the correct connector definitions.

- **Human URL:** [https://docs.streamkap.com/connectors](https://docs.streamkap.com/connectors)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Connectors
- Catalog
- Configuration

#### Properties

- [Documentation](https://docs.streamkap.com/connectors)
- [API Reference](https://docs.streamkap.com/api-reference/sources)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Transforms API

Author, clone, unit-test, preview, and deploy in-stream transforms (SQL, Python, TypeScript) running on Flink, including input/output topic wiring, checkpoints, DLQ errors, and job status.

- **Human URL:** [https://docs.streamkap.com/api-reference/transforms](https://docs.streamkap.com/api-reference/transforms)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Transforms
- Flink
- SQL
- Streaming Agents

#### Properties

- [Documentation](https://docs.streamkap.com/transforms)
- [API Reference](https://docs.streamkap.com/api-reference/transforms)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Topics API

Create, inspect, and manage the underlying Kafka topics - browse messages and message values, read topic metrics, statistics, and Kafka broker metadata, publish records, and drive topic-level snapshots.

- **Human URL:** [https://docs.streamkap.com/api-reference/topics](https://docs.streamkap.com/api-reference/topics)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Topics
- Kafka
- Messages

#### Properties

- [API Reference](https://docs.streamkap.com/api-reference/topics)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Tags API

Create, search, update, and delete tags used to label and group sources, destinations, pipelines, transforms, and topics for organization and bulk operations.

- **Human URL:** [https://docs.streamkap.com/api-reference/tags](https://docs.streamkap.com/api-reference/tags)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Tags
- Organization
- Metadata

#### Properties

- [API Reference](https://docs.streamkap.com/api-reference/tags)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Kafka Access API

Provision Kafka users and their ACLs for direct broker access, inspect consumer groups and reset their offsets, and browse the Schema Registry subjects and versions backing the streams.

- **Human URL:** [https://docs.streamkap.com/api-reference/kafka-access](https://docs.streamkap.com/api-reference/kafka-access)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Kafka
- Access
- ACLs
- Consumer Groups

#### Properties

- [API Reference](https://docs.streamkap.com/api-reference/kafka-access)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Streamkap Authentication API

Exchange a client-id and secret (or a project key) for a JWT access token, refresh tokens, manage client credentials and project keys, and inspect the caller's identity, permissions, and roles.

- **Human URL:** [https://docs.streamkap.com/api-reference/authentication](https://docs.streamkap.com/api-reference/authentication)
- **Base URL:** `https://api.streamkap.com/api`

#### Tags

- Authentication
- Tokens
- Project Keys
- Credentials

#### Properties

- [API Reference](https://docs.streamkap.com/api-reference/authentication)
- [OpenAPI](openapi/streamkap-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/streamkap.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/streamkap.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/streamkap-com)
- [LinkedIn](https://www.linkedin.com/company/streamkap)
- [Website](https://streamkap.com/)
- [Documentation](https://docs.streamkap.com)
- [Plans](plans/streamkap-plans-pricing.yml)
- [Rate Limits](rate-limits/streamkap-rate-limits.yml)
- [Fin Ops](finops/streamkap-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
