---
api_specs:
- filename: codag-activate-api-openapi.yml
  format: yaml
  label: Codag Activate API
  slug: codag-activate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-activate-api-openapi.yml
- filename: codag-admin-api-openapi.yml
  format: yaml
  label: Codag Admin API
  slug: codag-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-admin-api-openapi.yml
- filename: codag-anonymous-api-openapi.yml
  format: yaml
  label: Codag Anonymous API
  slug: codag-anonymous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-anonymous-api-openapi.yml
- filename: codag-auth-api-openapi.yml
  format: yaml
  label: Codag Auth API
  slug: codag-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-auth-api-openapi.yml
- filename: codag-billing-api-openapi.yml
  format: yaml
  label: Codag Billing API
  slug: codag-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-billing-api-openapi.yml
- filename: codag-capsule-api-openapi.yml
  format: yaml
  label: Codag Capsule API
  slug: codag-capsule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-capsule-api-openapi.yml
- filename: codag-cli-api-openapi.yml
  format: yaml
  label: Codag Cli API
  slug: codag-cli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-cli-api-openapi.yml
- filename: codag-compact-api-openapi.yml
  format: yaml
  label: Codag Compact API
  slug: codag-compact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-compact-api-openapi.yml
- filename: codag-free-api-openapi.yml
  format: yaml
  label: Codag Free API
  slug: codag-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-free-api-openapi.yml
- filename: codag-health-api-openapi.yml
  format: yaml
  label: Codag Health API
  slug: codag-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-health-api-openapi.yml
- filename: codag-incident-memory-api-openapi.yml
  format: yaml
  label: Codag Incident Memory API
  slug: codag-incident-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-incident-memory-api-openapi.yml
- filename: codag-install-sh-api-openapi.yml
  format: yaml
  label: Codag Install.sh API
  slug: codag-install-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-install-sh-api-openapi.yml
- filename: codag-internal-api-openapi.yml
  format: yaml
  label: Codag Internal API
  slug: codag-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-internal-api-openapi.yml
- filename: codag-onboard-api-openapi.yml
  format: yaml
  label: Codag Onboard API
  slug: codag-onboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-onboard-api-openapi.yml
- filename: codag-org-api-openapi.yml
  format: yaml
  label: Codag Org API
  slug: codag-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-org-api-openapi.yml
- filename: codag-orgs-api-openapi.yml
  format: yaml
  label: Codag Orgs API
  slug: codag-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-orgs-api-openapi.yml
- filename: codag-parse-api-openapi.yml
  format: yaml
  label: Codag Parse API
  slug: codag-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-parse-api-openapi.yml
- filename: codag-whoami-api-openapi.yml
  format: yaml
  label: Codag Whoami API
  slug: codag-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-whoami-api-openapi.yml
- filename: codag-oauth-api-openapi.yml
  format: yaml
  label: Codag OAUTH API
  slug: codag-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-oauth-api-openapi.yml
- filename: codag-agent-cost-api-openapi.yml
  format: yaml
  label: Codag Agent Cost API
  slug: codag-agent-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codag/openapi/codag-agent-cost-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data. Name, email, organization.
  - category: behavioral
    text: Eligible tool output, transiently. Large eligible tool results (logs, test and build output, search results, file listings, document reads, agent handoffs) plus minimal task context are processed to produce the reduced evidence and are not retained.
  - category: device
    text: Contentless usage metrics. Byte and token counts, estimated costs, latency, reduce or passthrough decisions, fail-open reasons, retry and retrieval counters, client versions, plan and billing events.
  - category: financial
    text: Stripe. Payment processing and subscription management. Handles card data; we do not store full card numbers.
  deletion:
    route: Request full deletion of all per-customer data by emailing [email protected]
    text: Request full deletion of all per-customer data by emailing [email protected] . We honor requests within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate and bill
    text: Used to authenticate and bill.
  - purpose: Return reduced evidence
    text: Process eligible tool output transiently to return the reduced evidence.
  - purpose: Meter usage and report savings
    text: Meter usage, bill plans, and report savings using the contentless metrics described above.
  - purpose: Aggregate reliability and cost diagnostics
    text: Aggregate reliability and cost metrics to diagnose issues, prevent abuse, plan capacity, and guide product decisions.
  residency:
  - region: United States
    text: Account data and contentless metrics are stored in an encrypted PostgreSQL database hosted on US-based cloud infrastructure.
  retention:
  - period: while your account is active
    scope: Contentless metrics, account data, billing records
    text: Contentless metrics, account data, and billing records are retained while your account is active.
  - period: 30 days
    scope: Account deletion
    text: If you delete your account or request deletion in writing, we purge all per-customer data within 30 days.
  - period: seven days
    scope: Local encrypted cache
    text: The local encrypted cache on your machine expires on its own after seven days and is yours to delete at any time.
  - period: null
    scope: Customer content processed for reduction
    text: Customer content is processed only on inference endpoints Codag controls and is not retained after the request completes.
  rights:
  - right: Access, correct, or delete account data
    text: Access, correct, or delete your account data.
  - right: Export usage records
    text: Export your usage records.
  - right: GDPR rights
    text: EU and UK residents have additional rights under GDPR; California residents have additional rights under CPRA.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data.
  subprocessors:
    text: Google OAuth. Console sign-in. We receive name and email from your Google account. Stripe. Payment processing and subscription management. Handles card data; we do not store full card numbers. Modal. Managed infrastructure for Codag-controlled inference. Railway. US-based cloud hosting for the API and database. Vercel. Hosting for the web console. Resend. Transactional email delivery (such as organization invites). PostHog. Product analytics, website analytics, feature usage, and opt-out state for non-essential analytics.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Codag
provenance_date: '2026-11-09'
provider_name: Codag
provider_slug: codag
slug: codag-privacy-policy
source_date: '2026-11-09'
source_filename: codag-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codag.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Codag\naid: codag\nurl: https://codag.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data. Name, email, organization.\n- category: behavioral\n  text: Eligible tool output, transiently. Large eligible tool results (logs, test and build output, search results,\n    file listings, document reads, agent handoffs) plus minimal task context are processed to produce the reduced\n    evidence and are not retained.\n- category: device\n  text: Contentless usage metrics. Byte and token counts, estimated costs, latency, reduce\
  \ or passthrough decisions,\n    fail-open reasons, retry and retrieval counters, client versions, plan and billing events.\n- category: financial\n  text: Stripe. Payment processing and subscription management. Handles card data; we do not store full card numbers.\npurposes:\n- purpose: Authenticate and bill\n  text: Used to authenticate and bill.\n- purpose: Return reduced evidence\n  text: Process eligible tool output transiently to return the reduced evidence.\n- purpose: Meter usage and report savings\n  text: Meter usage, bill plans, and report savings using the contentless metrics described above.\n- purpose: Aggregate reliability and cost diagnostics\n  text: Aggregate reliability and cost metrics to diagnose issues, prevent abuse, plan capacity, and guide product\n    decisions.\nretention:\n- scope: Contentless metrics, account data, billing records\n  period: while your account is active\n  text: Contentless metrics, account data, and billing records are retained while your\
  \ account is active.\n- scope: Account deletion\n  period: 30 days\n  text: If you delete your account or request deletion in writing, we purge all per-customer data within 30 days.\n- scope: Local encrypted cache\n  period: seven days\n  text: The local encrypted cache on your machine expires on its own after seven days and is yours to delete at\n    any time.\n- scope: Customer content processed for reduction\n  period: null\n  text: Customer content is processed only on inference endpoints Codag controls and is not retained after the request\n    completes.\nresidency:\n- region: United States\n  text: Account data and contentless metrics are stored in an encrypted PostgreSQL database hosted on US-based cloud\n    infrastructure.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Google OAuth. Console sign-in. We receive name and email from your Google account. Stripe. Payment processing\n    and subscription management. Handles card data; we do not store full card numbers. Modal.\
  \ Managed infrastructure\n    for Codag-controlled inference. Railway. US-based cloud hosting for the API and database. Vercel. Hosting for\n    the web console. Resend. Transactional email delivery (such as organization invites). PostHog. Product analytics,\n    website analytics, feature usage, and opt-out state for non-essential analytics.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request full deletion of all per-customer data by emailing [email protected]\n  text: Request full deletion of all per-customer data by emailing [email protected] . We honor requests within\n    30 days.\nrights:\n- right: Access, correct, or delete account data\n  text: Access, correct, or delete your account data.\n- right: Export usage records\n  text: Export your usage records.\n- right: GDPR rights\n  text: EU and UK residents have additional rights under GDPR; California residents have additional rights under\n    CPRA.\nsale_or_sharing:\n  stance: prohibited\n  text: We\
  \ do not sell or rent your data.\n"
source_yaml_url: https://artifacts.apis.io/codag/privacy/codag-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Codag's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Logging
- Observability
- Log Compression
- AI Agents
- MCP
- LLM Tooling
- Debugging
- Y Combinator
---
