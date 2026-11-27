---
api_specs:
- filename: alphaloops-carriers-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Carriers API
  slug: alphaloops-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-carriers-api-openapi.yml
- filename: alphaloops-contacts-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Contacts API
  slug: alphaloops-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-contacts-api-openapi.yml
- filename: alphaloops-inspections-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Inspections API
  slug: alphaloops-inspections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-inspections-api-openapi.yml
- filename: alphaloops-vins-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Vins API
  slug: alphaloops-vins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-vins-api-openapi.yml
- filename: alphaloops-custom-data-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Custom Data API
  slug: alphaloops-custom-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-custom-data-api-openapi.yml
- filename: alphaloops-mc-sale-listings-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Mc Sale Listings API
  slug: alphaloops-mc-sale-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-mc-sale-listings-api-openapi.yml
- filename: alphaloops-mc-sales-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Mc Sales API
  slug: alphaloops-mc-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-mc-sales-api-openapi.yml
- filename: alphaloops-peer-groups-api-openapi.yml
  format: yaml
  label: AlphaLoops FMCSA Carrier Data API Peer Groups API
  slug: alphaloops-peer-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaloops/openapi/alphaloops-peer-groups-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: AlphaLoops collects first and last names and email addresses of customer employees, contractors, and customers as part of our service.
  - category: device
    text: a device identifier that does not include your name or contact details
  deletion:
    route: contact your AlphaLoops representative or submit a request via email
    text: To request removal of your personal information from the AlphaLoops cloud-based offering, contact your AlphaLoops representative or submit a request via email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: identity verification and fraud prevention
    text: to verify your identity and to detect and protect against fraud
  retention:
  - period: null
    scope: all personal information
    text: AlphaLoops retains personal information in its system for as long as needed.
  - period: five years
    scope: fraud prevention records
    text: records never linked to any other verification automatically expire after five years.
  - period: 18 months
    scope: raw identifiers such as IP address
    text: Raw identifiers such as your IP address are deleted within 18 months.
  rights:
  - right: request removal of personal information
    text: To request removal of your personal information from the AlphaLoops cloud-based offering contact mitch@runalphaloop.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: AlphaLoops does not share, sell, rent, or trade personal information with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AlphaLoops FMCSA Carrier Data API
provenance_date: '2026-11-09'
provider_name: AlphaLoops FMCSA Carrier Data API
provider_slug: alphaloops
slug: alphaloops-privacy-policy
source_date: '2026-11-09'
source_filename: alphaloops-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://runalphaloops.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AlphaLoops FMCSA Carrier Data API\naid: alphaloops\nurl: https://runalphaloops.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: AlphaLoops collects first and last names and email addresses of customer employees, contractors, and customers\n    as part of our service.\n- category: device\n  text: a device identifier that does not include your name or contact details\npurposes:\n- purpose: identity verification and fraud prevention\n  text: to verify your identity and to detect and protect against fraud\nretention:\n- scope: all\
  \ personal information\n  period: null\n  text: AlphaLoops retains personal information in its system for as long as needed.\n- scope: fraud prevention records\n  period: five years\n  text: records never linked to any other verification automatically expire after five years.\n- scope: raw identifiers such as IP address\n  period: 18 months\n  text: Raw identifiers such as your IP address are deleted within 18 months.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact your AlphaLoops representative or submit a request via email\n  text: To request removal of your personal information from the AlphaLoops cloud-based offering, contact your AlphaLoops\n    representative or submit a request via email.\nrights:\n- right: request removal of personal information\n  text: To request removal of your personal information from the AlphaLoops cloud-based offering contact mitch@runalphaloop.com\n\
  sale_or_sharing:\n  stance: prohibited\n  text: AlphaLoops does not share, sell, rent, or trade personal information with third parties.\n"
source_yaml_url: https://artifacts.apis.io/alphaloops/privacy/alphaloops-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from AlphaLoops FMCSA Carrier Data API's own page on 2026-11-09.
synthetic: false
tags:
- fmcsa api
- safer web api
- dot lookup
- carrier data
- Freight
- Trucking
- Motor Carrier
- fleet intelligence
- Sales Intelligence
- MCP Server
- Contact Enrichment
- Risk Management
- Fraud Prevention
---
