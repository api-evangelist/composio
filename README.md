# Composio (composio)

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
