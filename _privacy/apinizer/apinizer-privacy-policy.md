---
api_specs:
- filename: apinizer-endpoints-api-openapi.yml
  format: yaml
  label: Apinizer Endpoints API
  slug: apinizer-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apinizer/openapi/apinizer-endpoints-api-openapi.yml
- filename: apinizer-gateways-api-openapi.yml
  format: yaml
  label: Apinizer Gateways API
  slug: apinizer-gateways-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apinizer/openapi/apinizer-gateways-api-openapi.yml
- filename: apinizer-monitoring-api-openapi.yml
  format: yaml
  label: Apinizer Monitoring API
  slug: apinizer-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apinizer/openapi/apinizer-monitoring-api-openapi.yml
- filename: apinizer-policies-api-openapi.yml
  format: yaml
  label: Apinizer Policies API
  slug: apinizer-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apinizer/openapi/apinizer-policies-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: name, work email, company, role, phone (optional), and the message you send
  - category: behavioral
    text: 'Aggregate usage analytics: page views, country-level location, referrer.'
  deletion:
    route: email privacy@apinizer.com
    text: To exercise any of these rights, email privacy@apinizer.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: respond to requests
    text: Used to respond to your request and route it to the right team.
  - purpose: newsletter
    text: 'Newsletter subscriptions: email address only.'
  residency:
  - region: EU and Türkiye
    text: Our internal systems run in EU and Türkiye data centers.
  retention:
  - period: 24 months from last interaction
    scope: Contact form submissions
    text: Contact form submissions — 24 months from last interaction
  - period: until you unsubscribe
    scope: Newsletter
    text: Newsletter — until you unsubscribe
  - period: 12 months, then aggregated further
    scope: Aggregate analytics
    text: Aggregate analytics — 12 months, then aggregated further
  rights:
  - right: access, correct, delete, restrict, object, portability
    text: access the personal data we hold about you, correct it, delete it, restrict its processing, object to processing, and request portability.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A current list is available on request.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apinizer
provenance_date: '2026-11-09'
provider_name: Apinizer
provider_slug: apinizer
slug: apinizer-privacy-policy
source_date: '2026-11-09'
source_filename: apinizer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apinizer.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apinizer\naid: apinizer\nurl: https://apinizer.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: name, work email, company, role, phone (optional), and the message you send\n- category: behavioral\n  text: 'Aggregate usage analytics: page views, country-level location, referrer.'\npurposes:\n- purpose: respond to requests\n  text: Used to respond to your request and route it to the right team.\n- purpose: newsletter\n  text: 'Newsletter subscriptions: email address only.'\nretention:\n- scope: Contact form submissions\n  period:\
  \ 24 months from last interaction\n  text: Contact form submissions — 24 months from last interaction\n- scope: Newsletter\n  period: until you unsubscribe\n  text: Newsletter — until you unsubscribe\n- scope: Aggregate analytics\n  period: 12 months, then aggregated further\n  text: Aggregate analytics — 12 months, then aggregated further\nresidency:\n- region: EU and Türkiye\n  text: Our internal systems run in EU and Türkiye data centers.\ntransfers: []\nsubprocessors:\n  url: null\n  text: A current list is available on request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@apinizer.com\n  text: To exercise any of these rights, email privacy@apinizer.com\nrights:\n- right: access, correct, delete, restrict, object, portability\n  text: access the personal data we hold about you, correct it, delete it, restrict its processing, object to processing,\n    and request portability.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apinizer/privacy/apinizer-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 11 quoted statements, read from Apinizer's own page on 2026-11-09.
synthetic: false
tags:
- API Gateway
- API Management
- API Monitoring
- API Security
- Policies
---
