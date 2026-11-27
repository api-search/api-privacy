---
api_specs:
- filename: tektolo-com-catalog-api-openapi.yml
  format: yaml
  label: tektolo-com Catalog API
  slug: tektolo-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-catalog-api-openapi.yml
- filename: tektolo-com-deposit-settlement-api-openapi.yml
  format: yaml
  label: tektolo-com Deposit Settlement API
  slug: tektolo-com-deposit-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-deposit-settlement-api-openapi.yml
- filename: tektolo-com-feedback-api-openapi.yml
  format: yaml
  label: tektolo-com Feedback API
  slug: tektolo-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-feedback-api-openapi.yml
- filename: tektolo-com-keys-api-openapi.yml
  format: yaml
  label: tektolo-com Keys API
  slug: tektolo-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-keys-api-openapi.yml
- filename: tektolo-com-property-turnover-api-openapi.yml
  format: yaml
  label: tektolo-com Property Turnover API
  slug: tektolo-com-property-turnover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-property-turnover-api-openapi.yml
- filename: tektolo-com-rules-history-api-openapi.yml
  format: yaml
  label: tektolo-com rules history API
  slug: tektolo-com-rules-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-rules-history-api-openapi.yml
- filename: tektolo-com-verify-api-openapi.yml
  format: yaml
  label: tektolo-com Verify API
  slug: tektolo-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-verify-api-openapi.yml
- filename: tektolo-com-x402-api-openapi.yml
  format: yaml
  label: tektolo-com X402 API
  slug: tektolo-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tektolo-com/openapi/tektolo-com-x402-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: your name, work email, company, role
  - category: behavioral
    text: 'Collected: page view (log line per page)'
  - category: device
    text: a category for the software that made the request
  - category: communication
    text: What you type into a feedback form
  - category: other
    text: The whole text of your notes, or the list of issues an AI assistant or other software sends
  - category: financial
    text: the wallet address that paid, the transaction id and network, the amount
  deletion:
    route: email support@tektolo.com
    text: If you want something removed, email support@tektolo.com with the approximate date and some of the text you typed
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and secure the Service
    text: To operate and secure the Service (rate limiting, abuse prevention, debugging)
  - purpose: improve demand and accuracy
    text: to understand demand and improve accuracy of our rules, matching and coverage
  residency:
  - region: United States
    text: stores logs and estimate records in data centers in the United States
  retention:
  - period: 30 days
    scope: usage event and page view logs
    text: Up to 30 days in Azure Log Analytics
  - period: 730 days
    scope: anonymized estimate record
    text: Up to 730 days, then automatically deleted
  - period: 5 years
    scope: property turnover notes
    text: Up to 5 years, then automatically deleted
  - period: 3 years
    scope: pilot application
    text: Up to 3 years, then automatically deleted
  rights:
  - right: know, access, correct, delete
    text: you may have rights to know, access, correct or delete personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tektolo-com
provenance_date: '2026-11-10'
provider_name: tektolo-com
provider_slug: tektolo-com
slug: tektolo-com-privacy-policy
source_date: '2026-11-10'
source_filename: tektolo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tektolo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tektolo-com\naid: tektolo-com\nurl: https://tektolo.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your name, work email, company, role\n- category: behavioral\n  text: 'Collected: page view (log line per page)'\n- category: device\n  text: a category for the software that made the request\n- category: communication\n  text: What you type into a feedback form\n- category: other\n  text: The whole text of your notes, or the list of issues an AI assistant or other software sends\n- category: financial\n  text: the wallet address\
  \ that paid, the transaction id and network, the amount\npurposes:\n- purpose: operate and secure the Service\n  text: To operate and secure the Service (rate limiting, abuse prevention, debugging)\n- purpose: improve demand and accuracy\n  text: to understand demand and improve accuracy of our rules, matching and coverage\nretention:\n- scope: usage event and page view logs\n  period: 30 days\n  text: Up to 30 days in Azure Log Analytics\n- scope: anonymized estimate record\n  period: 730 days\n  text: Up to 730 days, then automatically deleted\n- scope: property turnover notes\n  period: 5 years\n  text: Up to 5 years, then automatically deleted\n- scope: pilot application\n  period: 3 years\n  text: Up to 3 years, then automatically deleted\nresidency:\n- region: United States\n  text: stores logs and estimate records in data centers in the United States\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ email support@tektolo.com\n  text: If you want something removed, email support@tektolo.com with the approximate date and some of the text\n    you typed\nrights:\n- right: know, access, correct, delete\n  text: you may have rights to know, access, correct or delete personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information.\n"
source_yaml_url: https://artifacts.apis.io/tektolo-com/privacy/tektolo-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from tektolo-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tools
- Artificial Intelligence
- Automation
- Reliability
---
