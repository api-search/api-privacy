---
api_specs:
- filename: drillr-analyst-api-openapi.yml
  format: yaml
  label: drillr Public Data API Analyst API
  slug: drillr-analyst-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-analyst-api-openapi.yml
- filename: drillr-company-api-openapi.yml
  format: yaml
  label: drillr Public Data API Company API
  slug: drillr-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-company-api-openapi.yml
- filename: drillr-contract-api-openapi.yml
  format: yaml
  label: drillr Public Data API Contract API
  slug: drillr-contract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-contract-api-openapi.yml
- filename: drillr-earnings-api-openapi.yml
  format: yaml
  label: drillr Public Data API Earnings API
  slug: drillr-earnings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-earnings-api-openapi.yml
- filename: drillr-events-api-openapi.yml
  format: yaml
  label: drillr Public Data API Events API
  slug: drillr-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-events-api-openapi.yml
- filename: drillr-executives-api-openapi.yml
  format: yaml
  label: drillr Public Data API Executives API
  slug: drillr-executives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-executives-api-openapi.yml
- filename: drillr-filings-api-openapi.yml
  format: yaml
  label: drillr Public Data API Filings API
  slug: drillr-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-filings-api-openapi.yml
- filename: drillr-financials-api-openapi.yml
  format: yaml
  label: drillr Public Data API Financials API
  slug: drillr-financials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-financials-api-openapi.yml
- filename: drillr-ownership-api-openapi.yml
  format: yaml
  label: drillr Public Data API Ownership API
  slug: drillr-ownership-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-ownership-api-openapi.yml
- filename: drillr-prices-api-openapi.yml
  format: yaml
  label: drillr Public Data API Prices API
  slug: drillr-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-prices-api-openapi.yml
- filename: drillr-signal-api-openapi.yml
  format: yaml
  label: drillr Public Data API Signal API
  slug: drillr-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drillr/openapi/drillr-signal-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email, password hash, name (if provided), organization (if provided)'
  - category: financial
    text: 'Commercial: billing address, tax info, payment method (processed by third-party processors)'
  - category: device
    text: 'Technical: IP address, User-Agent, device type, browser, OS, timezone'
  - category: behavioral
    text: 'Usage data: queries you submit, API endpoints called, call frequency, summaries of returned outputs, error logs'
  - category: communication
    text: Support communications you send to support@lil-grebe.com or legal@lil-grebe.com
  deletion:
    route: Contact privacy@lil-grebe.com
    text: 'Delete : request deletion of your account and data, subject to legal obligations'
  dpa:
    available: null
    text: 'Service providers : hosting (AWS, Vercel, Cloudflare), payment processing (Stripe, etc.), email service, customer support tools, product analytics — all under data processing agreements'
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: 'Provide and maintain the Service : account management, authentication, quota enforcement, billing, customer support'
  - purpose: Improve the Service
    text: 'Improve the Service : usage analytics, debugging, product research, model quality evaluation (see Section 3)'
  - purpose: Security
    text: 'Security : abuse monitoring, fraud prevention, account moderation, vendor compliance audits'
  - purpose: Compliance
    text: 'Compliance : legal obligations, response to valid government or judicial requests'
  residency:
  - region: United States
    text: Data is primarily stored in the United States (AWS / Vercel U.S. regions)
  retention:
  - period: 30-day grace period after deletion
    scope: Account data
    text: 'Account data: for the life of your account + 30-day grace period after deletion'
  - period: 12 months
    scope: Usage logs
    text: 'Usage logs (for security and billing): 12 months'
  - period: null
    scope: Billing and tax records
    text: 'Billing and tax records: minimum period required by law (typically 7 years)'
  - period: 90 days
    scope: Backups
    text: 'Backups: rolling daily backups, up to 90 days'
  - period: 12 months
    scope: Usage analytics
    text: 'Retention : 12 months, after which the underlying rows are permanently deleted (monthly partition rotation).'
  rights:
  - right: Access and export
    text: 'Access and export : receive a copy of personal information we hold about you'
  - right: Correct
    text: 'Correct : correct inaccurate information'
  - right: Delete
    text: 'Delete : request deletion of your account and data, subject to legal obligations'
  - right: Object
    text: 'Object : object to processing based on legitimate interests'
  - right: Data portability
    text: 'Data portability : receive your data in a machine-readable format'
  - right: Withdraw consent
    text: 'Withdraw consent : at any time (does not affect prior lawful processing)'
  role:
    text: This Privacy Policy explains how LIL GREBE INC. ("drillr," "we") collects, uses, shares, and protects your personal information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information (as "sale" or "share" is defined under CCPA).
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: If you are located in the European Economic Area, the U.K., or Switzerland, your data will be transferred to the U.S. in reliance on Standard Contractual Clauses (SCCs) and equivalent safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: drillr
provenance_date: '2026-11-09'
provider_name: drillr
provider_slug: drillr
slug: drillr-privacy-policy
source_date: '2026-11-09'
source_filename: drillr-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://drillr.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: drillr\naid: drillr\nurl: https://drillr.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy explains how LIL GREBE INC. (\"drillr,\" \"we\") collects, uses, shares, and protects your\n    personal information.\ndata_categories:\n- category: identifying\n  text: 'Account: email, password hash, name (if provided), organization (if provided)'\n- category: financial\n  text: 'Commercial: billing address, tax info, payment method (processed by third-party processors)'\n- category: device\n  text: 'Technical: IP address, User-Agent, device type, browser, OS, timezone'\n\
  - category: behavioral\n  text: 'Usage data: queries you submit, API endpoints called, call frequency, summaries of returned outputs, error\n    logs'\n- category: communication\n  text: Support communications you send to support@lil-grebe.com or legal@lil-grebe.com\npurposes:\n- purpose: Provide and maintain the Service\n  text: 'Provide and maintain the Service : account management, authentication, quota enforcement, billing, customer\n    support'\n- purpose: Improve the Service\n  text: 'Improve the Service : usage analytics, debugging, product research, model quality evaluation (see Section\n    3)'\n- purpose: Security\n  text: 'Security : abuse monitoring, fraud prevention, account moderation, vendor compliance audits'\n- purpose: Compliance\n  text: 'Compliance : legal obligations, response to valid government or judicial requests'\nretention:\n- scope: Account data\n  period: 30-day grace period after deletion\n  text: 'Account data: for the life of your account + 30-day grace\
  \ period after deletion'\n- scope: Usage logs\n  period: 12 months\n  text: 'Usage logs (for security and billing): 12 months'\n- scope: Billing and tax records\n  period: null\n  text: 'Billing and tax records: minimum period required by law (typically 7 years)'\n- scope: Backups\n  period: 90 days\n  text: 'Backups: rolling daily backups, up to 90 days'\n- scope: Usage analytics\n  period: 12 months\n  text: 'Retention : 12 months, after which the underlying rows are permanently deleted (monthly partition rotation).'\nresidency:\n- region: United States\n  text: Data is primarily stored in the United States (AWS / Vercel U.S. regions)\ntransfers:\n- mechanism: SCC\n  text: If you are located in the European Economic Area, the U.K., or Switzerland, your data will be transferred\n    to the U.S. in reliance on Standard Contractual Clauses (SCCs) and equivalent safeguards\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: 'Service providers : hosting\
  \ (AWS, Vercel, Cloudflare), payment processing (Stripe, etc.), email service,\n    customer support tools, product analytics — all under data processing agreements'\ndeletion:\n  route: Contact privacy@lil-grebe.com\n  text: 'Delete : request deletion of your account and data, subject to legal obligations'\nrights:\n- right: Access and export\n  text: 'Access and export : receive a copy of personal information we hold about you'\n- right: Correct\n  text: 'Correct : correct inaccurate information'\n- right: Delete\n  text: 'Delete : request deletion of your account and data, subject to legal obligations'\n- right: Object\n  text: 'Object : object to processing based on legitimate interests'\n- right: Data portability\n  text: 'Data portability : receive your data in a machine-readable format'\n- right: Withdraw consent\n  text: 'Withdraw consent : at any time (does not affect prior lawful processing)'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information\
  \ (as \"sale\" or \"share\" is defined under CCPA).\n"
source_yaml_url: https://artifacts.apis.io/drillr/privacy/drillr-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from drillr's own page on 2026-11-09.
synthetic: false
tags:
- Financial Data
- Stocks
- SEC Filings
- Fundamentals
- Earnings
- Ownership
- Corporate Events
- Analyst Ratings
- news-signals
- MCP
- Agent-Native
---
