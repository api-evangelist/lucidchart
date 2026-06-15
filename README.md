# Lucidchart (lucidchart)

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
