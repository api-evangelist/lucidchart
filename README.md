# Lucidchart (lucidchart)

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

Lucidchart is a web-based intelligent diagramming application by Lucid Software, part of the Lucid Visual Collaboration Suite (Lucidchart, Lucidspark, Lucidscale). The Lucid Developer Platform exposes a REST API for documents/folders/collaborators/content, an Extension API for in-editor extensions, an Embed SDK for embedding diagrams in external apps, and a SCIM API for enterprise provisioning.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lucidchart/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lucidchart/refs/heads/main/apis.yml)

## Tags

- Productivity
- Diagramming
- Visualization
- Visual Workspace
- SaaS

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Lucid REST API

Programmatically create, search, read, copy, trash, and restore Lucid documents and folders. Manage collaborators and document permissions. Transfer content (import/export) and embed Lucid documents in other apps.

- **Human URL:** [https://developer.lucid.co/api/v1/](https://developer.lucid.co/api/v1/)
- **Base URL:** `https://api.lucid.co`

#### Tags

- Documents
- Folders
- REST

#### Properties

- [Documentation](https://developer.lucid.co/)
- [API Reference](https://developer.lucid.co/api/v1/)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucid Document Content / Import-Export API

Read structured document content (shapes, lines, pages) and import standard formats (Visio VSDX, Gliffy, draw.io, Mermaid, AWS architecture). Export to PNG, PDF, JPEG, SVG, and CSV.

- **Human URL:** [https://developer.lucid.co/api/v1/](https://developer.lucid.co/api/v1/)
- **Base URL:** `https://api.lucid.co`

#### Tags

- Content
- Import
- Export

#### Properties

- [API Reference](https://developer.lucid.co/api/v1/)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucid Embed SDK & API

Embed Lucid diagrams and whiteboards into external apps with read-only or interactive viewing, and listen to events such as page change and shape selection.

- **Human URL:** [https://developer.lucid.co/embed-sdk/](https://developer.lucid.co/embed-sdk/)
- **Base URL:** `https://lucid.app`

#### Tags

- Embed
- SDK
- Browser

#### Properties

- [Documentation](https://developer.lucid.co/embed-sdk/)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucid Extension API

Build extensions that run inside Lucidchart, Lucidspark, and Lucidscale editors. Read and modify canvas content, import data, and ship custom shape libraries via the lucid-package CLI.

- **Human URL:** [https://developer.lucid.co/extension-api/](https://developer.lucid.co/extension-api/)
- **Base URL:** `https://api.lucid.co`

#### Tags

- Extensions
- SDK
- In-Editor

#### Properties

- [Documentation](https://developer.lucid.co/extension-api/)
- [SDK](https://www.npmjs.com/package/lucid-extension-sdk)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucid OAuth 2.0 API

OAuth 2.0 authorization-code flow used by all Lucid REST API integrations to obtain user-scoped access tokens.

- **Human URL:** [https://developer.lucid.co/api/v1/#section/Authentication](https://developer.lucid.co/api/v1/#section/Authentication)
- **Base URL:** `https://lucid.app`

#### Tags

- OAuth
- Authorization

#### Properties

- [Documentation](https://developer.lucid.co/api/v1/#section/Authentication)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucid SCIM API

SCIM 2.0 API for Enterprise customers. Provisions users and groups from Okta, Azure AD, OneLogin, and other IdPs across the Lucid Visual Collaboration Suite.

- **Human URL:** [https://developer.lucid.co/scim-api/](https://developer.lucid.co/scim-api/)
- **Base URL:** `https://users.lucid.app/scim/v2`

#### Tags

- SCIM
- Identity
- Provisioning

#### Properties

- [API Reference](https://developer.lucid.co/scim-api/)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Lucid Webhooks API

Subscribe to events on documents and folders (create, update, trash, restore) and receive HTTP callbacks at your endpoint.

- **Human URL:** [https://developer.lucid.co/api/v1/#tag/Events](https://developer.lucid.co/api/v1/#tag/Events)
- **Base URL:** `https://api.lucid.co`

#### Tags

- Webhooks
- Events

#### Properties

- [API Reference](https://developer.lucid.co/api/v1/#tag/Events)
- [Postman Collection](collections/lucidchart.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lucidchart.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/lucidchart)
- [Website](https://www.lucidchart.com/)
- [Developer Portal](https://developer.lucid.co/)
- [Pricing](https://www.lucidchart.com/pages/pricing/lucidchart)
- [Git Hub](https://github.com/lucidsoftware)
- [Plans](plans/lucidchart-plans-pricing.yml)
- [Rate Limits](rate-limits/lucidchart-rate-limits.yml)
- [Fin Ops](finops/lucidchart-finops.yml)
- [L L Ms Txt](https://developer.lucid.co/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
