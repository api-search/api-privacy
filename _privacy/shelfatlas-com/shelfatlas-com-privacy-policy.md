---
api_specs:
- filename: shelfatlas-com-chains-api-openapi.yml
  format: yaml
  label: shelfatlas-com Chains API
  slug: shelfatlas-com-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-chains-api-openapi.yml
- filename: shelfatlas-com-mcp-api-openapi.yml
  format: yaml
  label: shelfatlas-com MCP API
  slug: shelfatlas-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-mcp-api-openapi.yml
- filename: shelfatlas-com-observations-api-openapi.yml
  format: yaml
  label: shelfatlas-com Observations API
  slug: shelfatlas-com-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-observations-api-openapi.yml
- filename: shelfatlas-com-observedprices-api-openapi.yml
  format: yaml
  label: shelfatlas-com Observed Prices API
  slug: shelfatlas-com-observedprices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-observedprices-api-openapi.yml
- filename: shelfatlas-com-offers-api-openapi.yml
  format: yaml
  label: shelfatlas-com Offers API
  slug: shelfatlas-com-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-offers-api-openapi.yml
- filename: shelfatlas-com-price-history-api-openapi.yml
  format: yaml
  label: shelfatlas-com Price history API
  slug: shelfatlas-com-price-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-price-history-api-openapi.yml
- filename: shelfatlas-com-products-api-openapi.yml
  format: yaml
  label: shelfatlas-com Products API
  slug: shelfatlas-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-products-api-openapi.yml
- filename: shelfatlas-com-seoterms-api-openapi.yml
  format: yaml
  label: shelfatlas-com Seo Terms API
  slug: shelfatlas-com-seoterms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-seoterms-api-openapi.yml
- filename: shelfatlas-com-stats-api-openapi.yml
  format: yaml
  label: shelfatlas-com Stats API
  slug: shelfatlas-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-stats-api-openapi.yml
- filename: shelfatlas-com-stores-api-openapi.yml
  format: yaml
  label: shelfatlas-com Stores API
  slug: shelfatlas-com-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shelfatlas-com/openapi/shelfatlas-com-stores-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: our authentication provider (Clerk) processes the email address and name you provide
  - category: financial
    text: Stripe handles the payment and the billing details you give it (name, email, card)
  - category: device
    text: Standard server logs (Cloudflare) and error monitoring (Sentry) may briefly capture technical request details, including IP addresses
  deletion:
    route: Deleting your account
    text: Deleting your account removes your account data and revokes your API keys.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate account and issue API keys
    text: We use it to operate your account and issue API keys
  - purpose: API usage counting
    text: We count requests per API key (for rate limits, quotas, and understanding usage)
  - purpose: operations
    text: They are used for operations only.
  rights:
  - right: access
    text: you can request access to, correction of, or deletion of your personal data
  - right: correction
    text: you can request access to, correction of, or deletion of your personal data
  - right: deletion
    text: you can request access to, correction of, or deletion of your personal data
  - right: complain to supervisory authority
    text: you have the right to complain to the Danish data protection authority, Datatilsynet
  role:
    text: Henrik Lambert , Odense, Denmark, is the data controller for ShelfAtlas.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No selling or sharing of personal data with third parties for their own purposes.
  subprocessors:
    text: Processors we rely on Clerk (authentication), Cloudflare (hosting), Supabase (database), Sentry (error monitoring), Resend (email delivery), Stripe (payments), and GitHub (scheduled jobs).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: shelfatlas-com
provenance_date: '2026-11-10'
provider_name: shelfatlas-com
provider_slug: shelfatlas-com
slug: shelfatlas-com-privacy-policy
source_date: '2026-11-10'
source_filename: shelfatlas-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shelfatlas.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: shelfatlas-com\naid: shelfatlas-com\nurl: https://shelfatlas.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Henrik Lambert , Odense, Denmark, is the data controller for ShelfAtlas.\ndata_categories:\n- category: identifying\n  text: our authentication provider (Clerk) processes the email address and name you provide\n- category: financial\n  text: Stripe handles the payment and the billing details you give it (name, email, card)\n- category: device\n  text: Standard server logs (Cloudflare) and error monitoring (Sentry) may briefly capture technical request details,\n   \
  \ including IP addresses\npurposes:\n- purpose: operate account and issue API keys\n  text: We use it to operate your account and issue API keys\n- purpose: API usage counting\n  text: We count requests per API key (for rate limits, quotas, and understanding usage)\n- purpose: operations\n  text: They are used for operations only.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors we rely on Clerk (authentication), Cloudflare (hosting), Supabase (database), Sentry (error monitoring),\n    Resend (email delivery), Stripe (payments), and GitHub (scheduled jobs).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deleting your account\n  text: Deleting your account removes your account data and revokes your API keys.\nrights:\n- right: access\n  text: you can request access to, correction of, or deletion of your personal data\n- right: correction\n  text: you can request access to, correction of, or deletion of your personal\
  \ data\n- right: deletion\n  text: you can request access to, correction of, or deletion of your personal data\n- right: complain to supervisory authority\n  text: you have the right to complain to the Danish data protection authority, Datatilsynet\nsale_or_sharing:\n  stance: prohibited\n  text: No selling or sharing of personal data with third parties for their own purposes.\n"
source_yaml_url: https://artifacts.apis.io/shelfatlas-com/privacy/shelfatlas-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from shelfatlas-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Grocery
- Denmark
- Retail
---
