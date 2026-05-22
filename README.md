# Redocly (redocly)

Redocly is a company that specializes in API documentation and governance tooling. Their platform helps organizations create, manage, and publish API documentation through Realm (the integrated lifecycle platform unifying Redoc, Revel, and Reef), Reunite (Git-connected collaboration and deployment for docs/APIs), Revel (developer portal), Reef (internal API catalog and scorecard), and Redoc (open-source OpenAPI renderer). The Redocly CLI provides linting, bundling, splitting, decoration, and documentation generation for OpenAPI, AsyncAPI, and Arazzo specifications. Respect Monitoring adds continuous, Arazzo-powered API monitoring, and the Enterprise tier exposes MCP Servers and AI search for Realm portals.

**URL:** [https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

AI, API Catalog, API Documentation, Arazzo, Developer Portal, Governance, Linting, MCP, Monitoring, OpenAPI

## Timestamps

- **Created:** 2026-01-05
- **Modified:** 2026-05-22

## APIs

### Redocly Realm

Comprehensive API lifecycle management platform unifying Redoc, Revel, and Reef. Includes API documentation, mock servers, linting, catalog, scorecard, API functions, Markdown/Markdoc/React docs, API Scout for hidden-API discovery, dynamic client registration, MCP Servers (Enterprise) with OAuth and CIMD support, plus AI search and Typesense search.

**Human URL:** [https://redocly.com/realm](https://redocly.com/realm)

#### Tags

AI, API Catalog, Developer Portal, Documentation, MCP

---

### Redocly Reunite

Git-connected collaboration and deployment surface for Realm. Ships a content editor, pull requests and reviews, deployments, scorecards, feedback, Respect Monitoring integration, and compliance reports. Provides Webview previews, Branch Previews, and GitOps releases. Integrates with GitHub, GitLab, Bitbucket, and Azure DevOps.

**Human URL:** [https://redocly.com/reunite](https://redocly.com/reunite)

#### Tags

Collaboration, Deployment, Documentation, GitOps

---

### Redocly Revel

External developer hub rendering Markdown, Markdoc, and React pages with multi-product and localization support. Creates polished, public-facing developer portals and onboarding experiences.

**Human URL:** [https://redocly.com/revel](https://redocly.com/revel)

#### Tags

Developer Portal, Documentation, Localization

---

### Redocly Reef

Internal API platform — service catalog and governance product with catalog organization, Scorecard linting rules, API Scout for hidden-API discovery, API functions, and developer onboarding with dynamic client registration.

**Human URL:** [https://redocly.com/reef](https://redocly.com/reef)

#### Tags

API Catalog, Governance, Scorecard

---

### Redocly Redoc

Open-source OpenAPI documentation renderer with a three-panel layout. Supports OpenAPI 3.2, 3.1, 3.0, and Swagger 2.0. Available as React component, HTML tag, CLI, and Docker image with over 25,000 GitHub stars.

**Human URL:** [https://redocly.com/redoc](https://redocly.com/redoc)

#### Tags

Documentation, OpenAPI, Reference

---

### Redocly CLI

Open-source CLI for linting, bundling, splitting, decorating, and building documentation from OpenAPI, AsyncAPI, and Arazzo definitions. Supports OpenAPI 3.2/3.1/3.0/2.0, AsyncAPI 3.0/2.6, and Arazzo 1.0/1.1. Built-in rulesets: spec, recommended, recommended-strict, minimal.

**Human URL:** [https://redocly.com/redocly-cli](https://redocly.com/redocly-cli)

#### Tags

Arazzo, CLI, Governance, Linting, OpenAPI

#### Properties

- [Documentation](https://redocly.com/docs/cli)
- [Reference](https://redocly.com/docs/cli/commands/lint)
- [Changelog](https://redocly.com/docs/cli/changelog)
- [GitHubOrg](https://github.com/Redocly/redocly-cli)
- [JSONSchema](json-schema/redocly-config-schema.json)
- [JSONSchema](json-schema/redocly-lint-result-schema.json)
- [JSONStructure](json-structure/redocly-config-structure.json)
- [JSONStructure](json-structure/redocly-lint-result-structure.json)
- [JSON-LD](json-ld/redocly-context.jsonld)
- [Vocabulary](vocabulary/redocly-vocabulary.yml)

---

### Redocly Respect Monitoring

Continuous API-aware monitoring powered by OpenAPI Arazzo workflows. Validates that API responses conform to specifications (status codes, content types, headers, schemas) and detects schema drift, missing status codes, and performance issues. Slack/email alerts, multi-environment support, and CI/CD integration with GitHub, GitLab, and Jenkins. Usage-based: 1,000 free monthly requests; commitment plans $100/month (20k) to $1,000/month (500k).

**Human URL:** [https://redocly.com/respect](https://redocly.com/respect)

#### Tags

Arazzo, Monitoring, Observability, Testing

---

### Arazzo Specification (Redocly Tooling)

Redocly is a primary tooling vendor for the OpenAPI Initiative's Arazzo specification (multi-step API workflows). Arazzo 1.1 (May 2026) adds AsyncAPI support, workflow composition, selectors, identity-based references, and clearer runtime behavior.

**Human URL:** [https://redocly.com/blog/arazzo-specification-1-1-release](https://redocly.com/blog/arazzo-specification-1-1-release)

#### Tags

Arazzo, OpenAPI, Specification, Workflows

---

## Examples

| File | Description |
|---|---|
| [examples/redocly-config-example.json](examples/redocly-config-example.json) | Example redocly.yaml configuration with multi-API setup |
| [examples/redocly-lint-result-example.json](examples/redocly-lint-result-example.json) | Example lint output with errors and warnings |
| [examples/redocly-cli-commands-example.json](examples/redocly-cli-commands-example.json) | Common CLI commands: lint, bundle, build-docs, split, push |

## Plans, Rate Limits, and FinOps

- [plans/redocly-plans-pricing.yml](plans/redocly-plans-pricing.yml) — API Commons Plans 0.1 capturing published Pro ($10/seat), Enterprise ($24/seat), Enterprise+, Revel/Reef/Realm add-ons, and Respect Monitoring usage tiers.
- [rate-limits/redocly-rate-limits.yml](rate-limits/redocly-rate-limits.yml) — API Commons Rate Limits 0.1 documenting project/page subscription quotas and Respect Monitoring monthly request quotas.
- [finops/redocly-finops.yml](finops/redocly-finops.yml) — FOCUS-aligned FinOps mapping for the hybrid subscription + metered billing surface.

## Common Properties

- [Documentation](https://redocly.com/docs)
- [Blog](https://redocly.com/blog)
- [Pricing](https://redocly.com/pricing)
- [Status](https://status.redocly.com/)
- [Support](https://redocly.com/contact-us)
- [Login](https://auth.cloud.redocly.com/login)
- [PrivacyPolicy](https://redocly.com/privacy-notice)
- [TermsOfService](https://redocly.com/subscription-agreement)
- [GitHubOrg](https://github.com/Redocly)
- [X](https://twitter.com/Redocly)
- [LinkedIn](https://www.linkedin.com/company/redocly)
- [Governance](https://redocly.com/api-governance)
- [Changelog](https://redocly.com/docs/realm/changelog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
