---
api_specs:
- filename: ctxstore-ai-account-api-openapi.yml
  format: yaml
  label: ctxstore.ai Account API
  slug: ctxstore-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-account-api-openapi.yml
- filename: ctxstore-ai-admin-api-openapi.yml
  format: yaml
  label: ctxstore.ai Admin API
  slug: ctxstore-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-admin-api-openapi.yml
- filename: ctxstore-ai-context-api-openapi.yml
  format: yaml
  label: ctxstore.ai Context API
  slug: ctxstore-ai-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-context-api-openapi.yml
- filename: ctxstore-ai-events-api-openapi.yml
  format: yaml
  label: ctxstore.ai Events API
  slug: ctxstore-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-events-api-openapi.yml
- filename: ctxstore-ai-facts-api-openapi.yml
  format: yaml
  label: ctxstore.ai Facts API
  slug: ctxstore-ai-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-facts-api-openapi.yml
- filename: ctxstore-ai-openapi-json-api-openapi.yml
  format: yaml
  label: ctxstore.ai Openapi.json API
  slug: ctxstore-ai-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-openapi-json-api-openapi.yml
- filename: ctxstore-ai-search-api-openapi.yml
  format: yaml
  label: ctxstore.ai Search API
  slug: ctxstore-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-search-api-openapi.yml
- filename: ctxstore-ai-stats-api-openapi.yml
  format: yaml
  label: ctxstore.ai Stats API
  slug: ctxstore-ai-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-stats-api-openapi.yml
- filename: ctxstore-ai-users-api-openapi.yml
  format: yaml
  label: ctxstore.ai Users API
  slug: ctxstore-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ctxstore-ai/openapi/ctxstore-ai-users-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address (optional — only if you link an account for multi-device access).
  - category: behavioral
    text: 'Usage data: Number of facts stored, queries made, API calls, timestamps of activity, and your plan tier.'
  - category: other
    text: 'Stored content: Facts, contexts, and memories you store through the service.'
  - category: financial
    text: 'Billing information: Payment details are processed by Stripe and never stored on our servers.'
  - category: device
    text: 'Technical data: IP address, client identifier, platform information (sent during provisioning), and session identifiers.'
  deletion:
    route: Email request
    text: You can request immediate deletion by emailing [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide and operate the ctxstore.ai service
  - purpose: Process payments
    text: Process payments and manage subscriptions via Stripe
  - purpose: Enforce usage limits
    text: Enforce usage limits and manage your plan tier
  - purpose: Transactional emails
    text: Send transactional emails (account setup, billing receipts) via Resend
  - purpose: Prevent abuse and security
    text: Prevent abuse and maintain service security
  - purpose: Support requests
    text: Respond to support requests
  residency:
  - region: United States (Virginia)
    text: Data is stored on servers in the United States (Virginia).
  retention:
  - period: 30 days
    scope: Stored facts and memories after cancellation or deletion request
    text: Your stored facts and memories are deleted within 30 days.
  - period: 7 years
    scope: Billing records
    text: Billing records are retained for 7 years as required by law.
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data ("right to be forgotten")
  - right: Portability
    text: Export your data in a portable format
  - right: Opt out of processing
    text: Opt out of certain data processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal data to any third party.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ctxstore.ai
provenance_date: '2026-11-09'
provider_name: ctxstore.ai
provider_slug: ctxstore-ai
slug: ctxstore-ai-privacy-policy
source_date: '2026-11-09'
source_filename: ctxstore-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ctxstore.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ctxstore.ai\naid: ctxstore-ai\nurl: https://ctxstore.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address (optional — only if you link an account for multi-device access).\n- category: behavioral\n  text: 'Usage data: Number of facts stored, queries made, API calls, timestamps of activity, and your plan tier.'\n- category: other\n  text: 'Stored content: Facts, contexts, and memories you store through the service.'\n- category: financial\n  text: 'Billing information: Payment details are processed by Stripe and never\
  \ stored on our servers.'\n- category: device\n  text: 'Technical data: IP address, client identifier, platform information (sent during provisioning), and session\n    identifiers.'\npurposes:\n- purpose: Provide and operate the service\n  text: Provide and operate the ctxstore.ai service\n- purpose: Process payments\n  text: Process payments and manage subscriptions via Stripe\n- purpose: Enforce usage limits\n  text: Enforce usage limits and manage your plan tier\n- purpose: Transactional emails\n  text: Send transactional emails (account setup, billing receipts) via Resend\n- purpose: Prevent abuse and security\n  text: Prevent abuse and maintain service security\n- purpose: Support requests\n  text: Respond to support requests\nretention:\n- scope: Stored facts and memories after cancellation or deletion request\n  period: 30 days\n  text: Your stored facts and memories are deleted within 30 days.\n- scope: Billing records\n  period: 7 years\n  text: Billing records are retained for\
  \ 7 years as required by law.\nresidency:\n- region: United States (Virginia)\n  text: Data is stored on servers in the United States (Virginia).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request\n  text: You can request immediate deletion by emailing [email protected] .\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data (\"right to be forgotten\")\n- right: Portability\n  text: Export your data in a portable format\n- right: Opt out of processing\n  text: Opt out of certain data processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal data to any third party.\n"
source_yaml_url: https://artifacts.apis.io/ctxstore-ai/privacy/ctxstore-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from ctxstore.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Memory
- MCP
- Context Management
- Developer Tools
---
