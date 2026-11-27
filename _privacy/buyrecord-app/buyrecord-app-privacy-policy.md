---
api_specs:
- filename: buyrecord-app-keys-api-openapi.yml
  format: yaml
  label: BuyRecord Keys API
  slug: buyrecord-app-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyrecord-app/openapi/buyrecord-app-keys-api-openapi.yml
- filename: buyrecord-app-merchants-api-openapi.yml
  format: yaml
  label: BuyRecord Merchants API
  slug: buyrecord-app-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyrecord-app/openapi/buyrecord-app-merchants-api-openapi.yml
- filename: buyrecord-app-outcomes-api-openapi.yml
  format: yaml
  label: BuyRecord Outcomes API
  slug: buyrecord-app-outcomes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyrecord-app/openapi/buyrecord-app-outcomes-api-openapi.yml
- filename: buyrecord-app-products-api-openapi.yml
  format: yaml
  label: BuyRecord Products API
  slug: buyrecord-app-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyrecord-app/openapi/buyrecord-app-products-api-openapi.yml
- filename: buyrecord-app-stays-api-openapi.yml
  format: yaml
  label: BuyRecord Stays API
  slug: buyrecord-app-stays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyrecord-app/openapi/buyrecord-app-stays-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Order numbers and receipt references are turned into one-way salted hashes as soon as they arrive
  - category: behavioral
    text: 'Orders, last 60 days: which products were bought, when, whether the order was cancelled or a test, refund and return status and return reasons'
  - category: device
    text: the user agent (browser or bot name) and a salted one-way hash of the IP address, never the address itself
  - category: contact
    text: 'Contact: stephane.rix@buyrecord.app'
  deletion:
    route: Email request to stephane.rix@buyrecord.app; app uninstall deletes access token; Shopify shop/redact request
    text: When Shopify sends a store deletion request ( shop/redact ), we delete that store's data within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: publish return statistics
    text: BuyRecord publishes how often products are kept or returned.
  - purpose: detect duplicates
    text: used only to detect duplicates, and never stored in readable form
  - purpose: traffic statistics
    text: For traffic statistics we record, for each request, the time, the page or API operation, the response status and time
  - purpose: abuse rate limits
    text: IP addresses are used in memory to apply rate limits and are not written to our logs.
  residency:
  - region: Germany
    text: 'Servers: Hetzner Online, Germany.'
  retention:
  - period: null
    scope: Counted outcomes
    text: Counted outcomes are kept while BuyRecord publishes the product's statistics; they contain no personal data.
  - period: 180 days
    scope: Pending verifications
    text: Pending verifications expire after 180 days
  - period: 90 days
    scope: Traffic statistics
    text: traffic statistics after 90 days
  - period: 14 days
    scope: Database backups
    text: database backups after 14 days
  - period: one hour
    scope: Access tokens (assistant connections)
    text: Access tokens expire after one hour
  - period: 90 days
    scope: Refresh tokens (assistant connections)
    text: refresh tokens after 90 days or when you disconnect
  rights:
  - right: access, correction or deletion
    text: you may have rights to access, correct or delete personal data
  - right: complaint to supervisory authority
    text: You can also lodge a complaint with the French data protection authority, the CNIL (cnil.fr)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data and do not share it with third parties beyond the hosting providers above.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BuyRecord
provenance_date: '2026-11-09'
provider_name: BuyRecord
provider_slug: buyrecord-app
slug: buyrecord-app-privacy-policy
source_date: '2026-11-09'
source_filename: buyrecord-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buyrecord.app/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BuyRecord\naid: buyrecord-app\nurl: https://buyrecord.app/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Order numbers and receipt references are turned into one-way salted hashes as soon as they arrive\n- category: behavioral\n  text: 'Orders, last 60 days: which products were bought, when, whether the order was cancelled or a test, refund\n    and return status and return reasons'\n- category: device\n  text: the user agent (browser or bot name) and a salted one-way hash of the IP address, never the address itself\n- category:\
  \ contact\n  text: 'Contact: stephane.rix@buyrecord.app'\npurposes:\n- purpose: publish return statistics\n  text: BuyRecord publishes how often products are kept or returned.\n- purpose: detect duplicates\n  text: used only to detect duplicates, and never stored in readable form\n- purpose: traffic statistics\n  text: For traffic statistics we record, for each request, the time, the page or API operation, the response status\n    and time\n- purpose: abuse rate limits\n  text: IP addresses are used in memory to apply rate limits and are not written to our logs.\nretention:\n- scope: Counted outcomes\n  period: null\n  text: Counted outcomes are kept while BuyRecord publishes the product's statistics; they contain no personal data.\n- scope: Pending verifications\n  period: 180 days\n  text: Pending verifications expire after 180 days\n- scope: Traffic statistics\n  period: 90 days\n  text: traffic statistics after 90 days\n- scope: Database backups\n  period: 14 days\n  text: database\
  \ backups after 14 days\n- scope: Access tokens (assistant connections)\n  period: one hour\n  text: Access tokens expire after one hour\n- scope: Refresh tokens (assistant connections)\n  period: 90 days\n  text: refresh tokens after 90 days or when you disconnect\nresidency:\n- region: Germany\n  text: 'Servers: Hetzner Online, Germany.'\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to stephane.rix@buyrecord.app; app uninstall deletes access token; Shopify shop/redact request\n  text: When Shopify sends a store deletion request ( shop/redact ), we delete that store's data within 30 days.\nrights:\n- right: access, correction or deletion\n  text: you may have rights to access, correct or delete personal data\n- right: complaint to supervisory authority\n  text: You can also lodge a complaint with the French data protection authority, the CNIL (cnil.fr)\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell data and do not share it with third parties beyond the hosting providers above.\n"
source_yaml_url: https://artifacts.apis.io/buyrecord-app/privacy/buyrecord-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from BuyRecord's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- E-Commerce
- Data
- Shopping
- Analytics
---
