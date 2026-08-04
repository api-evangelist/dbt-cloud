# dbt Cloud (dbt-cloud)

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
