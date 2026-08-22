# Salesforce Knowledge Management (salesforce-knowledge-management)

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

API for managing knowledge articles, categories, and data in Salesforce Knowledge. Enables creating, reading, updating, publishing, and archiving knowledge articles for customer self-service and agent-assisted support scenarios across multiple channels including internal app, public knowledge base, and customer portals.

**APIs.json:** [https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/](https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/)

## Tags

- Articles
- CRM
- Customer Service
- Documentation
- Knowledge Management
- Support

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Salesforce Knowledge REST API

REST API for accessing and managing Salesforce Knowledge articles, categories, and knowledge base content. Enables creating, reading, updating, publishing, and archiving knowledge articles for customer self-service and agent-assisted support scenarios.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/](https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/)
- **Base URL:** `https://yourInstance.salesforce.com/services/data/v59.0/support`

#### Tags

- Articles
- Knowledge
- REST

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development.htm)
- [OpenAPI](openapi/salesforce-knowledge-management-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salesforce-knowledge-management-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-knowledge-management-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm)

### Salesforce Knowledge SOAP API

SOAP API for managing knowledge articles with enterprise integration.

- **Human URL:** [https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/](https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/)
- **Base URL:** `https://yourInstance.salesforce.com/services/Soap/c/59.0`

#### Tags

- Enterprise
- Knowledge
- SOAP

#### Properties

- [Documentation](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_knowledge.htm)
- [W S D L](https://yourInstance.salesforce.com/services/wsdl/class/KnowledgeArticleVersion)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm)
- [Postman Collection](collections/salesforce-knowledge-management-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salesforce-knowledge-management-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development_intro.htm)
- [Authentication](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm)
- [Rate Limits](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm)
- [S D Ks](https://developer.salesforce.com/tools/sdks)
- [Status Page](https://status.salesforce.com/)
- [Terms of Service](https://www.salesforce.com/company/legal/agreements/)
- [Privacy Policy](https://www.salesforce.com/company/privacy/)
- [Trailhead  Learning](https://trailhead.salesforce.com/en/content/learn/modules/knowledge-basics)
- [GitHub Organization](https://github.com/salesforce)
- [Spectral  Rules](rules/salesforce-knowledge-management-rules.yml)
- [Capabilities](capabilities/knowledge-management.yaml)
- [J S O N  Schema](json-schema/salesforce-knowledge-management-article-schema.json)
- [J S O N  Schema](json-schema/salesforce-knowledge-management-category-schema.json)
- [J S O N- L D  Context](json-ld/salesforce-knowledge-management-context.jsonld)
- [Vocabulary](vocabulary/salesforce-knowledge-management-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
