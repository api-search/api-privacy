---
api_specs:
- filename: fedex-authorization-api-openapi.yml
  format: yaml
  label: FedEx API Authorization
  slug: fedex-api-authorization
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-authorization-api-openapi.yml
- filename: fedex-rate-api-openapi.yml
  format: yaml
  label: FedEx Rates and Transit Times API
  slug: fedex-rates-and-transit-times-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-rate-api-openapi.yml
- filename: fedex-ship-api-openapi.yml
  format: yaml
  label: FedEx Ship API
  slug: fedex-ship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-ship-api-openapi.yml
- filename: fedex-pickup-api-openapi.yml
  format: yaml
  label: FedEx Pickup Request API
  slug: fedex-pickup-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-pickup-api-openapi.yml
- filename: fedex-track-api-openapi.yml
  format: yaml
  label: FedEx Basic Integrated Visibility
  slug: fedex-basic-integrated-visibility
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-track-api-openapi.yml
- filename: fedex-regulatory-api-openapi.yml
  format: yaml
  label: FedEx Regulatory API
  slug: fedex-regulatory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-regulatory-api-openapi.yml
- filename: fedex-address-api-openapi.yml
  format: yaml
  label: FedEx Address API
  slug: fedex-address-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-address-api-openapi.yml
- filename: fedex-availability-api-openapi.yml
  format: yaml
  label: FedEx Availability API
  slug: fedex-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-availability-api-openapi.yml
- filename: fedex-commodity-api-openapi.yml
  format: yaml
  label: FedEx Commodity API
  slug: fedex-commodity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-commodity-api-openapi.yml
- filename: fedex-country-api-openapi.yml
  format: yaml
  label: FedEx Country API
  slug: fedex-country-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-country-api-openapi.yml
- filename: fedex-documents-api-openapi.yml
  format: yaml
  label: FedEx Documents API
  slug: fedex-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-documents-api-openapi.yml
- filename: fedex-dutytax-api-openapi.yml
  format: yaml
  label: FedEx Dutytax API
  slug: fedex-dutytax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-dutytax-api-openapi.yml
- filename: fedex-globaltrade-api-openapi.yml
  format: yaml
  label: FedEx Globaltrade API
  slug: fedex-globaltrade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-globaltrade-api-openapi.yml
- filename: fedex-irc-api-openapi.yml
  format: yaml
  label: FedEx Irc API
  slug: fedex-irc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-irc-api-openapi.yml
- filename: fedex-location-api-openapi.yml
  format: yaml
  label: FedEx Location API
  slug: fedex-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-location-api-openapi.yml
- filename: fedex-webhook-api-openapi.yml
  format: yaml
  label: FedEx Webhook API
  slug: fedex-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fedex/openapi/fedex-webhook-api-openapi.yml
claim_count: 6
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Examples of Personal Data: Names Government-issued identification numbers (social security and driver’s license numbers, etc.)'
  - category: contact
    text: Addresses Phone numbers Email addresses
  - category: other
    text: Photos or videos
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: null
    scope: Personal Data no longer needed for the purpose
    text: Personal Data no longer needed for the purpose specified at the time of collection shall be deleted according to applicable retention schedules unless it is subject to an exception from the Legal Department.
  rights:
  - right: Access, correction or deletion
    text: To the extent required by Applicable Law, individuals have a right to access their Personal Data and, where appropriate, to correct or delete it and exercise any other right provided by Applicable Law.
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
  - mechanism: other
    text: Personal Data may not be transferred to a country outside the country of origin unless the transfer has been approved by the Legal Department, who will ensure an adequate level of data protection or suitable safeguards are in place.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FedEx
provenance_date: '2026-11-09'
provider_name: FedEx
provider_slug: fedex
slug: fedex-privacy-policy
source_date: '2026-11-09'
source_filename: fedex-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fedex.com/en-us/trust-center/global-privacy-policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FedEx\naid: fedex\nurl: https://www.fedex.com/en-us/trust-center/global-privacy-policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Examples of Personal Data: Names Government-issued identification numbers (social security and driver’s\n    license numbers, etc.)'\n- category: contact\n  text: Addresses Phone numbers Email addresses\n- category: other\n  text: Photos or videos\npurposes: []\nretention:\n- scope: Personal Data no longer needed for the purpose\n  period: null\n  text: Personal Data no longer needed for the purpose\
  \ specified at the time of collection shall be deleted according\n    to applicable retention schedules unless it is subject to an exception from the Legal Department.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Personal Data may not be transferred to a country outside the country of origin unless the transfer has\n    been approved by the Legal Department, who will ensure an adequate level of data protection or suitable safeguards\n    are in place.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access, correction or deletion\n  text: To the extent required by Applicable Law, individuals have a right to access their Personal Data and, where\n    appropriate, to correct or delete it and exercise any other right provided by Applicable Law.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fedex/privacy/fedex-privacy-policy.yml
stated_fields:
- data_categories
- retention
- transfers
- rights
summary_line: 6 quoted statements, read from FedEx's own page on 2026-11-09.
synthetic: false
tags:
- Address Validation
- Freight
- Logistics
- Pickup
- Ratings
- Shipping
- Tracking
- Webhook
- Fortune 100
---
