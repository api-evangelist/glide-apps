# Glide (glide-apps)

Glide is a no-code platform for building custom business apps from your data. The Glide REST API (v2) lets you programmatically work with Glide Big Tables - creating tables, listing and paginating rows, adding, updating, and deleting rows, staging large batches with stashes, and querying tables with SQL - using a Bearer API token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/glide-apps/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/glide-apps/refs/heads/main/apis.yml)

## Tags

- No Code
- App Builder
- Tables
- Big Tables
- Data
- AI

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Glide Tables API

Create and overwrite Glide Big Tables in a team, defining columns and optionally seeding data, and discover the tables available to an API token.

- **Human URL:** [https://apidocs.glideapps.com/api-reference/v2](https://apidocs.glideapps.com/api-reference/v2)
- **Base URL:** `https://api.glideapps.com`

#### Tags

- Tables
- Big Tables
- Schema

#### Properties

- [Documentation](https://www.glideapps.com/docs/using-glide-tables-api)
- [API Reference](https://apidocs.glideapps.com/api-reference/v2/tables/post-tables)
- [OpenAPI](openapi/glide-apps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glide-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glide-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glide Big Tables Rows API

List rows from a Big Table with continuation-token pagination (max 10K rows per response), read a single row by ID, add rows, patch an existing row, and delete a row, with optional ETag/If-Match data versioning.

- **Human URL:** [https://apidocs.glideapps.com/api-reference/v2](https://apidocs.glideapps.com/api-reference/v2)
- **Base URL:** `https://api.glideapps.com`

#### Tags

- Rows
- CRUD
- Pagination

#### Properties

- [Documentation](https://www.glideapps.com/docs/using-glide-tables-api)
- [API Reference](https://apidocs.glideapps.com/api-reference/v2)
- [OpenAPI](openapi/glide-apps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glide-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glide-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glide Stash & Bulk API

Stage large data payloads in serial chunks via stashes, then reference the stash when creating a table or adding rows so very large batches can be loaded without oversized request bodies; delete a stash when finished.

- **Human URL:** [https://apidocs.glideapps.com/api-reference/v2](https://apidocs.glideapps.com/api-reference/v2)
- **Base URL:** `https://api.glideapps.com`

#### Tags

- Stash
- Bulk
- Batch

#### Properties

- [Documentation](https://www.glideapps.com/docs/using-glide-tables-api)
- [API Reference](https://apidocs.glideapps.com/api-reference/v2)
- [OpenAPI](openapi/glide-apps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glide-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glide-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Glide Queries API

Query a Big Table with SQL (SELECT with WHERE/AND/OR and parameter binding) to retrieve filtered, server-side result sets, with continuation support for large results. Available on Business and Enterprise plans.

- **Human URL:** [https://apidocs.glideapps.com/api-reference/v2](https://apidocs.glideapps.com/api-reference/v2)
- **Base URL:** `https://api.glideapps.com`

#### Tags

- Queries
- SQL
- Filter

#### Properties

- [Documentation](https://www.glideapps.com/docs/getting-started-with-the-glide-api)
- [API Reference](https://apidocs.glideapps.com/api-reference/v2)
- [OpenAPI](openapi/glide-apps-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/glide-apps.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/glide-apps.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/glideapps)
- [LinkedIn](https://www.linkedin.com/company/glideapps)
- [Website](https://www.glideapps.com)
- [Documentation](https://www.glideapps.com/docs)
- [Plans](plans/glide-apps-plans-pricing.yml)
- [Rate Limits](rate-limits/glide-apps-rate-limits.yml)
- [Fin Ops](finops/glide-apps-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
