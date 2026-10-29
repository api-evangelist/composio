# Composio

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

**Areas:** AI Agents · Authentication · Integration · MCP · Sandbox · Tools · Triggers · Unified API · Webhook

## Composio on APIs.io

Everything profiled for Composio is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/composio/](https://apis.io/providers/composio/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [Composio Auth Configs API](https://apis.io/apis/composio/composio-auth-configs-api/) — Authentication configuration management
- [Composio Authentication API](https://apis.io/apis/composio/composio-authentication-api/) — Authentication related endpoints
- [Composio CLI API](https://apis.io/apis/composio/composio-cli-api/) — CLI integration endpoints
- [Composio CLI Authentication API](https://apis.io/apis/composio/composio-cli-authentication-api/) — The CLI Authentication API from Composio — 2 operation(s) for cli authentication.
- [Composio Connected Accounts API](https://apis.io/apis/composio/composio-connected-accounts-api/) — Connected account management
- [Composio Files API](https://apis.io/apis/composio/composio-files-api/) — File management
- [Composio Logs API](https://apis.io/apis/composio/composio-logs-api/) — Logging and monitoring
- [Composio MCP API](https://apis.io/apis/composio/composio-mcp-api/) — MCP server management
- [Composio Migration API](https://apis.io/apis/composio/composio-migration-api/) — Endpoints to help with migration from v1 to v3
- [Composio Organization Management API](https://apis.io/apis/composio/composio-organization-management-api/) — The Organization Management API from Composio — 5 operation(s) for organization management.
- [Composio Projects API](https://apis.io/apis/composio/composio-projects-api/) — The Projects API from Composio — 6 operation(s) for projects.
- [Composio Tool Router API](https://apis.io/apis/composio/composio-tool-router-api/) — (Labs) Tool router endpoints
- [Composio Toolkits API](https://apis.io/apis/composio/composio-toolkits-api/) — Toolkit and tool management
- [Composio Tools API](https://apis.io/apis/composio/composio-tools-api/) — Tool execution endpoints
- [Composio Triggers API](https://apis.io/apis/composio/composio-triggers-api/) — Trigger management and execution
- [Composio Webhook Endpoints API](https://apis.io/apis/composio/composio-webhook-endpoints-api/) — Per-OAuth-app webhook ingress endpoints. Inbound URLs the provider posts to, plus signing secret storage and verification.
- [Composio Webhook Subscriptions API](https://apis.io/apis/composio/composio-webhook-subscriptions-api/) — Webhook delivery subscriptions. Outbound URLs Composio posts trigger events to, plus signing secret rotation and event-type filters.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (11)

Multi-step workflows that chain operations into a business task.

- [Composio Connect an Account via a New Auth Config](https://apis.io/arazzos/composio/composio-connect-account-via-auth-config-workflow/)
- [Composio Disable an Active Trigger](https://apis.io/arazzos/composio/composio-disable-active-trigger-workflow/)
- [Composio Discover and Execute a Tool](https://apis.io/arazzos/composio/composio-discover-and-execute-tool-workflow/)
- [Composio Execute a Tool on a User's Connected Account](https://apis.io/arazzos/composio/composio-execute-tool-on-connected-account-workflow/)
- [Composio Generate a Hosted Auth Link](https://apis.io/arazzos/composio/composio-hosted-auth-link-workflow/)
- [Composio Natural Language Tool Execution](https://apis.io/arazzos/composio/composio-natural-language-tool-execution-workflow/)
- [Composio Provision an MCP Server](https://apis.io/arazzos/composio/composio-provision-mcp-server-workflow/)
- [Composio Refresh a Connected Account](https://apis.io/arazzos/composio/composio-refresh-connected-account-workflow/)
- [Composio Set Up a Trigger](https://apis.io/arazzos/composio/composio-setup-trigger-workflow/)
- [Composio Tool Router Connect a Toolkit](https://apis.io/arazzos/composio/composio-tool-router-connect-toolkit-workflow/)
- [Composio Tool Router Session](https://apis.io/arazzos/composio/composio-tool-router-session-workflow/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [composio-mcp.yml](https://apis.io/servers/composio/composio-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Composio Agentic Access](https://apis.io/agentic-access/composio/composio-agentic-access/)

#### JSON Schema (24)

The data models the API reads and writes.

- [AuthConfigListResponse](https://apis.io/schemas/composio/composio-authconfiglistresponse/)
- [AuthConfigResponse](https://apis.io/schemas/composio/composio-authconfigresponse/)
- [Composio Connected Account](https://apis.io/schemas/composio/composio-connected-account/)
- [ConnectedAccountListResponse](https://apis.io/schemas/composio/composio-connectedaccountlistresponse/)
- [ConnectedAccountResponse](https://apis.io/schemas/composio/composio-connectedaccountresponse/)
- [CreateAuthConfigRequest](https://apis.io/schemas/composio/composio-createauthconfigrequest/)
- [CreateConnectedAccountRequest](https://apis.io/schemas/composio/composio-createconnectedaccountrequest/)
- [CreateTriggerRequest](https://apis.io/schemas/composio/composio-createtriggerrequest/)
- [DeprecatedToolkitInfo](https://apis.io/schemas/composio/composio-deprecatedtoolkitinfo/)
- [Error](https://apis.io/schemas/composio/composio-error/)
- [ErrorResponse](https://apis.io/schemas/composio/composio-errorresponse/)
- [ExecuteToolRequest](https://apis.io/schemas/composio/composio-executetoolrequest/)
- [ExecuteToolResponse](https://apis.io/schemas/composio/composio-executetoolresponse/)
- [PatchConnectedAccountBody](https://apis.io/schemas/composio/composio-patchconnectedaccountbody/)
- [SessionResponse](https://apis.io/schemas/composio/composio-sessionresponse/)
- [Composio Tool](https://apis.io/schemas/composio/composio-tool/)
- [Composio Toolkit](https://apis.io/schemas/composio/composio-toolkit/)
- [ToolkitListResponse](https://apis.io/schemas/composio/composio-toolkitlistresponse/)
- [ToolkitResponse](https://apis.io/schemas/composio/composio-toolkitresponse/)
- [ToolListResponse](https://apis.io/schemas/composio/composio-toollistresponse/)
- [ToolRouterToolkitsListResponse](https://apis.io/schemas/composio/composio-toolroutertoolkitslistresponse/)
- [ToolsPaginated](https://apis.io/schemas/composio/composio-toolspaginated/)
- [TriggerListResponse](https://apis.io/schemas/composio/composio-triggerlistresponse/)
- [TriggerResponse](https://apis.io/schemas/composio/composio-triggerresponse/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Composio Structure](https://apis.io/json-structure/composio/composio-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Composio Context](https://apis.io/jsonld/composio/composio-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Composio Domain Vocabulary](https://apis.io/vocabularies/composio/composio-vocabulary/)

#### Examples (13)

Example requests and responses.

- [Composio Patchauthconfigsbynanoid Example](https://apis.io/examples/composio/composio-patchauthconfigsbynanoid-example/)
- [Composio Patchconnectedaccountsbynanoid Example](https://apis.io/examples/composio/composio-patchconnectedaccountsbynanoid-example/)
- [Composio Patchmcpbyid Example](https://apis.io/examples/composio/composio-patchmcpbyid-example/)
- [Composio Patchorgprojectconfig Example](https://apis.io/examples/composio/composio-patchorgprojectconfig-example/)
- [Composio Postclicodactfailures Example](https://apis.io/examples/composio/composio-postclicodactfailures-example/)
- [Composio Postfilesuploadrequest Example](https://apis.io/examples/composio/composio-postfilesuploadrequest-example/)
- [Composio Postlabstoolroutersession Example](https://apis.io/examples/composio/composio-postlabstoolroutersession-example/)
- [Composio Postmcpservers Example](https://apis.io/examples/composio/composio-postmcpservers-example/)
- [Composio Postmcpserversbyserveridinstances Example](https://apis.io/examples/composio/composio-postmcpserversbyserveridinstances-example/)
- [Composio Postmcpserverscustom Example](https://apis.io/examples/composio/composio-postmcpserverscustom-example/)
- [Composio Postmcpserversgenerate Example](https://apis.io/examples/composio/composio-postmcpserversgenerate-example/)
- [Composio Postorgownerprojectnew Example](https://apis.io/examples/composio/composio-postorgownerprojectnew-example/)
- [Composio Posttoolroutersession Example](https://apis.io/examples/composio/composio-posttoolroutersession-example/)

#### Collections (40)

Postman and Open Collection request collections.

- [Composio Platform Account Management API](https://apis.io/collections/composio/open-composio-account-management-api/)
- [Composio Platform Account Management AI API](https://apis.io/collections/composio/open-composio-ai-api/)
- [Composio Platform Account Management API Keys API](https://apis.io/collections/composio/open-composio-api-keys-api/)
- [Composio Platform Account Management Applications API](https://apis.io/collections/composio/open-composio-applications-api/)
- [Composio Platform Account Management Auth Configs API](https://apis.io/collections/composio/open-composio-auth-configs-api/)
- [Composio Platform Account Management Authentication API](https://apis.io/collections/composio/open-composio-authentication-api/)
- [Composio Platform Account Management Categories API](https://apis.io/collections/composio/open-composio-categories-api/)
- [Composio Platform Account Management CLI API](https://apis.io/collections/composio/open-composio-cli-api/)
- [Composio Platform Account Management CLI Authentication API](https://apis.io/collections/composio/open-composio-cli-authentication-api/)
- [Composio Platform Account Management Configuration API](https://apis.io/collections/composio/open-composio-configuration-api/)
- [Composio Platform Account Management Connected Accounts API](https://apis.io/collections/composio/open-composio-connected-accounts-api/)
- [Composio Platform Account Management Custom API](https://apis.io/collections/composio/open-composio-custom-api/)
- [Composio Platform Account Management Execution API](https://apis.io/collections/composio/open-composio-execution-api/)
- [Composio Platform Account Management Files API](https://apis.io/collections/composio/open-composio-files-api/)
- [Composio Platform Account Management Instances API](https://apis.io/collections/composio/open-composio-instances-api/)
- [Composio Platform Account Management Integration API](https://apis.io/collections/composio/open-composio-integration-api/)
- [Composio Platform Account Management Logs API](https://apis.io/collections/composio/open-composio-logs-api/)
- [Composio Platform Account Management MCP API](https://apis.io/collections/composio/open-composio-mcp-api/)
- [Composio Platform Account Management Migration API](https://apis.io/collections/composio/open-composio-migration-api/)
- [Composio Platform Account Management Natural Language Processing API](https://apis.io/collections/composio/open-composio-natural-language-processing-api/)
- [Composio Platform API](https://apis.io/collections/composio/open-composio-openapi-original/)
- [Composio Platform Account Management Organization API](https://apis.io/collections/composio/open-composio-organization-api/)
- [Composio Platform Account Management Organization Management API](https://apis.io/collections/composio/open-composio-organization-management-api/)
- [Composio Platform Account Management Projects API](https://apis.io/collections/composio/open-composio-projects-api/)
- [Composio Platform Account Management Proxy API](https://apis.io/collections/composio/open-composio-proxy-api/)
- …and 15 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Composio Openapi Original Overlay](https://apis.io/overlays/composio/composio-openapi-original-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Composio — jsonschema rules](https://apis.io/rules/composio/composio-jsonschema-spectral-rules/)
- [Composio API Rules](https://apis.io/rules/composio/composio-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Composio Authentication](https://apis.io/security/composio/composio-authentication/)
- [Composio Domain Security](https://apis.io/security/composio/composio-domain-security/)
- [Composio Vulnerability Disclosure](https://apis.io/security/composio/composio-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Composio Plans Pricing](https://apis.io/plans/composio/composio-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Composio Rate Limits](https://apis.io/rate-limits/composio/composio-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Composio Finops](https://apis.io/finops/composio/composio-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.composio.dev/)
- [Documentation](https://docs.composio.dev/docs)
- [Getting started](https://docs.composio.dev/docs/quickstart)
- [API reference](https://docs.composio.dev/reference)
- [Pricing](https://composio.dev/pricing)
- [Changelog](https://docs.composio.dev/docs/changelog)
- [Blog](https://composio.dev/blog)
- [Terms of service](https://composio.dev/terms)
- [Privacy policy](https://composio.dev/privacy)
- [GitHub](https://github.com/ComposioHQ)
- [Status](https://status.composio.dev)

## API Evangelist rating

**Kin Score 55.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 54.0 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 56.0 |
| Access clarity | 52.6 |

**Agent readiness 30.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/composio/](https://apis.io/providers/composio/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Composio: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/composio/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
