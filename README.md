# Redocly (redocly)

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
