---
api_specs:
- filename: patternfetch-com-api-openapi.json
  format: json
  label: patternfetch Api API
  slug: patternfetch-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/patternfetch-com/openapi/_original/patternfetch-com-api-openapi.json
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address. Minting an API key at POST /v1/keys requires a valid email address.
  - category: contact
    text: Email address. Minting an API key at POST /v1/keys requires a valid email address.
  - category: device
    text: the requesting IP address, a coarse client classification, and the User-Agent string (truncated)
  - category: behavioral
    text: For market-data calls the requested ticker and timeframe are stored.
  - category: financial
    text: For paying accounts the account row holds the plan, its status, the included allowance, the period end, and the Stripe customer and subscription identifiers.
  - category: communication
    text: Newsletter opt-in is off by default; only an explicit opt-in is counted.
  deletion:
    route: No automated self-service deletion; removal by hand
    text: There is no automated self-service route that deletes an account or erases its stored data; the system does not do that on its own today.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Issue one-time free starter credit
    text: The normalized form is the identity used to hand out the one-time free starter credit once per address.
  - purpose: Signup abuse detection
    text: The hash exists only so the operator can count how many keys came from one origin when looking for signup abuse
  - purpose: Excluding internal testing traffic from analytics
    text: The operator's own IP addresses are recorded in a separate list so that internal testing traffic can be excluded from the product's own usage analytics.
  - purpose: Card payments and subscriptions
    text: patternfetch creates a Checkout or billing-portal session and passes Stripe only the internal account identifier as metadata, the amount, and the product name.
  retention:
  - period: null
    scope: Request logs, account rows and payment records
    text: Request logs, account rows and payment records remain until removed by hand.
  rights:
  - right: Unsubscribe from newsletter
    text: Newsletter mail carries an unsubscribe link, and unsubscribing is self-service
  - right: Rotate API key
    text: An API key can be rotated through the recovery flow.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: patternfetch-com
provenance_date: '2026-11-10'
provider_name: patternfetch-com
provider_slug: patternfetch-com
slug: patternfetch-com-privacy-policy
source_date: '2026-11-10'
source_filename: patternfetch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://patternfetch.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: patternfetch-com\naid: patternfetch-com\nurl: https://patternfetch.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address. Minting an API key at POST /v1/keys requires a valid email address.\n- category: contact\n  text: Email address. Minting an API key at POST /v1/keys requires a valid email address.\n- category: device\n  text: the requesting IP address, a coarse client classification, and the User-Agent string (truncated)\n- category: behavioral\n  text: For market-data calls the requested ticker and timeframe are\
  \ stored.\n- category: financial\n  text: For paying accounts the account row holds the plan, its status, the included allowance, the period end,\n    and the Stripe customer and subscription identifiers.\n- category: communication\n  text: Newsletter opt-in is off by default; only an explicit opt-in is counted.\npurposes:\n- purpose: Issue one-time free starter credit\n  text: The normalized form is the identity used to hand out the one-time free starter credit once per address.\n- purpose: Signup abuse detection\n  text: The hash exists only so the operator can count how many keys came from one origin when looking for signup\n    abuse\n- purpose: Excluding internal testing traffic from analytics\n  text: The operator's own IP addresses are recorded in a separate list so that internal testing traffic can be\n    excluded from the product's own usage analytics.\n- purpose: Card payments and subscriptions\n  text: patternfetch creates a Checkout or billing-portal session and passes Stripe\
  \ only the internal account identifier\n    as metadata, the amount, and the product name.\nretention:\n- scope: Request logs, account rows and payment records\n  period: null\n  text: Request logs, account rows and payment records remain until removed by hand.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: No automated self-service deletion; removal by hand\n  text: There is no automated self-service route that deletes an account or erases its stored data; the system does\n    not do that on its own today.\nrights:\n- right: Unsubscribe from newsletter\n  text: Newsletter mail carries an unsubscribe link, and unsubscribing is self-service\n- right: Rotate API key\n  text: An API key can be rotated through the recovery flow.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/patternfetch-com/privacy/patternfetch-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from patternfetch-com's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Market Data
- Stocks
- Cryptocurrency
---
