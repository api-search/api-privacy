---
api_specs:
- filename: agent-ready-dev-mcp-api-openapi.yml
  format: yaml
  label: Agent Ready MCP API
  slug: agent-ready-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-ready-dev/openapi/agent-ready-dev-mcp-api-openapi.yml
- filename: agent-ready-dev-nlweb-api-openapi.yml
  format: yaml
  label: Agent Ready NL Web API
  slug: agent-ready-dev-nlweb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-ready-dev/openapi/agent-ready-dev-nlweb-api-openapi.yml
- filename: agent-ready-dev-scans-api-openapi.yml
  format: yaml
  label: Agent Ready Scans API
  slug: agent-ready-dev-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent-ready-dev/openapi/agent-ready-dev-scans-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address, and optionally a name, provided via our authentication provider (Clerk)
  - category: financial
    text: We store a Stripe customer identifier and subscription identifier so we can link your account to your subscription.
  - category: behavioral
    text: the URLs you ask us to scan, the resulting scores and check outputs, and limited snippets of public page content
  - category: location
    text: your IP address (used transiently for rate-limiting and abuse prevention)
  - category: device
    text: standard request headers
  - category: other
    text: when the service encounters an unexpected error, we capture the stack trace and request path through Sentry
  deletion:
    route: Delete your account in Clerk or on the service; data is purged automatically
    text: You can trigger this yourself by deleting your account in Clerk; we automatically receive a deletion event and purge your data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: 'running scans, displaying results, sending regression alerts (legal basis: contract performance)'
  - purpose: take payment
    text: 'managing subscriptions and invoices through Stripe (legal basis: contract performance)'
  - purpose: keep the service running safely
    text: 'rate limiting, blocking abuse, debugging errors (legal basis: legitimate interests in service security and integrity)'
  retention:
  - period: null
    scope: account data
    text: for as long as you have an account. Deleted when you delete your account.
  - period: indefinitely
    scope: scan results
    text: Scan results - kept indefinitely so share links remain valid.
  - period: null
    scope: monitoring records
    text: deleted when you remove the site or delete your account.
  - period: maximum 30 days
    scope: rate-limit counters
    text: Rate-limit counters — maximum 30 days.
  - period: 6–7 years
    scope: billing records
    text: Billing records — retained by Stripe for the period required by tax law (typically 6–7 years).
  - period: up to 90 days
    scope: error reports
    text: Error reports — retained by Sentry for up to 90 days.
  rights:
  - right: access
    text: Access the personal data we hold about you.
  - right: rectification
    text: Correct anything that’s wrong.
  - right: erasure
    text: Delete your account and associated personal data (right to erasure).
  - right: portability
    text: Export your data in a portable format.
  - right: objection
    text: Object to certain processing (such as regression alerts).
  - right: complaint
    text: Lodge a complaint with your data protection regulator (the UK ICO, or your local EEA regulator).
  role:
    text: The data controller for the purposes of UK GDPR / EU GDPR is the operator of the service
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Transfers are covered by the UK International Data Transfer Agreement, EU Standard Contractual Clauses, or equivalent safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Ready
provenance_date: '2026-11-09'
provider_name: Agent Ready
provider_slug: agent-ready-dev
slug: agent-ready-dev-privacy-policy
source_date: '2026-11-09'
source_filename: agent-ready-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agent-ready.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Ready\naid: agent-ready-dev\nurl: https://agent-ready.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for the purposes of UK GDPR / EU GDPR is the operator of the service\ndata_categories:\n- category: contact\n  text: your email address, and optionally a name, provided via our authentication provider (Clerk)\n- category: financial\n  text: We store a Stripe customer identifier and subscription identifier so we can link your account to your subscription.\n- category: behavioral\n  text: the URLs you ask us to scan, the resulting scores and check outputs,\
  \ and limited snippets of public page\n    content\n- category: location\n  text: your IP address (used transiently for rate-limiting and abuse prevention)\n- category: device\n  text: standard request headers\n- category: other\n  text: when the service encounters an unexpected error, we capture the stack trace and request path through Sentry\npurposes:\n- purpose: provide the service\n  text: 'running scans, displaying results, sending regression alerts (legal basis: contract performance)'\n- purpose: take payment\n  text: 'managing subscriptions and invoices through Stripe (legal basis: contract performance)'\n- purpose: keep the service running safely\n  text: 'rate limiting, blocking abuse, debugging errors (legal basis: legitimate interests in service security\n    and integrity)'\nretention:\n- scope: account data\n  period: null\n  text: for as long as you have an account. Deleted when you delete your account.\n- scope: scan results\n  period: indefinitely\n  text: Scan results\
  \ - kept indefinitely so share links remain valid.\n- scope: monitoring records\n  period: null\n  text: deleted when you remove the site or delete your account.\n- scope: rate-limit counters\n  period: maximum 30 days\n  text: Rate-limit counters — maximum 30 days.\n- scope: billing records\n  period: 6–7 years\n  text: Billing records — retained by Stripe for the period required by tax law (typically 6–7 years).\n- scope: error reports\n  period: up to 90 days\n  text: Error reports — retained by Sentry for up to 90 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Transfers are covered by the UK International Data Transfer Agreement, EU Standard Contractual Clauses,\n    or equivalent safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account in Clerk or on the service; data is purged automatically\n  text: You can trigger this yourself by deleting your account in Clerk; we automatically\
  \ receive a deletion event\n    and purge your data.\nrights:\n- right: access\n  text: Access the personal data we hold about you.\n- right: rectification\n  text: Correct anything that’s wrong.\n- right: erasure\n  text: Delete your account and associated personal data (right to erasure).\n- right: portability\n  text: Export your data in a portable format.\n- right: objection\n  text: Object to certain processing (such as regression alerts).\n- right: complaint\n  text: Lodge a complaint with your data protection regulator (the UK ICO, or your local EEA regulator).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/agent-ready-dev/privacy/agent-ready-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Agent Ready's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Agent Readiness
- Website Scanning
- Developer Tools
- MCP
- A2A
- Llms.txt
- x402
- NLWeb
- Accessibility
- Agent-Native
- Australia
---
