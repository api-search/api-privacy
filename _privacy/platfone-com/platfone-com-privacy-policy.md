---
api_specs:
- filename: platfone-com-activation-report-api-openapi.yml
  format: yaml
  label: platfone-com Activation Report API
  slug: platfone-com-activation-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-activation-report-api-openapi.yml
- filename: platfone-com-catalog-api-openapi.yml
  format: yaml
  label: platfone-com Catalog API
  slug: platfone-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-catalog-api-openapi.yml
- filename: platfone-com-prices-api-openapi.yml
  format: yaml
  label: platfone-com Prices API
  slug: platfone-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-prices-api-openapi.yml
- filename: platfone-com-sms-activation-api-openapi.yml
  format: yaml
  label: platfone-com SMS Activation API
  slug: platfone-com-sms-activation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-sms-activation-api-openapi.yml
- filename: platfone-com-user-api-openapi.yml
  format: yaml
  label: platfone-com User API
  slug: platfone-com-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-user-api-openapi.yml
- filename: platfone-com-webhooks-api-openapi.yml
  format: yaml
  label: platfone-com Webhooks 📡 API
  slug: platfone-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/platfone-com/openapi/platfone-com-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email, Telegram, Google, Apple, or Facebook login IDs
  - category: contact
    text: name, date of birth, country document type (passport, ID card, etc.)
  - category: financial
    text: Amount, currency, timestamps Payment processor metadata (e.g., BIN, wallet address, issuer country)
  - category: location
    text: IP, region, and timestamps
  - category: behavioral
    text: API activity and rate limits
  - category: device
    text: Device/browser type
  - category: communication
    text: 'Limited SMS or call content may be stored for: fraud prevention support quality review'
  deletion:
    route: Dashboard or email request
    text: You may delete your account via dashboard or email.
  dpa:
    available: true
    text: Platfone may act as a data processor under a Data Processing Addendum (DPA).
    url: null
  purposes:
  - purpose: provide and improve the Platform
    text: provide and improve the Platform
  - purpose: prevent fraud and misuse
    text: prevent fraud and misuse
  - purpose: comply with AML/CTF, sanctions and tax laws
    text: comply with AML/CTF, sanctions, and tax laws
  - purpose: process payments and invoices
    text: process payments and invoices
  residency:
  - region: Outside user's country
    text: Your data may be processed outside your country, including in the U.S., EU, UK, or EEA.
  retention:
  - period: lifetime of account + 90 days
    scope: Account info
    text: 'Account info: lifetime of account + 90 days'
  - period: 7 years
    scope: Payments/invoices
    text: 'Payments/invoices: 7 years'
  - period: 30–180 days
    scope: Logs
    text: 'Logs: 30–180 days'
  - period: 12 months or 1,000 last records
    scope: Activations/messages
    text: 'Activations/messages: 12 months or 1,000 last records'
  - period: 3–6 months unless required longer by law
    scope: KYC audit logs
    text: 'KYC audit logs: 3–6 months unless required longer by law'
  rights:
  - right: access
    text: access your data
  - right: correct inaccuracies
    text: correct inaccuracies
  - right: request deletion
    text: request deletion
  - right: restrict processing
    text: restrict processing
  - right: withdraw marketing consent
    text: withdraw marketing consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Adequate safeguards (e.g., SCCs) are applied.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: platfone-com
provenance_date: '2026-11-10'
provider_name: platfone-com
provider_slug: platfone-com
slug: platfone-com-privacy-policy
source_date: '2026-11-10'
source_filename: platfone-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://platfone.com/compliance#privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: platfone-com\naid: platfone-com\nurl: https://platfone.com/compliance#privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email, Telegram, Google, Apple, or Facebook login IDs\n- category: contact\n  text: name, date of birth, country document type (passport, ID card, etc.)\n- category: financial\n  text: Amount, currency, timestamps Payment processor metadata (e.g., BIN, wallet address, issuer country)\n- category: location\n  text: IP, region, and timestamps\n- category: behavioral\n  text: API activity and rate limits\n- category:\
  \ device\n  text: Device/browser type\n- category: communication\n  text: 'Limited SMS or call content may be stored for: fraud prevention support quality review'\npurposes:\n- purpose: provide and improve the Platform\n  text: provide and improve the Platform\n- purpose: prevent fraud and misuse\n  text: prevent fraud and misuse\n- purpose: comply with AML/CTF, sanctions and tax laws\n  text: comply with AML/CTF, sanctions, and tax laws\n- purpose: process payments and invoices\n  text: process payments and invoices\nretention:\n- scope: Account info\n  period: lifetime of account + 90 days\n  text: 'Account info: lifetime of account + 90 days'\n- scope: Payments/invoices\n  period: 7 years\n  text: 'Payments/invoices: 7 years'\n- scope: Logs\n  period: 30–180 days\n  text: 'Logs: 30–180 days'\n- scope: Activations/messages\n  period: 12 months or 1,000 last records\n  text: 'Activations/messages: 12 months or 1,000 last records'\n- scope: KYC audit logs\n  period: 3–6 months unless required\
  \ longer by law\n  text: 'KYC audit logs: 3–6 months unless required longer by law'\nresidency:\n- region: Outside user's country\n  text: Your data may be processed outside your country, including in the U.S., EU, UK, or EEA.\ntransfers:\n- mechanism: SCC\n  text: Adequate safeguards (e.g., SCCs) are applied.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Platfone may act as a data processor under a Data Processing Addendum (DPA).\ndeletion:\n  route: Dashboard or email request\n  text: You may delete your account via dashboard or email.\nrights:\n- right: access\n  text: access your data\n- right: correct inaccuracies\n  text: correct inaccuracies\n- right: request deletion\n  text: request deletion\n- right: restrict processing\n  text: restrict processing\n- right: withdraw marketing consent\n  text: withdraw marketing consent\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/platfone-com/privacy/platfone-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from platfone-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Telecommunications
- SMS
- Temporary-Numbers
---
