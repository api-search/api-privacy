---
api_specs:
- filename: hermai-api-openapi.json
  format: json
  label: Hermai Agent-Native API API
  slug: hermai-agent-native-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hermai/openapi/_original/hermai-api-openapi.json
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we store the basic profile details returned by your chosen sign in method, such as your name, email, user ID, and provider username.
  - category: device
    text: Each API call is logged with operational metadata such as key ID, timestamp, endpoint, status code, latency, and IP address for rate limiting, abuse prevention, billing, and debugging.
  - category: behavioral
    text: Trevo receives event names, timestamps, selected event properties, an anonymous first party identifier and, when you are signed in, your Hermai user ID.
  - category: location
    text: Coarse geo (country-level)
  - category: identifying
    text: identify business visitors by name, business email, phone number, and LinkedIn profile, even if you do not submit a form.
  deletion:
    route: email
    text: To opt out or request deletion, email kingsong@hermai.ai .
  dpa:
    available: null
    text: Subprocessors operate under their own security and privacy commitments or data-processing terms
    url: null
  purposes:
  - purpose: provide, secure, debug, and bill the service
    text: Your request data is used to provide, secure, debug, and bill the service, not to train Hermai or third-party models.
  - purpose: business to business sales and marketing outreach
    text: We use this only for business to business sales and marketing outreach.
  - purpose: run and measure product experiments
    text: Trevo processes this data on our behalf to assign experiment variants and measure results.
  residency:
  - region: United States
    text: Our primary hosted API and fetch infrastructure currently runs in the United States.
  rights:
  - right: access
    text: Email kingsong@hermai.ai for privacy questions or access requests.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data. We do not sell your personal data or your individual request data.
  subprocessors:
    text: enterprise customers can request the current subprocessor list during review.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hermai Brand API
provenance_date: '2026-11-09'
provider_name: Hermai Brand API
provider_slug: hermai
slug: hermai-privacy-policy
source_date: '2026-11-09'
source_filename: hermai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hermai.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hermai Brand API\naid: hermai\nurl: https://hermai.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we store the basic profile details returned by your chosen sign in method, such\n    as your name, email, user ID, and provider username.\n- category: device\n  text: Each API call is logged with operational metadata such as key ID, timestamp, endpoint, status code, latency,\n    and IP address for rate limiting, abuse prevention, billing, and debugging.\n- category: behavioral\n  text: Trevo receives\
  \ event names, timestamps, selected event properties, an anonymous first party identifier and,\n    when you are signed in, your Hermai user ID.\n- category: location\n  text: Coarse geo (country-level)\n- category: identifying\n  text: identify business visitors by name, business email, phone number, and LinkedIn profile, even if you do not\n    submit a form.\npurposes:\n- purpose: provide, secure, debug, and bill the service\n  text: Your request data is used to provide, secure, debug, and bill the service, not to train Hermai or third-party\n    models.\n- purpose: business to business sales and marketing outreach\n  text: We use this only for business to business sales and marketing outreach.\n- purpose: run and measure product experiments\n  text: Trevo processes this data on our behalf to assign experiment variants and measure results.\nretention: []\nresidency:\n- region: United States\n  text: Our primary hosted API and fetch infrastructure currently runs in the United States.\n\
  transfers: []\nsubprocessors:\n  url: null\n  text: enterprise customers can request the current subprocessor list during review.\ndpa:\n  available: null\n  url: null\n  text: Subprocessors operate under their own security and privacy commitments or data-processing terms\ndeletion:\n  route: email\n  text: To opt out or request deletion, email kingsong@hermai.ai .\nrights:\n- right: access\n  text: Email kingsong@hermai.ai for privacy questions or access requests.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data. We do not sell your personal data or your individual request data.\n"
source_yaml_url: https://artifacts.apis.io/hermai/privacy/hermai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Hermai Brand API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Branding
- Marketing
- Software-as-a-Service
---
