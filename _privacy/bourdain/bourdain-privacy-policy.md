---
api_specs:
- filename: bourdain-acp-checkout-api-openapi.yml
  format: yaml
  label: Bourdain Acp Checkout API
  slug: bourdain-acp-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-checkout-api-openapi.yml
- filename: bourdain-acp-confirm-api-openapi.yml
  format: yaml
  label: Bourdain Acp Confirm API
  slug: bourdain-acp-confirm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-confirm-api-openapi.yml
- filename: bourdain-acp-payment-api-openapi.yml
  format: yaml
  label: Bourdain Acp Payment API
  slug: bourdain-acp-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-payment-api-openapi.yml
- filename: bourdain-acp-product-api-openapi.yml
  format: yaml
  label: Bourdain Acp Product API
  slug: bourdain-acp-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-product-api-openapi.yml
- filename: bourdain-acp-products-api-openapi.yml
  format: yaml
  label: Bourdain Acp Products API
  slug: bourdain-acp-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-acp-products-api-openapi.yml
- filename: bourdain-mcp-server-api-openapi.yml
  format: yaml
  label: Bourdain Mcp Server API
  slug: bourdain-mcp-server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bourdain/openapi/bourdain-mcp-server-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, phone number, date of birth, and password'
  - category: location
    text: 'Location Data: General location based on IP address (with your consent)'
  - category: financial
    text: 'Payment Information: Bank account details, payment method information (processed securely through Stripe)'
  - category: behavioral
    text: 'Usage Data: Pages visited, time spent, clicks, search queries'
  - category: device
    text: 'Device Information: IP address, browser type, operating system, device identifiers'
  - category: communication
    text: 'Communication: Messages sent through the Platform, support requests'
  deletion:
    route: Account settings or request to provider
    text: You may request deletion of your account and personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve platform services
    text: Provide, maintain, and improve our Platform services
  - purpose: Process transactions and payments
    text: Process transactions and facilitate payments
  - purpose: Marketing communications
    text: Send you marketing communications (with your consent)
  - purpose: Fraud prevention and identity verification
    text: Verify your identity and prevent fraud
  retention:
  - period: 30 days
    scope: Account deletion
    text: When you delete your account, we will delete or anonymize your personal data within 30 days, except where we are required to retain it for legal purposes.
  rights:
  - right: Access
    text: Right to access your personal data
  - right: Rectification
    text: Right to rectification of inaccurate data
  - right: Erasure
    text: Right to erasure ("right to be forgotten")
  - right: Restrict processing
    text: Right to restrict processing
  - right: Data portability
    text: Right to data portability
  - right: Object to processing
    text: Right to object to processing
  - right: Withdraw consent
    text: Right to withdraw consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Supabase: Database and authentication services'
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for such transfers in accordance with applicable data protection laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bourdain
provenance_date: '2026-11-09'
provider_name: Bourdain
provider_slug: bourdain
slug: bourdain-privacy-policy
source_date: '2026-11-09'
source_filename: bourdain-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bourdain.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bourdain\naid: bourdain\nurl: https://www.bourdain.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, phone number, date of birth, and password'\n- category: location\n  text: 'Location Data: General location based on IP address (with your consent)'\n- category: financial\n  text: 'Payment Information: Bank account details, payment method information (processed securely through Stripe)'\n- category: behavioral\n  text: 'Usage Data: Pages visited, time spent, clicks, search queries'\n- category:\
  \ device\n  text: 'Device Information: IP address, browser type, operating system, device identifiers'\n- category: communication\n  text: 'Communication: Messages sent through the Platform, support requests'\npurposes:\n- purpose: Provide and improve platform services\n  text: Provide, maintain, and improve our Platform services\n- purpose: Process transactions and payments\n  text: Process transactions and facilitate payments\n- purpose: Marketing communications\n  text: Send you marketing communications (with your consent)\n- purpose: Fraud prevention and identity verification\n  text: Verify your identity and prevent fraud\nretention:\n- scope: Account deletion\n  period: 30 days\n  text: When you delete your account, we will delete or anonymize your personal data within 30 days, except where\n    we are required to retain it for legal purposes.\nresidency: []\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place for such transfers in accordance with\
  \ applicable data protection\n    laws.\nsubprocessors:\n  url: null\n  text: 'Supabase: Database and authentication services'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or request to provider\n  text: You may request deletion of your account and personal data.\nrights:\n- right: Access\n  text: Right to access your personal data\n- right: Rectification\n  text: Right to rectification of inaccurate data\n- right: Erasure\n  text: Right to erasure (\"right to be forgotten\")\n- right: Restrict processing\n  text: Right to restrict processing\n- right: Data portability\n  text: Right to data portability\n- right: Object to processing\n  text: Right to object to processing\n- right: Withdraw consent\n  text: Right to withdraw consent\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bourdain/privacy/bourdain-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 21 quoted statements, read from Bourdain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Trading Cards
- Artificial Intelligence
- E-Commerce
- Collectibles
---
