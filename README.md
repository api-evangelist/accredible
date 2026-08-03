# Accredible (accredible)

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

Accredible is a digital credentialing platform for issuing, managing, and verifying digital certificates and Open Badges. The REST API lets issuers create and update credentials (certificates and badges) for recipients, organize them into Groups (courses/achievements), apply reusable visual Designs, attach Evidence Items and References, generate PDFs and blockchain-verifiable records, pull engagement analytics, manage Departments and Team Members, and generate recipient SSO links. Credentials are issued against a Group and rendered with a Design; the platform hosts a public verification page and share links for each credential.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/accredible/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/accredible/refs/heads/main/apis.yml)

Base URL: `https://api.accredible.com/v1` (sandbox: `https://sandbox.api.accredible.com/v1`). Authentication is an API key sent in the `Authorization` header using the scheme `Token token=YOUR_API_KEY`.

## Tags

- Digital Credentials
- Certificates
- Badges
- Open Badges
- Credentialing
- Verification
- Digital Badges

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs

### Accredible Credentials API

Create, retrieve, update, and delete digital credentials (certificates and badges), bulk-create credentials, search credentials, generate credential PDFs, resolve credential redirects, verify blockchain records, and pull per-credential analytics. Each credential is issued to a recipient against a Group.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Credentials
- Certificates
- Badges
- Issuing

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [API Reference](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Accredible Groups API

Manage Groups - the course or achievement containers that credentials are issued against. Create, retrieve, update, delete, list, and search Groups under the issuer account.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Groups
- Courses
- Achievements

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Accredible Designs API

Create, retrieve, update, delete, copy, search, and preview reusable visual Designs that specify how a credential (badge or certificate) is rendered, and initialize the embedded badge and certificate designer experiences. A Design can be reused across multiple Groups.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Designs
- Badges
- Certificates
- Templates

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Accredible Evidence and References API

Attach richer proof to a credential. Create, retrieve, update, and delete Evidence Items (work samples and artifacts) and References (peer, teacher, or manager endorsements) nested under an individual credential.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Evidence
- References
- Supplemental

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Accredible Analytics API

Retrieve issuer-level engagement analytics across credentials - views, shares, and other interaction metrics - to measure the reach of issued certificates and badges.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Analytics
- Engagement
- Reporting

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Accredible Departments and Team Members API

Administer an issuer organization. Search Departments (independent sub-organizations with their own Designs, Groups, and branding) and create, retrieve, update, and delete Team Members and their roles.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Departments
- Team Members
- Administration

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Accredible Issuer and SSO API

Read issuer account details and generate recipient single sign-on (SSO) links that let a recipient access their credentials, plus rotate the account API token.

- **Human URL:** [https://docs.api.accredible.com/](https://docs.api.accredible.com/)
- **Base URL:** `https://api.accredible.com/v1`

#### Tags

- Issuer
- SSO
- Recipients

#### Properties

- [Documentation](https://docs.api.accredible.com/)
- [OpenAPI](openapi/accredible-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/accredible.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/accredible.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/accredible)
- [LinkedIn](https://www.linkedin.com/company/accredible)
- [Website](https://www.accredible.com)
- [Documentation](https://docs.api.accredible.com/)
- [Plans](plans/accredible-plans-pricing.yml)
- [Rate Limits](rate-limits/accredible-rate-limits.yml)
- [Fin Ops](finops/accredible-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
