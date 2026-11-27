---
api_specs:
- filename: keyo-authentication-api-openapi.yml
  format: yaml
  label: Keyo Authentication API
  slug: keyo-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyo/openapi/keyo-authentication-api-openapi.yml
- filename: keyo-identities-api-openapi.yml
  format: yaml
  label: Keyo Identities API
  slug: keyo-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyo/openapi/keyo-identities-api-openapi.yml
claim_count: 3
description: ''
doc:
  deletion:
    route: user dashboard or mobile app
    text: delete your account right from your personal dashboard or mobile app
  dpa:
    available: null
    text: null
    url: null
  rights:
  - right: access to account activity and scan history
    text: Request account activity, see scan history
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Keyo does not and will never sell your information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Keyo
provenance_date: '2026-11-09'
provider_name: Keyo
provider_slug: keyo
slug: keyo-privacy-policy
source_date: '2026-11-09'
source_filename: keyo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://keyo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Keyo\naid: keyo\nurl: https://keyo.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories: []\npurposes: []\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: user dashboard or mobile app\n  text: delete your account right from your personal dashboard or mobile app\nrights:\n- right: access to account activity and scan history\n  text: Request account activity, see scan history\nsale_or_sharing:\n  stance: prohibited\n  text: Keyo does not and will never sell\
  \ your information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/keyo/privacy/keyo-privacy-policy.yml
stated_fields:
- deletion
- rights
- sale_or_sharing
summary_line: 3 quoted statements, read from Keyo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biometrics
- Identity
- Authentication
- Palm Recognition
- Access Control
- Payments
- Identity Verification
---
