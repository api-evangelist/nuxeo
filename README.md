# Nuxeo (nuxeo)

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

Nuxeo is an open-source, cloud-native enterprise content management platform owned by Hyland Software. It provides a comprehensive REST API for managing documents, digital assets, workflows, metadata, search, batch uploads, and cloud file storage in large-scale enterprise environments. The API supports OAuth2, token-based, and basic authentication, and exposes automation chains, content enrichers, and web adapters for flexible integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nuxeo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nuxeo/refs/heads/main/apis.yml)

## Tags

- Content Management
- Digital Asset Management
- Enterprise
- Documents
- Workflows
- Search
- Open Source

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Nuxeo REST API

The Nuxeo REST API provides HTTP/HTTPS access to the full Nuxeo Platform, enabling CRUD operations on documents, assets, users, groups, directories, workflows, tasks, and configurations. It exposes an automation command endpoint with over 100 server-side operations, batch upload support, search via NXQL and page providers, OAuth2 resource management, and user preferences. All endpoints follow the base path /nuxeo/api/v1/.

- **Human URL:** [https://doc.nuxeo.com/nxdoc/rest-api/](https://doc.nuxeo.com/nxdoc/rest-api/)
- **Base URL:** `https://{nuxeo-server}/nuxeo/api/v1`

#### Tags

- Documents
- Assets
- Workflows
- Search
- Automation
- Batch Upload
- OAuth2

#### Properties

- [Documentation](https://doc.nuxeo.com/nxdoc/rest-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nuxeo/main/openapi/nuxeo-rest-api-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A P I Source](https://github.com/nuxeo-sandbox/nuxeo-openapi)
- [Swagger](https://github.com/nuxeo/nuxeo-rest-api-swagger-doc)
- [Authentication](https://doc.nuxeo.com/rest-api/1/authentication/)
- [Endpoints](https://doc.nuxeo.com/nxdoc/rest-api-endpoints/)
- [How Tos](https://doc.nuxeo.com/nxdoc/rest-api-howtos/)
- [Automation](https://doc.nuxeo.com/nxdoc/content-automation-concepts/)

## Common Properties

- [Website](https://www.hyland.com/en/solutions/products/nuxeo-platform)
- [Documentation](https://doc.nuxeo.com/nxdoc/)
- [Git Hub Org](https://github.com/nuxeo)
- [LinkedIn](https://www.linkedin.com/company/nuxeo)
- [Blog](https://connect.hyland.com/t5/nuxeo-blog/bg-p/nuxeo1blog-board)
- [Pricing](https://www.hyland.com/en/resources/nuxeo-download)
- [Status Page](https://doc.nuxeo.com/nxdoc/health-check/)
- [X (Twitter)](https://x.com/nuxeo)
- [Plans](plans/nuxeo-plans-pricing.yml)
- [Rate Limits](rate-limits/nuxeo-rate-limits.yml)
- [Fin Ops](finops/nuxeo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
