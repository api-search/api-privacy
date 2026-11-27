---
api_specs:
- filename: konbiniapi-instagram-api-openapi.yml
  format: yaml
  label: KonbiniAPI Instagram API
  slug: konbiniapi-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-instagram-api-openapi.yml
- filename: konbiniapi-tiktok-api-openapi.yml
  format: yaml
  label: KonbiniAPI TikTok API
  slug: konbiniapi-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-tiktok-api-openapi.yml
- filename: konbiniapi-x-api-openapi.yml
  format: yaml
  label: KonbiniAPI X API
  slug: konbiniapi-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-x-api-openapi.yml
- filename: konbiniapi-reddit-api-openapi.yml
  format: yaml
  label: KonbiniAPI Reddit API
  slug: konbiniapi-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-reddit-api-openapi.yml
- filename: konbiniapi-linked-in-api-openapi.yml
  format: yaml
  label: KonbiniAPI Linked In API
  slug: konbiniapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konbiniapi/openapi/konbiniapi-linked-in-api-openapi.yml
claim_count: 34
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address and a hashed version of your password. You may optionally provide your name.
  - category: financial
    text: We do store your Stripe customer ID and records of transactions (plan, amount, date) for billing and accounting purposes.
  - category: device
    text: we log the endpoint called, the timestamp, HTTP status code, response time, and the number of credits consumed. We also record the IP address the request originated from.
  - category: behavioral
    text: we may collect standard web information such as pages visited, browser type and version, and the referring URL.
  - category: identifying
    source: https://konbiniapi.com/dpa
    text: publicly displayed profile information (names, usernames, profile photos, bios)
  - category: behavioral
    source: https://konbiniapi.com/dpa
    text: public posts, comments, and public engagement metadata (likes, view counts) associated with social media accounts
  deletion:
    route: Delete account
    text: If you delete your account, we will remove your personal data within 30 days.
  dpa:
    available: true
    source: https://konbiniapi.com/dpa
    text: Controllers that require a separately countersigned copy for their own records may request one at hello@konbiniapi.com .
    url: https://konbiniapi.com/dpa
  purposes:
  - purpose: Provide and improve service
    text: Provide, maintain, and improve the KonbiniAPI service
  - purpose: Process payments
    text: Process payments and manage your subscription through Stripe
  - purpose: Monitor usage and enforce limits
    text: Monitor API usage and enforce plan limits
  - purpose: Abuse and fraud prevention
    text: Detect abuse, prevent fraud, and address security threats
  - purpose: Transactional emails
    text: Send transactional emails related to your account, billing, and service updates
  - purpose: fulfill API requests
    source: https://konbiniapi.com/dpa
    text: process Personal Data only on documented instructions from Controller, namely to fulfill the API requests Controller initiates
  residency:
  - region: United States
    text: Data is stored on PostHog's US-based servers and transferred under Standard Contractual Clauses.
  - region: United States
    text: Supabase (database hosting on AWS, United States)
  retention:
  - period: 30 days
    scope: Account data
    text: If you delete your account, we will remove your personal data within 30 days.
  - period: 90 days
    scope: API usage logs
    text: 'API usage logs: Retained for 90 days for debugging and abuse detection purposes, then anonymized or deleted.'
  - period: 5 years
    scope: Payment records
    text: 'Payment records: Retained for a minimum of 5 years as required by Spanish tax law (Ley General Tributaria).'
  - period: 1 year
    scope: Website analytics
    text: 'Website analytics: Session-scoped data is retained for 1 year by PostHog.'
  - period: null
    scope: API response content
    source: https://konbiniapi.com/dpa
    text: Processor does not store, cache, or index the content of API responses beyond what is necessary to fulfill the individual request.
  rights:
  - right: Access
    text: Right of access — request a copy of the personal data we hold about you.
  - right: Rectification
    text: Right to rectification — ask us to correct any inaccurate or incomplete data.
  - right: Erasure
    text: Right to erasure — ask us to delete your personal data (“right to be forgotten”).
  - right: Restrict processing
    text: Right to restrict processing — ask us to temporarily stop processing your data in certain circumstances.
  - right: Portability
    text: Right to data portability — receive your data in a structured, commonly used, machine-readable format.
  - right: Object
    text: Right to object — object to processing based on legitimate interests.
  - right: Withdraw consent
    text: Right to withdraw consent — where processing is based on consent, you may withdraw it at any time
  - right: data subject request assistance
    source: https://konbiniapi.com/dpa
    text: provide reasonable assistance to Controller, taking into account the nature of the processing, in responding to data subject requests (access, rectification, erasure, restriction, portability, objection)
  role:
    text: KonbiniAPI (“we,” “us,” “our”) collects, uses, stores, and protects your personal data when you use our website at konbiniapi.com
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No data is shared with advertisers or third parties.
  subprocessors:
    source: https://konbiniapi.com/dpa
    text: Google Cloud Platform (Google LLC) — hosting and infrastructure for the API.
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are protected by Standard Contractual Clauses (SCCs) as approved by the European Commission
  - mechanism: SCC
    source: https://konbiniapi.com/dpa
    text: including the EU Standard Contractual Clauses (with Controller as data exporter and Processor, or the relevant Sub-processor, as data importer, as applicable)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: KonbiniAPI
provenance_date: '2026-11-09'
provider_name: KonbiniAPI
provider_slug: konbiniapi
slug: konbiniapi-privacy-policy
source_date: '2026-11-09'
source_filename: konbiniapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://konbiniapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: KonbiniAPI\naid: konbiniapi\nurl: https://konbiniapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://konbiniapi.com/dpa\n  - https://konbiniapi.com/privacy\nrole:\n  value: controller\n  text: KonbiniAPI (“we,” “us,” “our”) collects, uses, stores, and protects your personal data when you use our\n    website at konbiniapi.com\ndata_categories:\n- category: identifying\n  text: we collect your email address and a hashed version of your password. You may optionally provide your name.\n- category: financial\n  text: We do store your Stripe customer ID and records of transactions (plan, amount,\
  \ date) for billing and accounting\n    purposes.\n- category: device\n  text: we log the endpoint called, the timestamp, HTTP status code, response time, and the number of credits consumed.\n    We also record the IP address the request originated from.\n- category: behavioral\n  text: we may collect standard web information such as pages visited, browser type and version, and the referring\n    URL.\n- category: identifying\n  text: publicly displayed profile information (names, usernames, profile photos, bios)\n  source: https://konbiniapi.com/dpa\n- category: behavioral\n  text: public posts, comments, and public engagement metadata (likes, view counts) associated with social media\n    accounts\n  source: https://konbiniapi.com/dpa\npurposes:\n- purpose: Provide and improve service\n  text: Provide, maintain, and improve the KonbiniAPI service\n- purpose: Process payments\n  text: Process payments and manage your subscription through Stripe\n- purpose: Monitor usage and enforce limits\n\
  \  text: Monitor API usage and enforce plan limits\n- purpose: Abuse and fraud prevention\n  text: Detect abuse, prevent fraud, and address security threats\n- purpose: Transactional emails\n  text: Send transactional emails related to your account, billing, and service updates\n- purpose: fulfill API requests\n  text: process Personal Data only on documented instructions from Controller, namely to fulfill the API requests\n    Controller initiates\n  source: https://konbiniapi.com/dpa\nretention:\n- scope: Account data\n  period: 30 days\n  text: If you delete your account, we will remove your personal data within 30 days.\n- scope: API usage logs\n  period: 90 days\n  text: 'API usage logs: Retained for 90 days for debugging and abuse detection purposes, then anonymized or deleted.'\n- scope: Payment records\n  period: 5 years\n  text: 'Payment records: Retained for a minimum of 5 years as required by Spanish tax law (Ley General Tributaria).'\n- scope: Website analytics\n  period: 1\
  \ year\n  text: 'Website analytics: Session-scoped data is retained for 1 year by PostHog.'\n- scope: API response content\n  period: null\n  text: Processor does not store, cache, or index the content of API responses beyond what is necessary to fulfill\n    the individual request.\n  source: https://konbiniapi.com/dpa\nresidency:\n- region: United States\n  text: Data is stored on PostHog's US-based servers and transferred under Standard Contractual Clauses.\n- region: United States\n  text: Supabase (database hosting on AWS, United States)\ntransfers:\n- mechanism: SCC\n  text: These transfers are protected by Standard Contractual Clauses (SCCs) as approved by the European Commission\n- mechanism: SCC\n  text: including the EU Standard Contractual Clauses (with Controller as data exporter and Processor, or the relevant\n    Sub-processor, as data importer, as applicable)\n  source: https://konbiniapi.com/dpa\nsubprocessors:\n  url: null\n  text: Google Cloud Platform (Google LLC) —\
  \ hosting and infrastructure for the API.\n  source: https://konbiniapi.com/dpa\ndpa:\n  available: true\n  url: https://konbiniapi.com/dpa\n  text: Controllers that require a separately countersigned copy for their own records may request one at hello@konbiniapi.com\n    .\n  source: https://konbiniapi.com/dpa\ndeletion:\n  route: Delete account\n  text: If you delete your account, we will remove your personal data within 30 days.\nrights:\n- right: Access\n  text: Right of access — request a copy of the personal data we hold about you.\n- right: Rectification\n  text: Right to rectification — ask us to correct any inaccurate or incomplete data.\n- right: Erasure\n  text: Right to erasure — ask us to delete your personal data (“right to be forgotten”).\n- right: Restrict processing\n  text: Right to restrict processing — ask us to temporarily stop processing your data in certain circumstances.\n- right: Portability\n  text: Right to data portability — receive your data in a structured,\
  \ commonly used, machine-readable format.\n- right: Object\n  text: Right to object — object to processing based on legitimate interests.\n- right: Withdraw consent\n  text: Right to withdraw consent — where processing is based on consent, you may withdraw it at any time\n- right: data subject request assistance\n  text: provide reasonable assistance to Controller, taking into account the nature of the processing, in responding\n    to data subject requests (access, rectification, erasure, restriction, portability, objection)\n  source: https://konbiniapi.com/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: No data is shared with advertisers or third parties.\n"
source_yaml_url: https://artifacts.apis.io/konbiniapi/privacy/konbiniapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 34 quoted statements, read from KonbiniAPI's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Instagram
- TikTok
- X
- Reddit
- LinkedIn
- ActivityStreams 2.0
- Web Scraping
- Data Extraction
- Public Data
- Influencer Marketing
- Social Listening
- Creator Tools
- MCP
- Agent Skills
- Agents
- A2A
---
