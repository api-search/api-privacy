---
api_specs:
- filename: clinkforge-com-openapi-generated.yml
  format: yaml
  label: Clink Forge API
  slug: clinkforge-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clinkforge-com/openapi/_ae-authored/clinkforge-com-openapi-generated.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: device
    text: Like any web service, API requests carry an IP address, user-agent string, headers, and query parameters.
  - category: financial
    text: We record the paying wallet address, amount, and on-chain transaction reference for each settlement
  - category: contact
    text: If you write to us, we have your email and what you sent.
  deletion:
    route: email request
    text: If you believe we hold personal data about you and want it corrected or removed, or you have any privacy question, email [email protected] and we will respond promptly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate service
    text: 'We log these to operate the service: telemetry, abuse prevention, capacity planning, and understanding which datasets are asked for.'
  - purpose: reply to inquiries
    text: We use it to reply.
  retention:
  - period: 14 days
    scope: operational telemetry
    text: system health metrics are pruned after 14 days
  - period: long-term
    scope: settlement and receipt records
    text: Settlement and receipt records are kept long-term
  rights:
  - right: correction or removal
    text: If you believe we hold personal data about you and want it corrected or removed
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No sale or rental of data about callers, ever.
  subprocessors:
    text: Cloudflare serves this site and fronts the API (CDN, edge, DDoS protection) and processes request metadata to do so.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clink Forge
provenance_date: '2026-11-09'
provider_name: Clink Forge
provider_slug: clinkforge-com
slug: clinkforge-com-privacy-policy
source_date: '2026-11-09'
source_filename: clinkforge-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clinkforge.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clink Forge\naid: clinkforge-com\nurl: https://clinkforge.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Like any web service, API requests carry an IP address, user-agent string, headers, and query parameters.\n- category: financial\n  text: We record the paying wallet address, amount, and on-chain transaction reference for each settlement\n- category: contact\n  text: If you write to us, we have your email and what you sent.\npurposes:\n- purpose: operate service\n  text: 'We log these to operate the service: telemetry, abuse\
  \ prevention, capacity planning, and understanding\n    which datasets are asked for.'\n- purpose: reply to inquiries\n  text: We use it to reply.\nretention:\n- scope: operational telemetry\n  period: 14 days\n  text: system health metrics are pruned after 14 days\n- scope: settlement and receipt records\n  period: long-term\n  text: Settlement and receipt records are kept long-term\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare serves this site and fronts the API (CDN, edge, DDoS protection) and processes request metadata\n    to do so.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: If you believe we hold personal data about you and want it corrected or removed, or you have any privacy\n    question, email [email protected] and we will respond promptly.\nrights:\n- right: correction or removal\n  text: If you believe we hold personal data about you and want it corrected or removed\nsale_or_sharing:\n  stance:\
  \ prohibited\n  text: No sale or rental of data about callers, ever.\n"
source_yaml_url: https://artifacts.apis.io/clinkforge-com/privacy/clinkforge-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from Clink Forge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government Data
- Open Data
- x402
- Payments
- MCP
- AI Agents
- Data Provenance
- Cryptocurrency
---
