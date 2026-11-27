---
api_specs:
- filename: indexed-vc-companies-api-openapi.yml
  format: yaml
  label: Indexed Companies API
  slug: indexed-vc-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-companies-api-openapi.yml
- filename: indexed-vc-enrich-api-openapi.yml
  format: yaml
  label: Indexed Enrich API
  slug: indexed-vc-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-enrich-api-openapi.yml
- filename: indexed-vc-industries-api-openapi.yml
  format: yaml
  label: Indexed Industries API
  slug: indexed-vc-industries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-industries-api-openapi.yml
- filename: indexed-vc-investors-api-openapi.yml
  format: yaml
  label: Indexed Investors API
  slug: indexed-vc-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-investors-api-openapi.yml
- filename: indexed-vc-reveal-api-openapi.yml
  format: yaml
  label: Indexed Reveal API
  slug: indexed-vc-reveal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-reveal-api-openapi.yml
- filename: indexed-vc-scheduled-exports-api-openapi.yml
  format: yaml
  label: Indexed Scheduled Exports API
  slug: indexed-vc-scheduled-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-scheduled-exports-api-openapi.yml
- filename: indexed-vc-usage-api-openapi.yml
  format: yaml
  label: Indexed Usage API
  slug: indexed-vc-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-usage-api-openapi.yml
- filename: indexed-vc-webhooks-api-openapi.yml
  format: yaml
  label: Indexed Webhooks API
  slug: indexed-vc-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/indexed-vc/openapi/indexed-vc-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect your email address and, if you use Google OAuth, your name and profile information provided by Google
  - category: behavioral
    text: We track your usage of the Service — including searches performed, company profiles viewed, list builder queries, and exports made
  - category: financial
    text: We store only a Stripe customer ID and subscription status; we do not store your full credit card number or banking details.
  - category: device
    text: server log data including IP addresses, browser type and version, operating system, device type, referring URLs, pages visited, and timestamps
  - category: location
    text: Your IP address may be used to derive approximate geographic location (city/country level).
  deletion:
    route: Contact hello@indexed.vc
    text: After account deletion, we will delete your personal data within 30 days, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, maintain, and improve the Service
    text: Provide, operate, maintain, and improve the Service
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions
  - purpose: Send transactional emails
    text: Send transactional emails (receipts, password resets, subscription notices)
  - purpose: Detect and prevent fraud and abuse
    text: Detect, investigate, and prevent fraud, abuse, or unauthorized access
  - purpose: Analyze usage trends
    text: Analyze usage trends to improve product features and user experience
  residency:
  - region: United States
    text: Your data is processed and stored in the United States through our infrastructure providers (Vercel, Supabase, Stripe).
  retention:
  - period: null
    scope: Account data
    text: We retain your account data for as long as your account is active.
  - period: 24 months
    scope: Usage logs
    text: Usage logs are retained for up to 24 months.
  - period: 30 days
    scope: Personal data after account deletion
    text: After account deletion, we will delete your personal data within 30 days, except where retention is required by law.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction: Request that we correct inaccurate or incomplete data'
  - right: Deletion
    text: 'Deletion: Request that we delete your personal data'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format'
  - right: Objection
    text: 'Objection: Object to certain types of processing of your data'
  - right: Opt out of sale (CCPA)
    text: Opt out of the sale of your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on our service providers' data protection frameworks and standard contractual clauses to ensure adequate protection of transferred data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Indexed
provenance_date: '2026-11-09'
provider_name: Indexed
provider_slug: indexed-vc
slug: indexed-vc-privacy-policy
source_date: '2026-11-09'
source_filename: indexed-vc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://indexed.vc/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Indexed\naid: indexed-vc\nurl: https://indexed.vc/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we collect your email address and, if you use Google OAuth, your name and profile information provided by\n    Google\n- category: behavioral\n  text: We track your usage of the Service — including searches performed, company profiles viewed, list builder\n    queries, and exports made\n- category: financial\n  text: We store only a Stripe customer ID and subscription status; we do not store your full credit card number\n    or banking\
  \ details.\n- category: device\n  text: server log data including IP addresses, browser type and version, operating system, device type, referring\n    URLs, pages visited, and timestamps\n- category: location\n  text: Your IP address may be used to derive approximate geographic location (city/country level).\npurposes:\n- purpose: Provide, operate, maintain, and improve the Service\n  text: Provide, operate, maintain, and improve the Service\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions\n- purpose: Send transactional emails\n  text: Send transactional emails (receipts, password resets, subscription notices)\n- purpose: Detect and prevent fraud and abuse\n  text: Detect, investigate, and prevent fraud, abuse, or unauthorized access\n- purpose: Analyze usage trends\n  text: Analyze usage trends to improve product features and user experience\nretention:\n- scope: Account data\n  period: null\n  text: We retain your account data\
  \ for as long as your account is active.\n- scope: Usage logs\n  period: 24 months\n  text: Usage logs are retained for up to 24 months.\n- scope: Personal data after account deletion\n  period: 30 days\n  text: After account deletion, we will delete your personal data within 30 days, except where retention is required\n    by law.\nresidency:\n- region: United States\n  text: Your data is processed and stored in the United States through our infrastructure providers (Vercel, Supabase,\n    Stripe).\ntransfers:\n- mechanism: SCC\n  text: We rely on our service providers' data protection frameworks and standard contractual clauses to ensure\n    adequate protection of transferred data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact hello@indexed.vc\n  text: After account deletion, we will delete your personal data within 30 days, except where retention is required\n    by law.\nrights:\n- right: Access\n  text:\
  \ 'Access: Request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction: Request that we correct inaccurate or incomplete data'\n- right: Deletion\n  text: 'Deletion: Request that we delete your personal data'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable format'\n- right: Objection\n  text: 'Objection: Object to certain types of processing of your data'\n- right: Opt out of sale (CCPA)\n  text: Opt out of the sale of your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/indexed-vc/privacy/indexed-vc-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Indexed's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Private Company
- Funding
---
