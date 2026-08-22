# Composio (composio)

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

Composio is an agent execution platform that bridges AI decision-making and real-world action across 1000+ apps through just-in-time tool calls, secure delegated auth, sandboxed environments, an MCP gateway, parallel execution, and context-aware sessions. Developers get managed OAuth, a tool router for runtime tool discovery, webhook triggers, and a CLI so agents turn intent into action without custom integration work.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Agents
- Authentication
- Integrations
- MCP
- OAuth
- Sandbox
- Tools
- Triggers
- Unified_API
- Webhooks

## Timestamps

- **Created:** 2026-03-03
- **Modified:** 2026-05-19

## APIs

### Composio Tool Router API

Session-based API for AI agents to discover and execute tools. The Tool Router provides the primary interface for AI agents to find relevant tools and execute actions through Composio's unified platform.

- **Human URL:** [https://docs.composio.dev/reference](https://docs.composio.dev/reference)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- AI Agents
- Sessions
- Tools

#### Properties

- [Documentation](https://docs.composio.dev/reference)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio Tools API

Enables listing, searching, and executing individual actions within toolkits. The Tools API allows developers to discover available tools, filter by toolkit or capability, and execute specific actions on behalf of connected users.

- **Human URL:** [https://docs.composio.dev/reference/api-reference/tools](https://docs.composio.dev/reference/api-reference/tools)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- Actions
- Execution
- Tools

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/tools)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio Connected Accounts API

Handles management of user OAuth connections to applications. The Connected Accounts API enables creating, listing, and managing authenticated connections between end users and third-party applications through Composio's managed OAuth flow.

- **Human URL:** [https://docs.composio.dev/reference/api-reference/connected-accounts](https://docs.composio.dev/reference/api-reference/connected-accounts)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- Accounts
- Authentication
- Connections
- OAuth

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/connected-accounts)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio Auth Configs API

Allows configuration of authentication methods for toolkit access. Auth configs contain developer credentials and app-level settings such as scopes and authentication methods, and can be reused across all users.

- **Human URL:** [https://docs.composio.dev/reference/api-reference/auth-configs](https://docs.composio.dev/reference/api-reference/auth-configs)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- Authentication
- Configuration
- OAuth

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/auth-configs)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio Triggers API

Manages webhook subscriptions from connected applications. The Triggers API enables developers to set up and manage event-driven notifications from third-party applications, allowing AI agents to respond to real-time events.

- **Human URL:** [https://docs.composio.dev/reference/api-reference/triggers](https://docs.composio.dev/reference/api-reference/triggers)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- Events
- Triggers
- Webhooks

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/triggers)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio Toolkits API

Provides browsing capabilities for available applications and their associated tools. The Toolkits API allows developers to discover and explore the 1000+ available integrations across services like GitHub, Gmail, Slack, Notion, and more.

- **Human URL:** [https://docs.composio.dev/reference/api-reference/toolkits](https://docs.composio.dev/reference/api-reference/toolkits)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- Applications
- Integrations
- Toolkits

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/toolkits)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio MCP API

Exposes Composio's toolkits over the Model Context Protocol so MCP-compatible clients (Claude Desktop, Cursor, and other MCP hosts) can discover and execute Composio tools through a managed gateway with delegated auth and scoped sessions.

- **Human URL:** [https://docs.composio.dev/reference](https://docs.composio.dev/reference)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- MCP
- Gateway
- AI Agents
- Tools

#### Properties

- [Documentation](https://docs.composio.dev/reference)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

### Composio Webhooks API

Manages webhook endpoints and subscriptions for outbound delivery of Composio events (trigger fires, account state changes, execution events) to consumer-owned HTTP endpoints, including signing keys and replay controls.

- **Human URL:** [https://docs.composio.dev/reference](https://docs.composio.dev/reference)
- **Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

- Events
- Webhooks
- Notifications

#### Properties

- [Documentation](https://docs.composio.dev/reference)
- [OpenAPI](openapi/composio-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/composio-openapi-original.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/composio-openapi-original.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/composio-openapi-original.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral  Rules](rules/composio-rules.yml)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/composiohq)
- [Portal](https://app.composio.dev/dashboard)
- [Documentation](https://docs.composio.dev/docs)
- [Getting Started](https://docs.composio.dev/docs/quickstart)
- [API Reference](https://docs.composio.dev/reference)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://docs.composio.dev/faq/api_key/api_key)
- [Blog](https://composio.dev/blog)
- [Status Page](https://status.composio.dev)
- [Pricing](https://composio.dev/pricing)
- [Changelog](https://docs.composio.dev/docs/changelog)
- [Privacy Policy](https://composio.dev/privacy)
- [Terms of Service](https://composio.dev/terms)
- [GitHub Organization](https://github.com/ComposioHQ)
- [Git Hub  Repo](https://github.com/ComposioHQ/composio)
- [Python  S D K](https://github.com/ComposioHQ/composio)
- [Node.js  S D K](https://www.npmjs.com/package/@composio/client)
- [Sign Up](https://app.composio.dev/dashboard)
- [Agent  Sign  Up](https://agents.composio.dev)
- [Toolkits  Catalog](https://composio.dev/toolkits)
- [JSON-LD](json-ld/composio-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/composio-tool-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/composio-toolkit-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/composio-connected-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [L L Ms Txt](https://docs.composio.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
