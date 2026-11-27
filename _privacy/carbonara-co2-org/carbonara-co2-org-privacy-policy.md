---
api_specs:
- filename: carbonara-co2-org-calculate-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Calculate API
  slug: carbonara-co2-org-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-calculate-api-openapi.yml
- filename: carbonara-co2-org-factors-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Factors API
  slug: carbonara-co2-org-factors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-factors-api-openapi.yml
- filename: carbonara-co2-org-healthz-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Healthz API
  slug: carbonara-co2-org-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-healthz-api-openapi.yml
- filename: carbonara-co2-org-places-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Places API
  slug: carbonara-co2-org-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-places-api-openapi.yml
- filename: carbonara-co2-org-recommend-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Recommend API
  slug: carbonara-co2-org-recommend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-recommend-api-openapi.yml
- filename: carbonara-co2-org-report-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Report API
  slug: carbonara-co2-org-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-report-api-openapi.yml
- filename: carbonara-co2-org-scenario-api-openapi.yml
  format: yaml
  label: Carbonara CO2 Scenario API
  slug: carbonara-co2-org-scenario-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonara-co2-org/openapi/carbonara-co2-org-scenario-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your name, email address and its domain, sign-in provider and account id
  - category: behavioral
    text: how many shipments you calculate each day
  - category: device
    text: your network address is held in memory for the day only
  deletion:
    route: account page
    text: which you can do at any time from your account page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the test service
    text: 'We use them only to run this test service: to recognise you, to apply the fair-use limits, and to contact you about the service.'
  retention:
  - period: about two months
    scope: usage counts
    text: Usage counts are kept for about two months
  - period: until you delete it
    scope: account
    text: the account until you delete it, which you can do at any time from your account page
  - period: 90 days
    scope: published iLEAP results
    text: their iLEAP results (shipment footprints, with places, weights and emissions, and the TOCs and HOCs used) are stored for 90 days
  - period: for the day only
    scope: network addresses
    text: Without signing in, your network address is held in memory for the day only, to apply the daily limit
  rights:
  - right: deletion of published results
    text: You can delete them, or revoke a recipient, at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: They aren't shared or sold.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Carbonara CO2
provenance_date: '2026-11-09'
provider_name: Carbonara CO2
provider_slug: carbonara-co2-org
slug: carbonara-co2-org-privacy-policy
source_date: '2026-11-09'
source_filename: carbonara-co2-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sootcase.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Carbonara CO2\naid: carbonara-co2-org\nurl: https://sootcase.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we store your name, email address and its domain, sign-in provider and account id\n- category: behavioral\n  text: how many shipments you calculate each day\n- category: device\n  text: your network address is held in memory for the day only\npurposes:\n- purpose: run the test service\n  text: 'We use them only to run this test service: to recognise you, to apply the fair-use limits, and to contact\n    you about the\
  \ service.'\nretention:\n- scope: usage counts\n  period: about two months\n  text: Usage counts are kept for about two months\n- scope: account\n  period: until you delete it\n  text: the account until you delete it, which you can do at any time from your account page\n- scope: published iLEAP results\n  period: 90 days\n  text: their iLEAP results (shipment footprints, with places, weights and emissions, and the TOCs and HOCs used)\n    are stored for 90 days\n- scope: network addresses\n  period: for the day only\n  text: Without signing in, your network address is held in memory for the day only, to apply the daily limit\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account page\n  text: which you can do at any time from your account page\nrights:\n- right: deletion of published results\n  text: You can delete them, or revoke a recipient, at any time.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: They aren't shared or sold.\n"
source_yaml_url: https://artifacts.apis.io/carbonara-co2-org/privacy/carbonara-co2-org-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from Carbonara CO2's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sustainability
- Open Source
- Climate Tech
- Software
---
