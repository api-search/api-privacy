---
api_specs:
- filename: pexafy-collections-api-openapi.yml
  format: yaml
  label: Pexafy Collections API
  slug: pexafy-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-collections-api-openapi.yml
- filename: pexafy-facets-api-openapi.yml
  format: yaml
  label: Pexafy Facets API
  slug: pexafy-facets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-facets-api-openapi.yml
- filename: pexafy-photos-api-openapi.yml
  format: yaml
  label: Pexafy Photos API
  slug: pexafy-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-photos-api-openapi.yml
- filename: pexafy-search-api-openapi.yml
  format: yaml
  label: Pexafy Search API
  slug: pexafy-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-search-api-openapi.yml
- filename: pexafy-usage-api-openapi.yml
  format: yaml
  label: Pexafy Usage API
  slug: pexafy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexafy/openapi/pexafy-usage-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — used for account creation, login, and communications
  - category: identifying
    text: Password — stored as a bcrypt hash (never in plaintext)
  - category: device
    text: IP address — used for security, abuse prevention and rate-limiting.
  - category: device
    text: User-Agent — browser/client information
  - category: behavioral
    text: Visitor cookie ( pxf_vid ) — a first-party identifier we set to recognise a returning browser and understand how people arrive at Pexafy.
  - category: communication
    text: Name, email, subject, and message when you contact us
  - category: financial
    text: Creem collects your payment and billing details (name, email, billing address, payment method) to charge you, issue your invoices and collect taxes
  deletion:
    route: Account deletion by the user
    text: Account data — retained until you delete your account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: Provide the Service — authenticate you, process API requests, manage your subscription
  - purpose: Security
    text: Security — detect abuse, enforce rate limits, prevent unauthorized access
  - purpose: Communications
    text: Communications — transactional emails (account-related, not marketing)
  - purpose: Analytics
    text: Analytics — anonymized, aggregated usage statistics to improve the Service
  - purpose: Legal obligations
    text: Legal obligations — comply with applicable law
  residency:
  - region: European Union
    text: Your data is stored within the European Union.
  retention:
  - period: until you delete your account
    scope: Account data
    text: Account data — retained until you delete your account
  - period: 90 days
    scope: API call log
    text: API call log, including the text of searches — 90 days
  - period: 60 days
    scope: Page requests
    text: Page requests, including search text in the address — 60 days, then deleted by a purge that runs every day
  - period: 1 year
    scope: Contact messages
    text: Contact messages — 1 year, then deleted by the same daily purge
  - period: 7 years
    scope: Billing records
    text: Billing records — 7 years (legal obligation)
  rights:
  - right: Right of access
    text: Right of access — request a copy of your data
  - right: Right to rectification
    text: Right to rectification — correct inaccurate data
  - right: Right to erasure
    text: Right to erasure — request deletion of your data ("right to be forgotten")
  - right: Right to portability
    text: Right to portability — receive your data in a machine-readable format
  - right: Right to object
    text: Right to object — object to processing based on legitimate interest
  - right: Right to restrict processing
    text: Right to restrict processing — limit how we use your data
  role:
    text: OSCAR HOLDING is the data controller for personal data processed through this Service.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data .
  subprocessors:
    text: Brevo — delivery of transactional email (account activation, password reset). Receives your email address and the message we send you.
    url: null
  transfers:
  - mechanism: SCC
    text: Where that involves a transfer outside the EU, it takes place under the safeguards those providers offer (Standard Contractual Clauses or equivalent).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Pexafy
provenance_date: '2026-11-10'
provider_name: Pexafy
provider_slug: pexafy
slug: pexafy-privacy-policy
source_date: '2026-11-10'
source_filename: pexafy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pexafy.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Pexafy\naid: pexafy\nurl: https://pexafy.com/legal/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: OSCAR HOLDING is the data controller for personal data processed through this Service.\ndata_categories:\n- category: contact\n  text: Email address — used for account creation, login, and communications\n- category: identifying\n  text: Password — stored as a bcrypt hash (never in plaintext)\n- category: device\n  text: IP address — used for security, abuse prevention and rate-limiting.\n- category: device\n  text: User-Agent — browser/client information\n- category: behavioral\n  text:\
  \ Visitor cookie ( pxf_vid ) — a first-party identifier we set to recognise a returning browser and understand\n    how people arrive at Pexafy.\n- category: communication\n  text: Name, email, subject, and message when you contact us\n- category: financial\n  text: Creem collects your payment and billing details (name, email, billing address, payment method) to charge\n    you, issue your invoices and collect taxes\npurposes:\n- purpose: Provide the Service\n  text: Provide the Service — authenticate you, process API requests, manage your subscription\n- purpose: Security\n  text: Security — detect abuse, enforce rate limits, prevent unauthorized access\n- purpose: Communications\n  text: Communications — transactional emails (account-related, not marketing)\n- purpose: Analytics\n  text: Analytics — anonymized, aggregated usage statistics to improve the Service\n- purpose: Legal obligations\n  text: Legal obligations — comply with applicable law\nretention:\n- scope: Account data\n \
  \ period: until you delete your account\n  text: Account data — retained until you delete your account\n- scope: API call log\n  period: 90 days\n  text: API call log, including the text of searches — 90 days\n- scope: Page requests\n  period: 60 days\n  text: Page requests, including search text in the address — 60 days, then deleted by a purge that runs every day\n- scope: Contact messages\n  period: 1 year\n  text: Contact messages — 1 year, then deleted by the same daily purge\n- scope: Billing records\n  period: 7 years\n  text: Billing records — 7 years (legal obligation)\nresidency:\n- region: European Union\n  text: Your data is stored within the European Union.\ntransfers:\n- mechanism: SCC\n  text: Where that involves a transfer outside the EU, it takes place under the safeguards those providers offer\n    (Standard Contractual Clauses or equivalent).\nsubprocessors:\n  url: null\n  text: Brevo — delivery of transactional email (account activation, password reset). Receives your\
  \ email address\n    and the message we send you.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion by the user\n  text: Account data — retained until you delete your account\nrights:\n- right: Right of access\n  text: Right of access — request a copy of your data\n- right: Right to rectification\n  text: Right to rectification — correct inaccurate data\n- right: Right to erasure\n  text: Right to erasure — request deletion of your data (\"right to be forgotten\")\n- right: Right to portability\n  text: Right to portability — receive your data in a machine-readable format\n- right: Right to object\n  text: Right to object — object to processing based on legitimate interest\n- right: Right to restrict processing\n  text: Right to restrict processing — limit how we use your data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data .\n"
source_yaml_url: https://artifacts.apis.io/pexafy/privacy/pexafy-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Pexafy's own page on 2026-11-10.
synthetic: false
tags:
- Image
- Photos
- Stock Photos
- Image Search
- Semantic Search
- Computer Vision
- Embeddings
- MCP
- Agent-Native
- Content Licensing
---
