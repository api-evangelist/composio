# Composio (composio)
Composio is a unified API and tooling platform for AI agents with 1000+ pre-built connectors, managed OAuth, tool search, context management, and a sandboxed workbench to help you build AI agents that turn intent into action. Authentication is via the `x-api-key` (project) or `x-org-api-key` (organization) header.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/composio/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

 - AI Agents, Authentication, Integrations, OAuth, Tools, Unified_API

## Timestamps

- **Created:** 2026-03-03
- **Modified:** 2026-04-28

## APIs

### Composio Tool Router API
Session-based API for AI agents to discover and execute tools. The Tool Router provides the primary interface for AI agents to find relevant tools and execute actions through Composio's unified platform.

**Human URL:** [https://docs.composio.dev/reference](https://docs.composio.dev/reference)

**Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

 - AI Agents, Sessions, Tools

#### Properties

- [Documentation](https://docs.composio.dev/reference)
- [Local OpenAPI](openapi/composio-openapi-original.yml)
- [Upstream OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Spectral Rules](rules/composio-rules.yml)
- [Naftiko Capabilities](capabilities/composio-tool-router.yml)

### Composio Tools API
Enables listing, searching, and executing individual actions within toolkits. The Tools API allows developers to discover available tools, filter by toolkit or capability, and execute specific actions on behalf of connected users.

**Human URL:** [https://docs.composio.dev/reference/api-reference/tools](https://docs.composio.dev/reference/api-reference/tools)

**Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

 - Actions, Execution, Tools

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/tools)
- [Local OpenAPI](openapi/composio-openapi-original.yml)
- [Upstream OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Spectral Rules](rules/composio-rules.yml)
- [Naftiko Capabilities](capabilities/composio-tool-router.yml)

### Composio Connected Accounts API
Handles management of user OAuth connections to applications. The Connected Accounts API enables creating, listing, and managing authenticated connections between end users and third-party applications through Composio's managed OAuth flow.

**Human URL:** [https://docs.composio.dev/reference/api-reference/connected-accounts](https://docs.composio.dev/reference/api-reference/connected-accounts)

**Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

 - Accounts, Authentication, Connections, OAuth

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/connected-accounts)
- [Local OpenAPI](openapi/composio-openapi-original.yml)
- [Upstream OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Spectral Rules](rules/composio-rules.yml)
- [Naftiko Capabilities](capabilities/composio-tool-router.yml)

### Composio Auth Configs API
Allows configuration of authentication methods for toolkit access. Auth configs contain developer credentials and app-level settings such as scopes and authentication methods, and can be reused across all users.

**Human URL:** [https://docs.composio.dev/reference/api-reference/auth-configs](https://docs.composio.dev/reference/api-reference/auth-configs)

**Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

 - Authentication, Configuration, OAuth

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/auth-configs)
- [Local OpenAPI](openapi/composio-openapi-original.yml)
- [Upstream OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Spectral Rules](rules/composio-rules.yml)
- [Naftiko Capabilities](capabilities/composio-tool-router.yml)

### Composio Triggers API
Manages webhook subscriptions from connected applications. The Triggers API enables developers to set up and manage event-driven notifications from third-party applications, allowing AI agents to respond to real-time events.

**Human URL:** [https://docs.composio.dev/reference/api-reference/triggers](https://docs.composio.dev/reference/api-reference/triggers)

**Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

 - Events, Triggers, Webhooks

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/triggers)
- [Local OpenAPI](openapi/composio-openapi-original.yml)
- [Upstream OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Spectral Rules](rules/composio-rules.yml)
- [Naftiko Capabilities](capabilities/composio-tool-router.yml)

### Composio Toolkits API
Provides browsing capabilities for available applications and their associated tools. The Toolkits API allows developers to discover and explore the 1000+ available integrations across services like GitHub, Gmail, Slack, Notion, and more.

**Human URL:** [https://docs.composio.dev/reference/api-reference/toolkits](https://docs.composio.dev/reference/api-reference/toolkits)

**Base URL:** `https://backend.composio.dev/api/v3`

#### Tags

 - Applications, Integrations, Toolkits

#### Properties

- [Documentation](https://docs.composio.dev/reference/api-reference/toolkits)
- [Local OpenAPI](openapi/composio-openapi-original.yml)
- [Upstream OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Spectral Rules](rules/composio-rules.yml)
- [Naftiko Capabilities](capabilities/composio-tool-router.yml)

## Common Properties

- [Portal](https://app.composio.dev/dashboard)
- [Documentation](https://docs.composio.dev/docs)
- [Getting Started](https://docs.composio.dev/docs/quickstart)
- [API Reference](https://docs.composio.dev/reference)
- [OpenAPI](https://backend.composio.dev/api/v3/openapi.json)
- [Authentication](https://docs.composio.dev/faq/api_key/api_key)
- [Blog](https://composio.dev/blog)
- [Status](https://status.composio.dev)
- [Pricing](https://composio.dev/pricing)
- [Change Log](https://docs.composio.dev/docs/changelog)
- [Privacy Policy](https://composio.dev/privacy)
- [Terms of Service](https://composio.dev/terms)
- [GitHub Organization](https://github.com/ComposioHQ)
- [GitHub Repo](https://github.com/ComposioHQ/composio)
- [Python SDK](https://github.com/ComposioHQ/composio)
- [Node.js SDK](https://www.npmjs.com/package/@composio/client)
- [Sign Up](https://app.composio.dev/dashboard)
- [JSON-LD](json-ld/composio-context.jsonld)
- [Tool JSON Schema](json-schema/composio-tool-schema.json)
- [Toolkit JSON Schema](json-schema/composio-toolkit-schema.json)
- [Connected Account JSON Schema](json-schema/composio-connected-account-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
