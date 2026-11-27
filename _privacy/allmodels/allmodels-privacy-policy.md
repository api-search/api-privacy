---
api_specs:
- filename: allmodels-account-api-openapi.yml
  format: yaml
  label: Allmodels Account API
  slug: allmodels-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-account-api-openapi.yml
- filename: allmodels-allmodels-api-api-openapi.yml
  format: yaml
  label: Allmodels Allmodels API
  slug: allmodels-allmodels-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-allmodels-api-api-openapi.yml
- filename: allmodels-custom-voices-api-openapi.yml
  format: yaml
  label: Allmodels Custom Voices API
  slug: allmodels-custom-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-custom-voices-api-openapi.yml
- filename: allmodels-el-api-openapi.yml
  format: yaml
  label: Allmodels El API
  slug: allmodels-el-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-el-api-openapi.yml
- filename: allmodels-health-api-openapi.yml
  format: yaml
  label: Allmodels Health API
  slug: allmodels-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-health-api-openapi.yml
- filename: allmodels-oai-api-openapi.yml
  format: yaml
  label: Allmodels Oai API
  slug: allmodels-oai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-oai-api-openapi.yml
- filename: allmodels-realtime-api-openapi.yml
  format: yaml
  label: Allmodels Realtime API
  slug: allmodels-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allmodels/openapi/allmodels-realtime-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account information: your email address and basic account details.'
  - category: financial
    text: 'Payment information: Stripe handles payment-card information.'
  - category: communication
    text: 'Communications: information you send when you contact us for support, privacy requests, or other questions.'
  - category: other
    text: 'Requests and results: we process the prompts, inputs, files, and other data you send so we can route them to a provider and return the result.'
  - category: device
    text: 'Service information: ordinary server logs and usage information needed to operate, secure, troubleshoot, and understand the quality of the Service.'
  deletion:
    route: Request via email or account deletion
    text: You may ask us to delete your account and associated data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account, routing, billing and security
    text: 'We use information to: create and manage accounts; route requests, return results, and calculate usage;'
  residency:
  - region: United States and other countries
    text: We and the providers and service providers we use may process information in the United States and other countries.
  retention:
  - period: null
    scope: Account, transaction, usage and service information
    text: We keep account, transaction, usage, and service information only for as long as reasonably needed to provide the Service
  rights:
  - right: Access, correction and deletion
    text: You may contact us to request access to, correction of, or deletion of your personal information.
  - right: Copy of account information
    text: You may also ask for a copy of information associated with your account.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or share it for behavioral advertising.
  subprocessors:
    text: Stripe processes payments for us.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Allmodels
provenance_date: '2026-11-09'
provider_name: Allmodels
provider_slug: allmodels
slug: allmodels-privacy-policy
source_date: '2026-11-09'
source_filename: allmodels-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://allmodels.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Allmodels\naid: allmodels\nurl: https://allmodels.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account information: your email address and basic account details.'\n- category: financial\n  text: 'Payment information: Stripe handles payment-card information.'\n- category: communication\n  text: 'Communications: information you send when you contact us for support, privacy requests, or other questions.'\n- category: other\n  text: 'Requests and results: we process the prompts, inputs, files, and other data you send so we can route\
  \ them\n    to a provider and return the result.'\n- category: device\n  text: 'Service information: ordinary server logs and usage information needed to operate, secure, troubleshoot,\n    and understand the quality of the Service.'\npurposes:\n- purpose: Account, routing, billing and security\n  text: 'We use information to: create and manage accounts; route requests, return results, and calculate usage;'\nretention:\n- scope: Account, transaction, usage and service information\n  period: null\n  text: We keep account, transaction, usage, and service information only for as long as reasonably needed to provide\n    the Service\nresidency:\n- region: United States and other countries\n  text: We and the providers and service providers we use may process information in the United States and other\n    countries.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe processes payments for us.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via email\
  \ or account deletion\n  text: You may ask us to delete your account and associated data.\nrights:\n- right: Access, correction and deletion\n  text: You may contact us to request access to, correction of, or deletion of your personal information.\n- right: Copy of account information\n  text: You may also ask for a copy of information associated with your account.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or share it for behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/allmodels/privacy/allmodels-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Allmodels's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Text-to-Speech
- Speech-to-Text
- Real-Time
---
