---
api_specs:
- filename: carstat-app-recalls-api-openapi.yml
  format: yaml
  label: carstat-app Recalls API
  slug: carstat-app-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-recalls-api-openapi.yml
- filename: carstat-app-safety-ratings-api-openapi.yml
  format: yaml
  label: carstat-app Safety Ratings API
  slug: carstat-app-safety-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-safety-ratings-api-openapi.yml
- filename: carstat-app-vehicle-specifications-api-openapi.yml
  format: yaml
  label: carstat-app Vehicle Specifications API
  slug: carstat-app-vehicle-specifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-vehicle-specifications-api-openapi.yml
- filename: carstat-app-vin-decoding-api-openapi.yml
  format: yaml
  label: carstat-app VIN Decoding API
  slug: carstat-app-vin-decoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carstat-app/openapi/carstat-app-vin-decoding-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and password used to secure your account.
  - category: financial
    text: If you purchase prepaid credits, payment processing is handled by an authorized third-party provider.
  - category: behavioral
    text: Logs of your API requests (timestamps and endpoints) to manage rate limits and billing.
  - category: other
    text: we store the vehicles you save (including VIN, make, model, year, trim and any nickname you set)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication
    text: To authenticate your access to the Services.
  - purpose: Support and security alerts
    text: To provide technical support and security alerts regarding your account.
  - purpose: Prepaid credit transactions
    text: To process transactions for your prepaid credit purchases.
  - purpose: Functional communications
    text: Your email address is used exclusively for functional communications (e.g., password resets, billing receipts, or critical API updates).
  retention:
  - period: null
    scope: Credit payment and ledger records
    text: Credit payment and ledger records, including the original buyer ID and a normalized-email eligibility fingerprint, are retained after account deletion for payment reconciliation, auditing and preventing repeated introductory offers.
  - period: 12 months
    scope: Purchased or promotional credits
    text: Credits expire 12 months after they are added to your account, whether purchased or promotional
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal data to advertisers. We never share your personal data with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: carstat-app
provenance_date: '2026-11-09'
provider_name: carstat-app
provider_slug: carstat-app
slug: carstat-app-privacy-policy
source_date: '2026-11-09'
source_filename: carstat-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carstat.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: carstat-app\naid: carstat-app\nurl: https://carstat.app/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address and password used to secure your account.\n- category: financial\n  text: If you purchase prepaid credits, payment processing is handled by an authorized third-party provider.\n- category: behavioral\n  text: Logs of your API requests (timestamps and endpoints) to manage rate limits and billing.\n- category: other\n  text: we store the vehicles you save (including VIN, make, model, year, trim and any\
  \ nickname you set)\npurposes:\n- purpose: Authentication\n  text: To authenticate your access to the Services.\n- purpose: Support and security alerts\n  text: To provide technical support and security alerts regarding your account.\n- purpose: Prepaid credit transactions\n  text: To process transactions for your prepaid credit purchases.\n- purpose: Functional communications\n  text: Your email address is used exclusively for functional communications (e.g., password resets, billing receipts,\n    or critical API updates).\nretention:\n- scope: Credit payment and ledger records\n  period: null\n  text: Credit payment and ledger records, including the original buyer ID and a normalized-email eligibility fingerprint,\n    are retained after account deletion for payment reconciliation, auditing and preventing repeated introductory\n    offers.\n- scope: Purchased or promotional credits\n  period: 12 months\n  text: Credits expire 12 months after they are added to your account, whether purchased\
  \ or promotional\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal data to advertisers. We never share your personal data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/carstat-app/privacy/carstat-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 11 quoted statements, read from carstat-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Data
- Vehicles
---
