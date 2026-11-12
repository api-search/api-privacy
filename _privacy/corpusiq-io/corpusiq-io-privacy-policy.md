---
api_specs:
- filename: corpusiq-io-authentication-api-openapi.yml
  format: yaml
  label: CorpusIQ Authentication API
  slug: corpusiq-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-authentication-api-openapi.yml
- filename: corpusiq-io-discovery-api-openapi.yml
  format: yaml
  label: CorpusIQ Discovery API
  slug: corpusiq-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-discovery-api-openapi.yml
- filename: corpusiq-io-mcp-api-openapi.yml
  format: yaml
  label: CorpusIQ MCP API
  slug: corpusiq-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-mcp-api-openapi.yml
- filename: corpusiq-io-usage-api-openapi.yml
  format: yaml
  label: CorpusIQ Usage API
  slug: corpusiq-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corpusiq-io/openapi/corpusiq-io-usage-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name, and password hash when you register.
  - category: other
    text: Read-only access tokens for the third-party services you connect (e.g., Gmail, Shopify, SHOPLINE, QuickBooks).
  - category: communication
    text: Local AUDIT logs record raw query text and tool parameters plus bounded result summaries.
  - category: device
    text: Request timestamps, connector types used, and feature flags.
  - category: financial
    text: 'Payment data: Processed by Stripe. We do not store card numbers or full payment details.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and account protection
    text: To authenticate your identity and protect your account.
  - purpose: Connecting to third-party services
    text: To connect to third-party services on your behalf using OAuth.
  - purpose: Answering queries
    text: To answer your queries by retrieving authorized records live from your connected sources.
  - purpose: Billing and support
    text: To provide billing, usage reporting, and support.
  - purpose: Legal compliance
    text: To comply with legal obligations.
  retention:
  - period: while your account is active
    scope: Account data, encrypted OAuth tokens, aggregate usage records
    text: Account data, encrypted OAuth tokens, and aggregate usage records are retained while your account is active.
  - period: 30 days
    scope: Operational logs in Azure Log Analytics
    text: Operational logs in the Azure Log Analytics workspace are retained for 30 days.
  - period: until connector revocation or account deletion
    scope: Optional indexed-search metadata
    text: Optional indexed-search metadata remains until connector revocation or account deletion.
  rights:
  - right: Access
    text: Access a copy of the data we hold about you.
  - right: Correction
    text: Correct inaccurate data.
  - right: Deletion
    text: Request deletion of account data by emailing privacy@corpusiq.io.
  - right: Revoke OAuth access
    text: Revoke OAuth access to any connected service at any time from the Connectors dashboard.
  - right: Portability
    text: Port your data in a machine-readable format.
  - right: Complaint
    text: Lodge a complaint with your local data protection authority (GDPR users).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your data with third parties for advertising.
  subprocessors:
    text: 'We share data only with service providers required to operate CorpusIQ: Microsoft Azure (infrastructure), Stripe (payments), and Supabase (authentication).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CorpusIQ
provenance_date: '2026-11-09'
provider_name: CorpusIQ
provider_slug: corpusiq-io
slug: corpusiq-io-privacy-policy
source_date: '2026-11-09'
source_filename: corpusiq-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.corpusiq.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CorpusIQ\naid: corpusiq-io\nurl: https://www.corpusiq.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, name, and password hash when you register.\n- category: other\n  text: Read-only access tokens for the third-party services you connect (e.g., Gmail, Shopify, SHOPLINE, QuickBooks).\n- category: communication\n  text: Local AUDIT logs record raw query text and tool parameters plus bounded result summaries.\n- category: device\n  text: Request timestamps, connector types used, and feature flags.\n- category: financial\n\
  \  text: 'Payment data: Processed by Stripe. We do not store card numbers or full payment details.'\npurposes:\n- purpose: Authentication and account protection\n  text: To authenticate your identity and protect your account.\n- purpose: Connecting to third-party services\n  text: To connect to third-party services on your behalf using OAuth.\n- purpose: Answering queries\n  text: To answer your queries by retrieving authorized records live from your connected sources.\n- purpose: Billing and support\n  text: To provide billing, usage reporting, and support.\n- purpose: Legal compliance\n  text: To comply with legal obligations.\nretention:\n- scope: Account data, encrypted OAuth tokens, aggregate usage records\n  period: while your account is active\n  text: Account data, encrypted OAuth tokens, and aggregate usage records are retained while your account is active.\n- scope: Operational logs in Azure Log Analytics\n  period: 30 days\n  text: Operational logs in the Azure Log Analytics\
  \ workspace are retained for 30 days.\n- scope: Optional indexed-search metadata\n  period: until connector revocation or account deletion\n  text: Optional indexed-search metadata remains until connector revocation or account deletion.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data only with service providers required to operate CorpusIQ: Microsoft Azure (infrastructure),\n    Stripe (payments), and Supabase (authentication).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Access a copy of the data we hold about you.\n- right: Correction\n  text: Correct inaccurate data.\n- right: Deletion\n  text: Request deletion of account data by emailing privacy@corpusiq.io.\n- right: Revoke OAuth access\n  text: Revoke OAuth access to any connected service at any time from the Connectors dashboard.\n- right: Portability\n  text: Port your data in a machine-readable format.\n- right:\
  \ Complaint\n  text: Lodge a complaint with your local data protection authority (GDPR users).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your data with third parties for advertising.\n"
source_yaml_url: https://artifacts.apis.io/corpusiq-io/privacy/corpusiq-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from CorpusIQ's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Business Intelligence
- Small Business
- Integrations
- ChatGPT
- Analytics
---
