# dbt Cloud (dbt-cloud)

dbt Cloud is the analytics-engineering platform from dbt Labs for transforming data in the warehouse. It exposes the Administrative API for managing accounts, projects, jobs, runs, and environments, the Discovery (Metadata) API for project metadata and lineage via GraphQL, and the Semantic Layer API for querying governed metrics over GraphQL and JDBC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dbt-cloud/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dbt-cloud/refs/heads/main/apis.yml)

## Tags

- Data
- Analytics Engineering
- Data Transformation
- ELT
- Semantic Layer

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### dbt Cloud Administrative API

REST API (v2 and v3) over Bearer-token / service-token auth for programmatic administration of dbt Cloud - listing and triggering jobs, polling and cancelling runs, downloading run artifacts, and managing accounts, projects, environments, connections, credentials, groups, and users.

- **Human URL:** [https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api](https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api)
- **Base URL:** `https://cloud.getdbt.com/api/v2`

#### Tags

- Jobs
- Runs
- Projects
- Environments

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/admin-cloud-api)
- [API Reference](https://docs.getdbt.com/dbt-cloud/api-v2)
- [OpenAPI](openapi/dbt-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dbt-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dbt-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### dbt Cloud Discovery (Metadata) API

GraphQL API for fetching metadata about the state and health of a dbt project - models, sources, tests, exposures, lineage/DAG, and execution results - queried with a Metadata Only service token against metadata.cloud.getdbt.com/graphql.

- **Human URL:** [https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api](https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api)
- **Base URL:** `https://metadata.cloud.getdbt.com/graphql`

#### Tags

- Metadata
- Lineage
- GraphQL

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/discovery-api)
- [API Reference](https://docs.getdbt.com/docs/dbt-apis/discovery-querying)

### dbt Cloud Semantic Layer API

APIs for querying governed metrics and dimensions defined in the dbt Semantic Layer - a GraphQL API and a JDBC driver (ArrowFlight SQL) - with standard metadata functionality, authorized via service token.

- **Human URL:** [https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview)
- **Base URL:** `https://docs.getdbt.com/docs/dbt-cloud-apis/sl-graphql`

#### Tags

- Semantic Layer
- Metrics
- GraphQL
- JDBC

#### Properties

- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-api-overview)
- [GraphQL](https://docs.getdbt.com/docs/dbt-cloud-apis/sl-graphql)
- [API Reference](https://docs.getdbt.com/docs/dbt-apis/sl-jdbc)

## Common Properties

- [GitHub Organization](https://github.com/dbt-labs)
- [LinkedIn](https://www.linkedin.com/company/dbtlabsinc)
- [Website](https://www.getdbt.com)
- [Documentation](https://docs.getdbt.com/docs/dbt-cloud-apis/overview)
- [Plans](plans/dbt-cloud-plans-pricing.yml)
- [Rate Limits](rate-limits/dbt-cloud-rate-limits.yml)
- [Fin Ops](finops/dbt-cloud-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
