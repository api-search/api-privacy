---
api_specs:
- filename: typesearch-ai-charts-api-openapi.yml
  format: yaml
  label: typesearch-ai Charts API
  slug: typesearch-ai-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-charts-api-openapi.yml
- filename: typesearch-ai-contents-api-openapi.yml
  format: yaml
  label: typesearch-ai Contents API
  slug: typesearch-ai-contents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-contents-api-openapi.yml
- filename: typesearch-ai-embed-api-openapi.yml
  format: yaml
  label: typesearch-ai Embed API
  slug: typesearch-ai-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-embed-api-openapi.yml
- filename: typesearch-ai-indexes-api-openapi.yml
  format: yaml
  label: typesearch-ai Indexes API
  slug: typesearch-ai-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-indexes-api-openapi.yml
- filename: typesearch-ai-jobs-api-openapi.yml
  format: yaml
  label: typesearch-ai Jobs API
  slug: typesearch-ai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-jobs-api-openapi.yml
- filename: typesearch-ai-search-api-openapi.yml
  format: yaml
  label: typesearch-ai Search API
  slug: typesearch-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-search-api-openapi.yml
- filename: typesearch-ai-similar-api-openapi.yml
  format: yaml
  label: typesearch-ai Similar API
  slug: typesearch-ai-similar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-similar-api-openapi.yml
- filename: typesearch-ai-usage-api-openapi.yml
  format: yaml
  label: typesearch-ai Usage API
  slug: typesearch-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/typesearch-ai/openapi/typesearch-ai-usage-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: Account. Your name and email.
  - category: financial
    text: Billing. Paddle collects your payment and billing details (card, billing address and tax ID if you give one).
  - category: location
    text: your approximate country, from your IP address at sign-up
  - category: behavioral
    text: Website visits. Page views, referrers, countries, browsers and device types, in aggregate
  - category: communication
    text: Support messages. What you write to us through the Support page or by email, and our replies.
  deletion:
    route: email request
    text: Write to privacy@typesearch.ai from the email on your account
  dpa:
    available: true
    text: Enterprise customers can sign a data processing agreement (DPA) with us.
    url: null
  purposes:
  - purpose: provide the Service
    text: To provide the Service (account, keys, requests, credit, support and service emails)
  - purpose: security and reliability
    text: To keep it secure and working (preventing abuse and fraud, fixing errors, measuring quality and capacity)
  - purpose: legal obligations
    text: To meet legal obligations (tax and accounting records, requests from authorities)
  - purpose: product news
    text: To send you product news
  residency:
  - region: processing locations
    text: our providers process data in the United States, the European Union and other countries
  retention:
  - period: 7 days
    scope: 'request logs: queries and parameters'
    text: The queries and parameters are deleted after 7 days
  - period: null
    scope: 'request logs: rest of record'
    text: the rest of the record after 35
  - period: 30 days
    scope: account, team and keys
    text: When you close it, we delete them within 30 days, backups included.
  - period: null
    scope: aggregated usage
    text: 'Aggregated usage : while your account exists.'
  - period: a few weeks
    scope: technical logs
    text: rotated automatically, usually within a few weeks
  - period: 10 years
    scope: billing records
    text: in Argentina, up to 10 years
  rights:
  - right: access
    text: access the personal data we hold about you and get a copy
  - right: correction
    text: correct data that is wrong or incomplete
  - right: deletion
    text: delete your data, except what the law requires us to keep, such as billing records
  - right: portability
    text: export it in a structured, machine-readable format
  - right: objection or restriction
    text: object to processing based on our legitimate interests, or ask us to restrict it
  - right: withdraw consent
    text: withdraw your consent where we rely on it
  role:
    text: The controller of your personal data is [legal name]
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal data
  subprocessors:
    text: We use these providers to run the Service.
    url: null
  transfers:
  - mechanism: SCC
    text: include standard contractual clauses for transfers to countries without that recognition
  - mechanism: adequacy
    text: the European Commission considers that Argentina offers an adequate level of protection
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: typesearch-ai
provenance_date: '2026-11-10'
provider_name: typesearch-ai
provider_slug: typesearch-ai
slug: typesearch-ai-privacy-policy
source_date: '2026-11-10'
source_filename: typesearch-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://typesearch.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: typesearch-ai\naid: typesearch-ai\nurl: https://typesearch.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is [legal name]\ndata_categories:\n- category: contact\n  text: Account. Your name and email.\n- category: financial\n  text: Billing. Paddle collects your payment and billing details (card, billing address and tax ID if you give\n    one).\n- category: location\n  text: your approximate country, from your IP address at sign-up\n- category: behavioral\n  text: Website visits. Page views, referrers, countries, browsers and device types, in\
  \ aggregate\n- category: communication\n  text: Support messages. What you write to us through the Support page or by email, and our replies.\npurposes:\n- purpose: provide the Service\n  text: To provide the Service (account, keys, requests, credit, support and service emails)\n- purpose: security and reliability\n  text: To keep it secure and working (preventing abuse and fraud, fixing errors, measuring quality and capacity)\n- purpose: legal obligations\n  text: To meet legal obligations (tax and accounting records, requests from authorities)\n- purpose: product news\n  text: To send you product news\nretention:\n- scope: 'request logs: queries and parameters'\n  period: 7 days\n  text: The queries and parameters are deleted after 7 days\n- scope: 'request logs: rest of record'\n  period: null\n  text: the rest of the record after 35\n- scope: account, team and keys\n  period: 30 days\n  text: When you close it, we delete them within 30 days, backups included.\n- scope: aggregated usage\n\
  \  period: null\n  text: 'Aggregated usage : while your account exists.'\n- scope: technical logs\n  period: a few weeks\n  text: rotated automatically, usually within a few weeks\n- scope: billing records\n  period: 10 years\n  text: in Argentina, up to 10 years\nresidency:\n- region: processing locations\n  text: our providers process data in the United States, the European Union and other countries\ntransfers:\n- mechanism: SCC\n  text: include standard contractual clauses for transfers to countries without that recognition\n- mechanism: adequacy\n  text: the European Commission considers that Argentina offers an adequate level of protection\nsubprocessors:\n  url: null\n  text: We use these providers to run the Service.\ndpa:\n  available: true\n  url: null\n  text: Enterprise customers can sign a data processing agreement (DPA) with us.\ndeletion:\n  route: email request\n  text: Write to privacy@typesearch.ai from the email on your account\nrights:\n- right: access\n  text: access\
  \ the personal data we hold about you and get a copy\n- right: correction\n  text: correct data that is wrong or incomplete\n- right: deletion\n  text: delete your data, except what the law requires us to keep, such as billing records\n- right: portability\n  text: export it in a structured, machine-readable format\n- right: objection or restriction\n  text: object to processing based on our legitimate interests, or ask us to restrict it\n- right: withdraw consent\n  text: withdraw your consent where we rely on it\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell personal data\n"
source_yaml_url: https://artifacts.apis.io/typesearch-ai/privacy/typesearch-ai-privacy-policy.yml
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
summary_line: 29 quoted statements, read from typesearch-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Search
- Software-as-a-Service
- Data
---
