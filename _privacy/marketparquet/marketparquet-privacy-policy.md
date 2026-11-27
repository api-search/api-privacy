---
api_specs:
- filename: marketparquet-api-v1-api-openapi.yml
  format: yaml
  label: MarketParquet API V1 API
  slug: marketparquet-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketparquet/openapi/marketparquet-api-v1-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address, a hashed password (never the password itself)
  - category: financial
    text: Billing data -- purchases and subscription status.
  - category: device
    text: standard web-server logs (IP address, user agent, pages requested)
  - category: behavioral
    text: download history (which files, when)
  - category: behavioral
    text: the click identifier (e.g. Google's gclid ) and UTM parameters are stored in a first-party cookie
  deletion:
    route: Email support@marketparquet.com from your account address
    text: Email support@marketparquet.com from your account address to export or delete your account data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sell data files and measure ads
    text: We collect the minimum needed to sell you data files and measure our ads.
  - purpose: security and abuse prevention
    text: kept for security, abuse prevention, and capacity planning
  - purpose: ad attribution
    text: so we can tell which ads actually work
  retention:
  - period: as long as tax law requires afterwards
    scope: account and billing records
    text: Account and billing records are kept while your account exists and as long as tax law requires afterwards
  - period: null
    scope: server logs
    text: server logs rotate on a short schedule
  - period: 90 days
    scope: mp_attrib cookie
    text: expires after 90 days
  - period: 180 days
    scope: mp_vid cookie
    text: expires after 180 days
  rights:
  - right: export
    text: to export or delete your account data
  - right: unsubscribe
    text: every message has an unsubscribe link
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MarketParquet
provenance_date: '2026-11-10'
provider_name: MarketParquet
provider_slug: marketparquet
slug: marketparquet-privacy-policy
source_date: '2026-11-10'
source_filename: marketparquet-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://marketparquet.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MarketParquet\naid: marketparquet\nurl: https://marketparquet.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your email address, a hashed password (never the password itself)\n- category: financial\n  text: Billing data -- purchases and subscription status.\n- category: device\n  text: standard web-server logs (IP address, user agent, pages requested)\n- category: behavioral\n  text: download history (which files, when)\n- category: behavioral\n  text: the click identifier (e.g. Google's gclid ) and UTM parameters are stored\
  \ in a first-party cookie\npurposes:\n- purpose: sell data files and measure ads\n  text: We collect the minimum needed to sell you data files and measure our ads.\n- purpose: security and abuse prevention\n  text: kept for security, abuse prevention, and capacity planning\n- purpose: ad attribution\n  text: so we can tell which ads actually work\nretention:\n- scope: account and billing records\n  period: as long as tax law requires afterwards\n  text: Account and billing records are kept while your account exists and as long as tax law requires afterwards\n- scope: server logs\n  period: null\n  text: server logs rotate on a short schedule\n- scope: mp_attrib cookie\n  period: 90 days\n  text: expires after 90 days\n- scope: mp_vid cookie\n  period: 180 days\n  text: expires after 180 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@marketparquet.com from your account address\n\
  \  text: Email support@marketparquet.com from your account address to export or delete your account data.\nrights:\n- right: export\n  text: to export or delete your account data\n- right: unsubscribe\n  text: every message has an unsubscribe link\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data.\n"
source_yaml_url: https://artifacts.apis.io/marketparquet/privacy/marketparquet-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from MarketParquet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Data
- Market Data
---
