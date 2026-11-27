---
api_specs:
- filename: aon-pro-openapi-generated.yml
  format: yaml
  label: AON API
  slug: aon-pro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aon-pro/openapi/_ae-authored/aon-pro-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: we record the click together with your IP address and user-agent
  - category: behavioral
    text: Search queries. The product-related text you send to AON Shopping
  - category: device
    text: Standard server logs (request path, response status, latency) used to operate the service and detect abuse.
  - category: location
    text: a coarse country/region signal where available
  - category: contact
    text: 'Email: [email protected]'
  deletion:
    route: email the address below
    text: If you believe we hold information about you, you can email us at the address below and we will respond in accordance with applicable law
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: return product results
    text: To return product results that match your query.
  - purpose: partner attribution and settlement
    text: To attribute partner-confirmed transactions back to AON for the purpose of settlement with the partner.
  - purpose: service health and abuse detection
    text: To monitor service health, detect abuse, and protect the integrity of the network.
  - purpose: legal compliance
    text: To comply with legal obligations.
  residency:
  - region: Singapore
    text: AON operates from Singapore.
  retention:
  - period: 7 days
    scope: search queries and tool metadata (primary database)
    text: The primary database copy is removed by a scheduled purge job whose default retention window is 7 days.
  - period: null
    scope: analytics warehouse copy
    text: A copy of the same records is also exported to our analytics warehouse, where they are stored as append-only rows and are not covered by that purge.
  - period: null
    scope: anonymous click_id records
    text: we do not currently operate a scheduled deletion job for them, and our automated cleanup removes test-generated records only.
  - period: not longer than 30 days
    scope: operational logs
    text: Operational logs follow standard cloud-provider retention, typically not longer than 30 days.
  - period: indefinitely
    scope: aggregated analytics
    text: We retain aggregated, non-identifying analytics indefinitely.
  rights:
  - right: access
    text: the right to access, correct, delete, restrict, or object to certain processing of your information, and the right to data portability
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on standard contractual clauses or equivalent safeguards for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AON
provenance_date: '2026-11-09'
provider_name: AON
provider_slug: aon-pro
slug: aon-pro-privacy-policy
source_date: '2026-11-09'
source_filename: aon-pro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aon.pro/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AON\naid: aon-pro\nurl: https://www.aon.pro/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we record the click together with your IP address and user-agent\n- category: behavioral\n  text: Search queries. The product-related text you send to AON Shopping\n- category: device\n  text: Standard server logs (request path, response status, latency) used to operate the service and detect abuse.\n- category: location\n  text: a coarse country/region signal where available\n- category: contact\n  text: 'Email: [email protected]'\npurposes:\n\
  - purpose: return product results\n  text: To return product results that match your query.\n- purpose: partner attribution and settlement\n  text: To attribute partner-confirmed transactions back to AON for the purpose of settlement with the partner.\n- purpose: service health and abuse detection\n  text: To monitor service health, detect abuse, and protect the integrity of the network.\n- purpose: legal compliance\n  text: To comply with legal obligations.\nretention:\n- scope: search queries and tool metadata (primary database)\n  period: 7 days\n  text: The primary database copy is removed by a scheduled purge job whose default retention window is 7 days.\n- scope: analytics warehouse copy\n  period: null\n  text: A copy of the same records is also exported to our analytics warehouse, where they are stored as append-only\n    rows and are not covered by that purge.\n- scope: anonymous click_id records\n  period: null\n  text: we do not currently operate a scheduled deletion job for\
  \ them, and our automated cleanup removes test-generated\n    records only.\n- scope: operational logs\n  period: not longer than 30 days\n  text: Operational logs follow standard cloud-provider retention, typically not longer than 30 days.\n- scope: aggregated analytics\n  period: indefinitely\n  text: We retain aggregated, non-identifying analytics indefinitely.\nresidency:\n- region: Singapore\n  text: AON operates from Singapore.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on standard contractual clauses or equivalent safeguards for cross-border transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email the address below\n  text: If you believe we hold information about you, you can email us at the address below and we will respond\n    in accordance with applicable law\nrights:\n- right: access\n  text: the right to access, correct, delete, restrict, or object to certain processing of your\
  \ information, and\n    the right to data portability\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/aon-pro/privacy/aon-pro-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AON's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Commerce
- Monetization
- OfferNetwork
- Platform
---
