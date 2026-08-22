# Glide (glide-apps)

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
