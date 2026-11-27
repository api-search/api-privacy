---
api_specs:
- filename: parseaddr-com-checkout-api-openapi.yml
  format: yaml
  label: parseaddr-com Checkout API
  slug: parseaddr-com-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-checkout-api-openapi.yml
- filename: parseaddr-com-credits-api-openapi.yml
  format: yaml
  label: parseaddr-com Credits API
  slug: parseaddr-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-credits-api-openapi.yml
- filename: parseaddr-com-expand-api-openapi.yml
  format: yaml
  label: parseaddr-com Expand API
  slug: parseaddr-com-expand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-expand-api-openapi.yml
- filename: parseaddr-com-health-api-openapi.yml
  format: yaml
  label: parseaddr-com Health API
  slug: parseaddr-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-health-api-openapi.yml
- filename: parseaddr-com-parse-api-openapi.yml
  format: yaml
  label: parseaddr-com Parse API
  slug: parseaddr-com-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-parse-api-openapi.yml
- filename: parseaddr-com-signup-api-openapi.yml
  format: yaml
  label: parseaddr-com Signup API
  slug: parseaddr-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-signup-api-openapi.yml
- filename: parseaddr-com-usage-api-openapi.yml
  format: yaml
  label: parseaddr-com Usage API
  slug: parseaddr-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseaddr-com/openapi/parseaddr-com-usage-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account: email address, plan, and (for paid plans) a Stripe customer identifier.'
  - category: financial
    text: Payment card details are handled entirely by Stripe ; we never see or store card numbers.
  - category: identifying
    text: 'Usage metadata: API key identifier, timestamp, endpoint called, and call count — used for quotas and billing.'
  deletion:
    route: Email privacy@parseaddr.com
    text: you may request access to, correction of, or deletion of your account data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the API
    text: We process account and usage metadata to perform our contract with you (providing the API)
  - purpose: Operating and securing the service
    text: for our legitimate interest in operating and securing the service
  - purpose: Billing and quotas
    text: used for quotas and billing
  retention:
  - period: none (in-memory only)
    scope: Address content
    text: 'Address content: none (in-memory only).'
  - period: null
    scope: Account and usage metadata
    text: 'Account and usage metadata: retained while your account is active and for as long as required for billing, tax, and legal obligations, then deleted.'
  rights:
  - right: Access
    text: you may request access to, correction of, or deletion of your account data
  - right: Correction
    text: correction of, or deletion of your account data
  - right: Deletion
    text: deletion of your account data
  - right: Object or restrict
    text: may object to or restrict processing
  - right: Complain to regulator
    text: You may also complain to the UK Information Commissioner's Office (ICO).
  role:
    text: we act as a data processor for the address content our customers send, and as a controller for the limited account data described below
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Stripe — payments and billing. Our hosting provider — compute for the API (transient request processing only).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: parseaddr-com
provenance_date: '2026-11-10'
provider_name: parseaddr-com
provider_slug: parseaddr-com
slug: parseaddr-com-privacy-policy
source_date: '2026-11-10'
source_filename: parseaddr-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://parseaddr.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: parseaddr-com\naid: parseaddr-com\nurl: https://parseaddr.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a data processor for the address content our customers send, and as a controller for the limited\n    account data described below\ndata_categories:\n- category: contact\n  text: 'Account: email address, plan, and (for paid plans) a Stripe customer identifier.'\n- category: financial\n  text: Payment card details are handled entirely by Stripe ; we never see or store card numbers.\n- category: identifying\n  text: 'Usage metadata: API key identifier, timestamp, endpoint\
  \ called, and call count — used for quotas and billing.'\npurposes:\n- purpose: Providing the API\n  text: We process account and usage metadata to perform our contract with you (providing the API)\n- purpose: Operating and securing the service\n  text: for our legitimate interest in operating and securing the service\n- purpose: Billing and quotas\n  text: used for quotas and billing\nretention:\n- scope: Address content\n  period: none (in-memory only)\n  text: 'Address content: none (in-memory only).'\n- scope: Account and usage metadata\n  period: null\n  text: 'Account and usage metadata: retained while your account is active and for as long as required for billing,\n    tax, and legal obligations, then deleted.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe — payments and billing. Our hosting provider — compute for the API (transient request processing\n    only).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@parseaddr.com\n\
  \  text: you may request access to, correction of, or deletion of your account data\nrights:\n- right: Access\n  text: you may request access to, correction of, or deletion of your account data\n- right: Correction\n  text: correction of, or deletion of your account data\n- right: Deletion\n  text: deletion of your account data\n- right: Object or restrict\n  text: may object to or restrict processing\n- right: Complain to regulator\n  text: You may also complain to the UK Information Commissioner's Office (ICO).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/parseaddr-com/privacy/parseaddr-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from parseaddr-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Address
- Parsing
- libpostal
---
