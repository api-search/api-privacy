---
api_specs:
- filename: carbonguru-io-analysis-api-openapi.yml
  format: yaml
  label: CarbonGuru Analysis API
  slug: carbonguru-io-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-analysis-api-openapi.yml
- filename: carbonguru-io-history-api-openapi.yml
  format: yaml
  label: CarbonGuru History API
  slug: carbonguru-io-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-history-api-openapi.yml
- filename: carbonguru-io-offsets-api-openapi.yml
  format: yaml
  label: CarbonGuru Offsets API
  slug: carbonguru-io-offsets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-offsets-api-openapi.yml
- filename: carbonguru-io-reference-api-openapi.yml
  format: yaml
  label: CarbonGuru Reference API
  slug: carbonguru-io-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-reference-api-openapi.yml
- filename: carbonguru-io-service-api-openapi.yml
  format: yaml
  label: CarbonGuru Service API
  slug: carbonguru-io-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-service-api-openapi.yml
- filename: carbonguru-io-store-api-openapi.yml
  format: yaml
  label: CarbonGuru Store API
  slug: carbonguru-io-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-store-api-openapi.yml
- filename: carbonguru-io-webhooks-api-openapi.yml
  format: yaml
  label: CarbonGuru Webhooks API
  slug: carbonguru-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carbonguru-io/openapi/carbonguru-io-webhooks-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address, display name, and password to create and secure your account
  - category: behavioral
    text: we collect anonymous usage events on carbonguru.io — pages viewed and interactions such as button clicks
  - category: financial
    text: we process the order details needed to buy and retire the corresponding carbon credits (item, amount, and an order reference)
  - category: communication
    text: we request read-only access (the gmail.readonly scope)
  deletion:
    route: Request deletion through account or support contact
    text: Deletion — request deletion of your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Calculate carbon footprints
    text: Calculate the carbon footprint of products and shopping carts
  - purpose: Improve website
    text: Understand how our website and features are used, so we can improve them (anonymous product analytics)
  - purpose: Offset fulfillment
    text: when you purchase offsets or removals, we share your name (for certificate attribution), carbon amount, and order details with our fulfillment providers
  residency:
  - region: European Union
    text: PostHog processes this data on servers in the European Union
  retention:
  - period: while your account is active
    scope: Account data
    text: Account data — retained while your account is active
  - period: null
    scope: Email content
    text: Email content — not retained. Raw email HTML is processed in memory and discarded immediately after extraction
  - period: while your Gmail connection is active
    scope: Gmail OAuth tokens
    text: Gmail OAuth tokens — encrypted and retained while your Gmail connection is active.
  rights:
  - right: Access
    text: Access — request a copy of the data we hold about you
  - right: Deletion
    text: Deletion — request deletion of your account and associated data
  - right: Revoke Gmail access
    text: Revoke Gmail access — disconnect Gmail through your account settings or via Google Account Permissions
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: AI service providers that act as sub-processors on our behalf
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CarbonGuru
provenance_date: '2026-11-09'
provider_name: CarbonGuru
provider_slug: carbonguru-io
slug: carbonguru-io-privacy-policy
source_date: '2026-11-09'
source_filename: carbonguru-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carbonguru.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CarbonGuru\naid: carbonguru-io\nurl: https://carbonguru.io/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your email address, display name, and password to create and secure your account\n- category: behavioral\n  text: we collect anonymous usage events on carbonguru.io — pages viewed and interactions such as button clicks\n- category: financial\n  text: we process the order details needed to buy and retire the corresponding carbon credits (item, amount, and\n    an order reference)\n- category: communication\n  text:\
  \ we request read-only access (the gmail.readonly scope)\npurposes:\n- purpose: Calculate carbon footprints\n  text: Calculate the carbon footprint of products and shopping carts\n- purpose: Improve website\n  text: Understand how our website and features are used, so we can improve them (anonymous product analytics)\n- purpose: Offset fulfillment\n  text: when you purchase offsets or removals, we share your name (for certificate attribution), carbon amount,\n    and order details with our fulfillment providers\nretention:\n- scope: Account data\n  period: while your account is active\n  text: Account data — retained while your account is active\n- scope: Email content\n  period: null\n  text: Email content — not retained. Raw email HTML is processed in memory and discarded immediately after extraction\n- scope: Gmail OAuth tokens\n  period: while your Gmail connection is active\n  text: Gmail OAuth tokens — encrypted and retained while your Gmail connection is active.\nresidency:\n- region:\
  \ European Union\n  text: PostHog processes this data on servers in the European Union\ntransfers: []\nsubprocessors:\n  url: null\n  text: AI service providers that act as sub-processors on our behalf\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion through account or support contact\n  text: Deletion — request deletion of your account and associated data\nrights:\n- right: Access\n  text: Access — request a copy of the data we hold about you\n- right: Deletion\n  text: Deletion — request deletion of your account and associated data\n- right: Revoke Gmail access\n  text: Revoke Gmail access — disconnect Gmail through your account settings or via Google Account Permissions\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/carbonguru-io/privacy/carbonguru-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from CarbonGuru's own page on 2026-11-09.
synthetic: false
tags:
- Carbon Footprinting
- Automated Offsetting
- E-Commerce
- Marketplace
- B2B
- Consumer
- Sustainability
---
