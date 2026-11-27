---
api_specs:
- filename: cascade-industries-balance-api-openapi.yml
  format: yaml
  label: Cascade Balance API
  slug: cascade-industries-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cascade-industries/openapi/cascade-industries-balance-api-openapi.yml
- filename: cascade-industries-device-api-openapi.yml
  format: yaml
  label: Cascade Device API
  slug: cascade-industries-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cascade-industries/openapi/cascade-industries-device-api-openapi.yml
- filename: cascade-industries-forecast-api-openapi.yml
  format: yaml
  label: Cascade Forecast API
  slug: cascade-industries-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cascade-industries/openapi/cascade-industries-forecast-api-openapi.yml
- filename: cascade-industries-models-api-openapi.yml
  format: yaml
  label: Cascade Models API
  slug: cascade-industries-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cascade-industries/openapi/cascade-industries-models-api-openapi.yml
- filename: cascade-industries-usage-api-openapi.yml
  format: yaml
  label: Cascade Usage API
  slug: cascade-industries-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cascade-industries/openapi/cascade-industries-usage-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and sign-in information: your email address, account identifiers, authentication and authorization records, and information you provide through our sign-in service.'
  - category: financial
    text: 'Usage and billing information: request identifiers, models used, request size and shape, response status, latency, credit balances, charges, purchases, refunds and payment-provider records.'
  - category: device
    text: 'Technical and support information: connection and security logs, browser or device information, diagnostic events and information you send when requesting support.'
  - category: other
    text: 'Forecast data: the numeric observations, timestamps or frequency, model choices, forecast horizon, quantiles, covariates and other fields you submit, together with the resulting forecasts.'
  deletion:
    route: contact the privacy contact
    text: Contact us to request access to, correction of or deletion of personal information, or to raise a privacy concern.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation
    text: We process information to authenticate you, authorize connected applications, generate forecasts, describe and plot saved results, administer credits and payments, recover retryable requests, prevent abuse, diagnose failures and respond to support requests.
  - purpose: operational analysis
    text: The forecasting backend records derived series characteristics, model selections and timing information for operational analysis and routing evaluation.
  residency:
  - region: outside user country
    text: Information may be processed outside your country by these providers.
  - region: service as a whole
    text: TEE inference does not establish a particular data-residency location for the service as a whole.
  retention:
  - period: 24 hours
    scope: idempotency recovery records
    text: The replay window is 24 hours after completion.
  - period: 2 days
    scope: idempotency stored responses
    text: A daily job deletes these records once the window has passed, so a stored response is kept for at most 2 days.
  - period: null
    scope: inference backend logs
    text: The inference backend logs derived request characteristics and performance information, without series values.
  rights:
  - right: access, correction and deletion
    text: Contact us to request access to, correction of or deletion of personal information, or to raise a privacy concern.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The sub-processor list gives the role, data and location of each.
    url: null
  transfers:
  - mechanism: other
    text: Information may be processed outside your country by these providers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cascade
provenance_date: '2026-11-09'
provider_name: Cascade
provider_slug: cascade-industries
slug: cascade-industries-privacy-policy
source_date: '2026-11-09'
source_filename: cascade-industries-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ephemeris.cascade.industries/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cascade\naid: cascade-industries\nurl: https://ephemeris.cascade.industries/docs/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account and sign-in information: your email address, account identifiers, authentication and authorization\n    records, and information you provide through our sign-in service.'\n- category: financial\n  text: 'Usage and billing information: request identifiers, models used, request size and shape, response status,\n    latency, credit balances, charges, purchases, refunds and payment-provider records.'\n\
  - category: device\n  text: 'Technical and support information: connection and security logs, browser or device information, diagnostic\n    events and information you send when requesting support.'\n- category: other\n  text: 'Forecast data: the numeric observations, timestamps or frequency, model choices, forecast horizon, quantiles,\n    covariates and other fields you submit, together with the resulting forecasts.'\npurposes:\n- purpose: service operation\n  text: We process information to authenticate you, authorize connected applications, generate forecasts, describe\n    and plot saved results, administer credits and payments, recover retryable requests, prevent abuse, diagnose\n    failures and respond to support requests.\n- purpose: operational analysis\n  text: The forecasting backend records derived series characteristics, model selections and timing information\n    for operational analysis and routing evaluation.\nretention:\n- scope: idempotency recovery records\n  period:\
  \ 24 hours\n  text: The replay window is 24 hours after completion.\n- scope: idempotency stored responses\n  period: 2 days\n  text: A daily job deletes these records once the window has passed, so a stored response is kept for at most 2\n    days.\n- scope: inference backend logs\n  period: null\n  text: The inference backend logs derived request characteristics and performance information, without series values.\nresidency:\n- region: outside user country\n  text: Information may be processed outside your country by these providers.\n- region: service as a whole\n  text: TEE inference does not establish a particular data-residency location for the service as a whole.\ntransfers:\n- mechanism: other\n  text: Information may be processed outside your country by these providers.\nsubprocessors:\n  url: null\n  text: The sub-processor list gives the role, data and location of each.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the privacy contact\n  text:\
  \ Contact us to request access to, correction of or deletion of personal information, or to raise a privacy\n    concern.\nrights:\n- right: access, correction and deletion\n  text: Contact us to request access to, correction of or deletion of personal information, or to raise a privacy\n    concern.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cascade-industries/privacy/cascade-industries-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 15 quoted statements, read from Cascade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Time Series
- Forecasting
- Artificial Intelligence
- Machine Learning
- Foundation Models
- MCP
- Benchmarks
---
