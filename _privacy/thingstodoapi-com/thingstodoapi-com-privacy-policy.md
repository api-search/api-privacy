---
api_specs:
- filename: thingstodoapi-com-coverage-api-openapi.yml
  format: yaml
  label: thingstodoapi-com Coverage API
  slug: thingstodoapi-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingstodoapi-com/openapi/thingstodoapi-com-coverage-api-openapi.yml
- filename: thingstodoapi-com-events-api-openapi.yml
  format: yaml
  label: thingstodoapi-com Events API
  slug: thingstodoapi-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingstodoapi-com/openapi/thingstodoapi-com-events-api-openapi.yml
- filename: thingstodoapi-com-keys-api-openapi.yml
  format: yaml
  label: thingstodoapi-com Keys API
  slug: thingstodoapi-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingstodoapi-com/openapi/thingstodoapi-com-keys-api-openapi.yml
- filename: thingstodoapi-com-mcp-api-openapi.yml
  format: yaml
  label: thingstodoapi-com MCP API
  slug: thingstodoapi-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingstodoapi-com/openapi/thingstodoapi-com-mcp-api-openapi.yml
- filename: thingstodoapi-com-search-api-openapi.yml
  format: yaml
  label: thingstodoapi-com Search API
  slug: thingstodoapi-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thingstodoapi-com/openapi/thingstodoapi-com-search-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: We keep your email and a hash of your password, for your account
  - category: identifying
    text: a hash of your address, to count calls made without a key
  - category: behavioral
    text: your queries for 30 days, to improve results
  - category: financial
    text: Payments are handled by Stripe, which keeps your card; we never see it.
  deletion:
    route: email request to contact@thingstodoapi.com
    text: To see or delete what we keep about you, write to contact@thingstodoapi.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account
    text: We keep your email and a hash of your password, for your account
  - purpose: rate counting
    text: a hash of your address, to count calls made without a key
  - purpose: improve results
    text: your queries for 30 days, to improve results
  retention:
  - period: 30 days
    scope: queries
    text: your queries for 30 days, to improve results
  rights:
  - right: access
    text: To see or delete what we keep about you, write to contact@thingstodoapi.com .
  - right: deletion
    text: To see or delete what we keep about you, write to contact@thingstodoapi.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Nothing is sold.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: thingstodoapi-com
provenance_date: '2026-11-10'
provider_name: thingstodoapi-com
provider_slug: thingstodoapi-com
slug: thingstodoapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: thingstodoapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thingstodoapi.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: thingstodoapi-com\naid: thingstodoapi-com\nurl: https://thingstodoapi.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We keep your email and a hash of your password, for your account\n- category: identifying\n  text: a hash of your address, to count calls made without a key\n- category: behavioral\n  text: your queries for 30 days, to improve results\n- category: financial\n  text: Payments are handled by Stripe, which keeps your card; we never see it.\npurposes:\n- purpose: account\n  text: We keep your email and a hash of your\
  \ password, for your account\n- purpose: rate counting\n  text: a hash of your address, to count calls made without a key\n- purpose: improve results\n  text: your queries for 30 days, to improve results\nretention:\n- scope: queries\n  period: 30 days\n  text: your queries for 30 days, to improve results\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to contact@thingstodoapi.com\n  text: To see or delete what we keep about you, write to contact@thingstodoapi.com .\nrights:\n- right: access\n  text: To see or delete what we keep about you, write to contact@thingstodoapi.com .\n- right: deletion\n  text: To see or delete what we keep about you, write to contact@thingstodoapi.com .\nsale_or_sharing:\n  stance: prohibited\n  text: Nothing is sold.\n"
source_yaml_url: https://artifacts.apis.io/thingstodoapi-com/privacy/thingstodoapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from thingstodoapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Event
- Local
- Artificial Intelligence
- JSON
- MCP
---
