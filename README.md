# Accredible (accredible)

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
