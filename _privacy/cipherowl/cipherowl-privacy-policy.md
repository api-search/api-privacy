---
api_specs:
- filename: cipherowl-onchain-service-api-openapi.yml
  format: yaml
  label: CipherOwl Onchain Service API
  slug: cipherowl-onchain-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cipherowl/openapi/cipherowl-onchain-service-api-openapi.yml
- filename: cipherowl-private-data-api-api-openapi.yml
  format: yaml
  label: CipherOwl Private Data API
  slug: cipherowl-private-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cipherowl/openapi/cipherowl-private-data-api-api-openapi.yml
- filename: cipherowl-srr-api-api-openapi.yml
  format: yaml
  label: CipherOwl SRR API
  slug: cipherowl-srr-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cipherowl/openapi/cipherowl-srr-api-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: API key identifiers, IP-derived geolocation, and user-submitted content — may be indirectly associated with identifiable individuals or organizations.
  - category: device
    text: browser type and version, operating system, screen resolution, and device category (desktop, mobile, tablet).
  - category: behavioral
    text: 'Interaction data: clicks, scrolls, and engagement events within the Services.'
  - category: location
    text: 'Geographic data: approximate location derived from IP address (city/region level).'
  - category: communication
    text: we collect the content of those interactions, including prompts, queries, uploaded files, and responses
  deletion:
    route: contact privacy@cipherowl.com
    text: you may request deletion of your AI interaction data, including conversation history, uploaded files, and generated reports, by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: to operate, maintain, and improve the Services, including threat detection, analysis, and alerting.
  - purpose: API platform
    text: to authenticate API requests, enforce rate limits, and monitor usage.
  - purpose: Security
    text: to detect and prevent fraud, abuse, and security incidents affecting our platform and users.
  - purpose: Legal compliance
    text: to comply with applicable laws, regulations, legal processes, or enforceable government requests.
  retention:
  - period: 14 months
    scope: Google Analytics data
    text: 'retained according to our Google Analytics configuration (default: 14 months).'
  - period: 12 months
    scope: API logs
    text: 'API logs: retained for 12 months for operational, debugging, and product improvement purposes.'
  - period: 24 months
    scope: Threat analysis data
    text: submitted samples and scan results are retained for up to 24 months to support ongoing threat research, unless you request earlier deletion.
  - period: 12 months
    scope: Telemetry data
    text: 'Telemetry data: retained for up to 12 months for product improvement purposes.'
  - period: null
    scope: AI interaction data
    text: retained so you can return to earlier investigations, until you or your organization request their deletion.
  rights:
  - right: Threat data deletion
    text: if you have submitted samples or indicators for analysis, you may request their deletion by contacting us.
  - right: Cookie management
    text: you can control or delete cookies through your browser settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any data we collect.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CipherOwl
provenance_date: '2026-11-09'
provider_name: CipherOwl
provider_slug: cipherowl
slug: cipherowl-privacy-policy
source_date: '2026-11-09'
source_filename: cipherowl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cipherowl.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CipherOwl\naid: cipherowl\nurl: https://cipherowl.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: API key identifiers, IP-derived geolocation, and user-submitted content — may be indirectly associated with\n    identifiable individuals or organizations.\n- category: device\n  text: browser type and version, operating system, screen resolution, and device category (desktop, mobile, tablet).\n- category: behavioral\n  text: 'Interaction data: clicks, scrolls, and engagement events within the Services.'\n- category: location\n\
  \  text: 'Geographic data: approximate location derived from IP address (city/region level).'\n- category: communication\n  text: we collect the content of those interactions, including prompts, queries, uploaded files, and responses\npurposes:\n- purpose: Service delivery\n  text: to operate, maintain, and improve the Services, including threat detection, analysis, and alerting.\n- purpose: API platform\n  text: to authenticate API requests, enforce rate limits, and monitor usage.\n- purpose: Security\n  text: to detect and prevent fraud, abuse, and security incidents affecting our platform and users.\n- purpose: Legal compliance\n  text: to comply with applicable laws, regulations, legal processes, or enforceable government requests.\nretention:\n- scope: Google Analytics data\n  period: 14 months\n  text: 'retained according to our Google Analytics configuration (default: 14 months).'\n- scope: API logs\n  period: 12 months\n  text: 'API logs: retained for 12 months for operational,\
  \ debugging, and product improvement purposes.'\n- scope: Threat analysis data\n  period: 24 months\n  text: submitted samples and scan results are retained for up to 24 months to support ongoing threat research,\n    unless you request earlier deletion.\n- scope: Telemetry data\n  period: 12 months\n  text: 'Telemetry data: retained for up to 12 months for product improvement purposes.'\n- scope: AI interaction data\n  period: null\n  text: retained so you can return to earlier investigations, until you or your organization request their deletion.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacy@cipherowl.com\n  text: you may request deletion of your AI interaction data, including conversation history, uploaded files, and\n    generated reports, by contacting us.\nrights:\n- right: Threat data deletion\n  text: if you have submitted samples or indicators for analysis, you may\
  \ request their deletion by contacting us.\n- right: Cookie management\n  text: you can control or delete cookies through your browser settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any data we collect.\n"
source_yaml_url: https://artifacts.apis.io/cipherowl/privacy/cipherowl-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from CipherOwl's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Compliance
- Cryptocurrency
- Security
- Risk Management
- Sanctions Screening
- AML
- Digital Assets
- Stablecoins
- Web3
---
