---
api_specs:
- filename: cz-agents-dev-openapi-generated.yml
  format: yaml
  label: cz-agents-dev API
  slug: cz-agents-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cz-agents-dev/openapi/_ae-authored/cz-agents-dev-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Public registry data — IČO, company names, statutory bodies, sanction list entries, insolvency proceedings, FX rates.
  - category: device
    text: Request metadata — IP address (for rate limiting), Bearer API tokens (for paid tiers), HTTP headers, request/response timing.
  - category: financial
    text: Billing data — for paid tiers we use Stripe as a payment processor.
  - category: contact
    text: Stripe holds card data and customer email; we hold the Stripe customer/subscription IDs linked to an opaque API token (no card data).
  deletion:
    route: address the original registry (e.g. ARES) for registry-sourced data; contact email otherwise
    text: For data that originates from a public registry, the appropriate erasure path is to address the original registry (e.g. ARES).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operating public registry lookup service
    text: Legal basis (GDPR Art. 6) Public registry data — Art. 6(1)(f) legitimate interest .
  - purpose: operating, securing and rate-limiting the service
    text: Request metadata — Art. 6(1)(f) legitimate interest in operating, securing, and rate-limiting the service.
  - purpose: contract performance for billing
    text: Billing data — Art. 6(1)(b) contract performance .
  residency:
  - region: Germany (Falkenstein)
    text: Servers are hosted in Falkenstein, DE (Hetzner).
  retention:
  - period: up to 30 days
    scope: request metadata in server logs
    text: Retained for up to 30 days in server logs, then deleted.
  - period: null
    scope: public registry data
    text: We do not store this data beyond cache TTL except for sanctions snapshots (kept for change-detection) and the ISIR event feed (append-only log).
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: you have the rights under GDPR Art. 15–22 (access, rectification, erasure, restriction, portability, objection).
  - right: confirmation of cached data
    text: We can confirm what we cache about you and refresh from source on request.
  role:
    text: cz-agents ( the service ) is operated by Martin Havel
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share data with third parties for marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We do not transfer data outside the EU.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cz-agents-dev
provenance_date: '2026-11-09'
provider_name: cz-agents-dev
provider_slug: cz-agents-dev
slug: cz-agents-dev-privacy-policy
source_date: '2026-11-09'
source_filename: cz-agents-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cz-agents.dev/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cz-agents-dev\naid: cz-agents-dev\nurl: https://cz-agents.dev/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: cz-agents ( the service ) is operated by Martin Havel\ndata_categories:\n- category: identifying\n  text: Public registry data — IČO, company names, statutory bodies, sanction list entries, insolvency proceedings,\n    FX rates.\n- category: device\n  text: Request metadata — IP address (for rate limiting), Bearer API tokens (for paid tiers), HTTP headers, request/response\n    timing.\n- category: financial\n  text: Billing data — for paid tiers we use Stripe as a payment\
  \ processor.\n- category: contact\n  text: Stripe holds card data and customer email; we hold the Stripe customer/subscription IDs linked to an opaque\n    API token (no card data).\npurposes:\n- purpose: operating public registry lookup service\n  text: Legal basis (GDPR Art. 6) Public registry data — Art. 6(1)(f) legitimate interest .\n- purpose: operating, securing and rate-limiting the service\n  text: Request metadata — Art. 6(1)(f) legitimate interest in operating, securing, and rate-limiting the service.\n- purpose: contract performance for billing\n  text: Billing data — Art. 6(1)(b) contract performance .\nretention:\n- scope: request metadata in server logs\n  period: up to 30 days\n  text: Retained for up to 30 days in server logs, then deleted.\n- scope: public registry data\n  period: null\n  text: We do not store this data beyond cache TTL except for sanctions snapshots (kept for change-detection) and\n    the ISIR event feed (append-only log).\nresidency:\n- region: Germany\
  \ (Falkenstein)\n  text: Servers are hosted in Falkenstein, DE (Hetzner).\ntransfers:\n- mechanism: other\n  text: We do not transfer data outside the EU.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: address the original registry (e.g. ARES) for registry-sourced data; contact email otherwise\n  text: For data that originates from a public registry, the appropriate erasure path is to address the original\n    registry (e.g. ARES).\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: you have the rights under GDPR Art. 15–22 (access, rectification, erasure, restriction, portability, objection).\n- right: confirmation of cached data\n  text: We can confirm what we cache about you and refresh from source on request.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share data with third parties for marketing.\n"
source_yaml_url: https://artifacts.apis.io/cz-agents-dev/privacy/cz-agents-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from cz-agents-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- Czech
- Compliance
- Open Source
- Artificial Intelligence
---
