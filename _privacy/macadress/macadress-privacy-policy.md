---
api_specs:
- filename: macadress-healthz-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Healthz API'
  slug: macadress-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-healthz-api-openapi.yml
- filename: macadress-mac-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Mac API'
  slug: macadress-mac-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-mac-api-openapi.yml
- filename: macadress-vendors-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Vendors API'
  slug: macadress-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-vendors-api-openapi.yml
- filename: macadress-vendor-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Vendor API'
  slug: macadress-vendor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-vendor-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: If you create an account, we store your email address, a bcrypt hash of your password (never the password itself), your plan, and an encrypted copy of your API key.
  - category: device
    text: Request logs (IP address, requested path, timestamp) are kept briefly for debugging and abuse prevention, then rotated out.
  - category: financial
    text: we only ever see your Stripe customer and subscription IDs and subscription status, never your card number.
  - category: behavioral
    text: We also use Google Analytics (GA4) to see aggregate traffic and usage patterns
  deletion:
    route: email to the address on the page
    text: To delete your account and the data tied to it, email us at the address below; we'll confirm once it's done.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: debugging and abuse prevention
    text: Request logs (IP address, requested path, timestamp) are kept briefly for debugging and abuse prevention, then rotated out.
  - purpose: payment processing
    text: Stripe, for payment processing on paid plans
  - purpose: aggregate analytics
    text: Google, for the aggregate analytics described above.
  - purpose: providing lookups
    text: We don't sell or share extension data, or use it for anything except providing lookups.
  retention:
  - period: null
    scope: request logs
    text: Request logs (IP address, requested path, timestamp) are kept briefly for debugging and abuse prevention, then rotated out.
  - period: null
    scope: account data
    text: Account data is kept for as long as your account is active.
  - period: up to 7 days
    scope: extension cache
    text: lookup answers cached for up to 7 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or rent your data.
  subprocessors:
    text: 'It''s shared with two processors: Stripe, for payment processing on paid plans, and Google, for the aggregate analytics described above.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
provenance_date: '2026-11-10'
provider_name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
provider_slug: macadress
slug: macadress-privacy-policy
source_date: '2026-11-10'
source_filename: macadress-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://macadress.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 'MAC Address Lookup: Find Vendor, OUI & Device Type'\naid: macadress\nurl: https://macadress.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: If you create an account, we store your email address, a bcrypt hash of your password (never the password\n    itself), your plan, and an encrypted copy of your API key.\n- category: device\n  text: Request logs (IP address, requested path, timestamp) are kept briefly for debugging and abuse prevention,\n    then rotated out.\n- category: financial\n  text: we only ever see your Stripe\
  \ customer and subscription IDs and subscription status, never your card number.\n- category: behavioral\n  text: We also use Google Analytics (GA4) to see aggregate traffic and usage patterns\npurposes:\n- purpose: debugging and abuse prevention\n  text: Request logs (IP address, requested path, timestamp) are kept briefly for debugging and abuse prevention,\n    then rotated out.\n- purpose: payment processing\n  text: Stripe, for payment processing on paid plans\n- purpose: aggregate analytics\n  text: Google, for the aggregate analytics described above.\n- purpose: providing lookups\n  text: We don't sell or share extension data, or use it for anything except providing lookups.\nretention:\n- scope: request logs\n  period: null\n  text: Request logs (IP address, requested path, timestamp) are kept briefly for debugging and abuse prevention,\n    then rotated out.\n- scope: account data\n  period: null\n  text: Account data is kept for as long as your account is active.\n- scope: extension\
  \ cache\n  period: up to 7 days\n  text: lookup answers cached for up to 7 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'It''s shared with two processors: Stripe, for payment processing on paid plans, and Google, for the aggregate\n    analytics described above.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to the address on the page\n  text: To delete your account and the data tied to it, email us at the address below; we'll confirm once it's done.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or rent your data.\n"
source_yaml_url: https://artifacts.apis.io/macadress/privacy/macadress-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: '14 quoted statements, read from MAC Address Lookup: Find Vendor, OUI & Device Type''s own page on 2026-11-10.'
synthetic: false
tags:
- Networking
- Network Access Control
- Security
- SecOps
- IoT
- Device Fleet Management
- MDM
- Reference Data
- IEEE OUI Lookup
- Developer Tools
- MCP
- Agent-Native
---
