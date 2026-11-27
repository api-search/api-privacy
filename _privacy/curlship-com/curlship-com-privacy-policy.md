---
api_specs:
- filename: curlship-com-badge-api-openapi.yml
  format: yaml
  label: CurlShip Badge API
  slug: curlship-com-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-badge-api-openapi.yml
- filename: curlship-com-billing-api-openapi.yml
  format: yaml
  label: CurlShip Billing API
  slug: curlship-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-billing-api-openapi.yml
- filename: curlship-com-edits-api-openapi.yml
  format: yaml
  label: CurlShip Edits API
  slug: curlship-com-edits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-edits-api-openapi.yml
- filename: curlship-com-listings-api-openapi.yml
  format: yaml
  label: CurlShip Listings API
  slug: curlship-com-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-listings-api-openapi.yml
- filename: curlship-com-stats-api-openapi.yml
  format: yaml
  label: CurlShip Stats API
  slug: curlship-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-stats-api-openapi.yml
- filename: curlship-com-x402-api-openapi.yml
  format: yaml
  label: CurlShip X402 API
  slug: curlship-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curlship-com/openapi/curlship-com-x402-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Email — the only personal datum. Required so you can prove ownership of the listing and so we can contact you about it.
  - category: identifying
    text: IP addresses used for rate limiting are held in memory only , in per-IP dictionaries, for at most one hour, and are never written to disk.
  - category: other
    text: Product URL and scraped Open Graph fields (title, description, image).
  - category: financial
    text: Listing metadata — tier, badge status, status, timestamps, and (for paid tiers) a DodoPayments subscription id.
  deletion:
    route: email request to privacy contact
    text: Erasing the stored email, and the audit rows with it, is a request to [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: contract
    text: Contract — to create and keep your listing live, and to deliver a paid-tier subscription you bought.
  - purpose: legitimate interest
    text: Legitimate interest — to operate the directory, fight spam/abuse, and apply per-IP rate limits.
  retention:
  - period: as long as the listing is active
    scope: active listings and email
    text: Active listings (and their email) stay for as long as the listing is active.
  - period: as long as the listing exists
    scope: edit records
    text: Both are kept for as long as the listing exists — they are what makes an unwanted change provable and reversible.
  - period: 7 days
    scope: removed free listing audit row
    text: keeps the audit row so the change can be undone for 7 days.
  - period: within one hour
    scope: in-memory rate-limit data
    text: In-memory rate-limit data expires within one hour.
  - period: null
    scope: subscription records
    text: Subscription records may be retained by the Merchant of Record for as long as tax and accounting rules require.
  rights:
  - right: access
    text: 'Under GDPR (Arts. 15–21) you can request: access, rectification, erasure, restriction of processing, data portability, and to object to processing based on legitimate interest.'
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with a supervisory authority in your country of residence.
  role:
    text: CurlShip is run by Marcin Dudek , an indie developer ( marcindudek.dev ).
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: DodoPayments — Merchant of Record for paid tiers.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CurlShip
provenance_date: '2026-11-09'
provider_name: CurlShip
provider_slug: curlship-com
slug: curlship-com-privacy-policy
source_date: '2026-11-09'
source_filename: curlship-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://curlship.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CurlShip\naid: curlship-com\nurl: https://curlship.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CurlShip is run by Marcin Dudek , an indie developer ( marcindudek.dev ).\ndata_categories:\n- category: contact\n  text: Email — the only personal datum. Required so you can prove ownership of the listing and so we can contact\n    you about it.\n- category: identifying\n  text: IP addresses used for rate limiting are held in memory only , in per-IP dictionaries, for at most one hour,\n    and are never written to disk.\n- category: other\n  text: Product URL and scraped Open Graph\
  \ fields (title, description, image).\n- category: financial\n  text: Listing metadata — tier, badge status, status, timestamps, and (for paid tiers) a DodoPayments subscription\n    id.\npurposes:\n- purpose: contract\n  text: Contract — to create and keep your listing live, and to deliver a paid-tier subscription you bought.\n- purpose: legitimate interest\n  text: Legitimate interest — to operate the directory, fight spam/abuse, and apply per-IP rate limits.\nretention:\n- scope: active listings and email\n  period: as long as the listing is active\n  text: Active listings (and their email) stay for as long as the listing is active.\n- scope: edit records\n  period: as long as the listing exists\n  text: Both are kept for as long as the listing exists — they are what makes an unwanted change provable and reversible.\n- scope: removed free listing audit row\n  period: 7 days\n  text: keeps the audit row so the change can be undone for 7 days.\n- scope: in-memory rate-limit data\n  period:\
  \ within one hour\n  text: In-memory rate-limit data expires within one hour.\n- scope: subscription records\n  period: null\n  text: Subscription records may be retained by the Merchant of Record for as long as tax and accounting rules require.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: DodoPayments — Merchant of Record for paid tiers.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy contact\n  text: Erasing the stored email, and the audit rows with it, is a request to [email protected] .\nrights:\n- right: access\n  text: 'Under GDPR (Arts. 15–21) you can request: access, rectification, erasure, restriction of processing, data\n    portability, and to object to processing based on legitimate interest.'\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with a supervisory authority in your country of residence.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/curlship-com/privacy/curlship-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from CurlShip's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Directory
- Product Listings
- Developer Tools
- MCP
- AI Agents
- REST API
- Launch Platform
---
