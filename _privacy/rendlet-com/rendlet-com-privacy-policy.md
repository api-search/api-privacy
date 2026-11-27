---
api_specs:
- filename: rendlet-com-checkout-api-openapi.yml
  format: yaml
  label: rendlet-com Checkout API
  slug: rendlet-com-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-checkout-api-openapi.yml
- filename: rendlet-com-pdf-api-openapi.yml
  format: yaml
  label: rendlet-com PDF API
  slug: rendlet-com-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-pdf-api-openapi.yml
- filename: rendlet-com-signup-api-openapi.yml
  format: yaml
  label: rendlet-com Signup API
  slug: rendlet-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-signup-api-openapi.yml
- filename: rendlet-com-templates-api-openapi.yml
  format: yaml
  label: rendlet-com Templates API
  slug: rendlet-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-templates-api-openapi.yml
- filename: rendlet-com-usage-api-openapi.yml
  format: yaml
  label: rendlet-com Usage API
  slug: rendlet-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendlet-com/openapi/rendlet-com-usage-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Signup: your email address and, if you fill them in, your use case, expected volume and the plan you''re interested in.'
  - category: identifying
    text: A truncated SHA-256 hash of your IP address is stored to limit signups per network.
  - category: financial
    text: your plan, your prepaid credit balance and the account email
  - category: behavioral
    text: a monthly count of documents per key
  - category: device
    text: PostHog stores a random visitor ID in your browser's localStorage, not a cookie, and receives your IP address and browser details with each event.
  deletion:
    route: email support@rendlet.com
    text: To request access or deletion, email support@rendlet.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: product analytics
    text: 'Since 2026-10-20 we use PostHog (US cloud) for product analytics: page views and a few button events'
  - purpose: payment processing
    text: Stripe processes card payments, so we never see your card number.
  - purpose: rate limiting
    text: short-lived rate-limit counters keyed by the key hash, or by a hashed IP address for the sandbox key and the free MCP preview.
  retention:
  - period: about two days
    scope: rate-limit counters
    text: Rate-limit counters older than about two days are deleted periodically.
  - period: null
    scope: other data
    text: We haven't set automatic deletion periods for other data.
  rights:
  - right: access
    text: To request access or deletion, email support@rendlet.com .
  - right: deletion
    text: To request access or deletion, email support@rendlet.com .
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
name: rendlet-com
provenance_date: '2026-11-10'
provider_name: rendlet-com
provider_slug: rendlet-com
slug: rendlet-com-privacy-policy
source_date: '2026-11-10'
source_filename: rendlet-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rendlet.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rendlet-com\naid: rendlet-com\nurl: https://rendlet.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Signup: your email address and, if you fill them in, your use case, expected volume and the plan you''re\n    interested in.'\n- category: identifying\n  text: A truncated SHA-256 hash of your IP address is stored to limit signups per network.\n- category: financial\n  text: your plan, your prepaid credit balance and the account email\n- category: behavioral\n  text: a monthly count of documents per key\n- category: device\n  text:\
  \ PostHog stores a random visitor ID in your browser's localStorage, not a cookie, and receives your IP address\n    and browser details with each event.\npurposes:\n- purpose: product analytics\n  text: 'Since 2026-10-20 we use PostHog (US cloud) for product analytics: page views and a few button events'\n- purpose: payment processing\n  text: Stripe processes card payments, so we never see your card number.\n- purpose: rate limiting\n  text: short-lived rate-limit counters keyed by the key hash, or by a hashed IP address for the sandbox key and\n    the free MCP preview.\nretention:\n- scope: rate-limit counters\n  period: about two days\n  text: Rate-limit counters older than about two days are deleted periodically.\n- scope: other data\n  period: null\n  text: We haven't set automatic deletion periods for other data.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@rendlet.com\n\
  \  text: To request access or deletion, email support@rendlet.com .\nrights:\n- right: access\n  text: To request access or deletion, email support@rendlet.com .\n- right: deletion\n  text: To request access or deletion, email support@rendlet.com .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rendlet-com/privacy/rendlet-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from rendlet-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PDF
- Document Generation
- Software-as-a-Service
- Artificial Intelligence
---
