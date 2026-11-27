---
api_specs:
- filename: horsetruth-horses-api-openapi.yml
  format: yaml
  label: Horse Truth Horses API
  slug: horsetruth-horses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-horses-api-openapi.yml
- filename: horsetruth-identity-api-openapi.yml
  format: yaml
  label: Horse Truth Identity API
  slug: horsetruth-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-identity-api-openapi.yml
- filename: horsetruth-machine-api-openapi.yml
  format: yaml
  label: Horse Truth Machine API
  slug: horsetruth-machine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-machine-api-openapi.yml
- filename: horsetruth-mcp-api-openapi.yml
  format: yaml
  label: Horse Truth MCP API
  slug: horsetruth-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-mcp-api-openapi.yml
- filename: horsetruth-sandbox-api-openapi.yml
  format: yaml
  label: Horse Truth Sandbox API
  slug: horsetruth-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-sandbox-api-openapi.yml
- filename: horsetruth-x402-api-openapi.yml
  format: yaml
  label: Horse Truth X402 API
  slug: horsetruth-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/horsetruth/openapi/horsetruth-x402-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Horse Truth collects account information required to provide subscription access, billing access and customer support.
  - category: contact
    text: If you follow a horse, Horse Truth keeps your email address, the horses you follow, and a record of your consent
  - category: device
    text: We store your internet address and browser or agent identifier only as a one-way scrambled code, used to count usage, prevent abuse and improve the service.
  - category: financial
    text: We record the transaction reference, amount, network and a scrambled form of the paying wallet so we can deliver what was paid for and keep accurate records.
  deletion:
    route: Email the privacy address to ask for deletion
    text: You can ask us to access, correct or delete information we hold about you by emailing the address below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: subscription and billing access
    text: Horse Truth collects account information required to provide subscription access, billing access and customer support.
  - purpose: security and service improvement
    text: Portal activity may be logged for security, subscription access control and service improvement.
  - purpose: follow alerts
    text: We use it only to email you when Horse Truth's view of those horses changes and for occasional Horse Truth updates.
  - purpose: usage counting and abuse prevention
    text: used to count usage, prevent abuse and improve the service.
  residency:
  - region: United States
    text: Railway (hosting, in the United States)
  retention:
  - period: null
    scope: request and usage records
    text: We keep request and usage records only as long as needed for security, accurate billing and improving the service.
  - period: null
    scope: billing records
    text: Billing records are kept as long as the law requires.
  - period: null
    scope: follow-alert data
    text: Follow-alert data is deleted when you ask us to.
  rights:
  - right: access
    text: You can ask us to access, correct or delete information we hold about you by emailing the address below.
  - right: correction
    text: You can ask us to access, correct or delete information we hold about you by emailing the address below.
  - right: deletion
    text: You can ask us to access, correct or delete information we hold about you by emailing the address below.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell or share your email.
  subprocessors:
    text: 'We use trusted providers to run Horse Truth: Railway (hosting, in the United States), Stripe (card payments), an x402 payment facilitator (machine payments) and Resend (email).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Horse Truth
provenance_date: '2026-11-09'
provider_name: Horse Truth
provider_slug: horsetruth
slug: horsetruth-privacy-policy
source_date: '2026-11-09'
source_filename: horsetruth-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://horsetruth.com.au/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Horse Truth\naid: horsetruth\nurl: https://horsetruth.com.au/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Horse Truth collects account information required to provide subscription access, billing access and customer\n    support.\n- category: contact\n  text: If you follow a horse, Horse Truth keeps your email address, the horses you follow, and a record of your\n    consent\n- category: device\n  text: We store your internet address and browser or agent identifier only as a one-way scrambled code, used to\n    count usage, prevent\
  \ abuse and improve the service.\n- category: financial\n  text: We record the transaction reference, amount, network and a scrambled form of the paying wallet so we can\n    deliver what was paid for and keep accurate records.\npurposes:\n- purpose: subscription and billing access\n  text: Horse Truth collects account information required to provide subscription access, billing access and customer\n    support.\n- purpose: security and service improvement\n  text: Portal activity may be logged for security, subscription access control and service improvement.\n- purpose: follow alerts\n  text: We use it only to email you when Horse Truth's view of those horses changes and for occasional Horse Truth\n    updates.\n- purpose: usage counting and abuse prevention\n  text: used to count usage, prevent abuse and improve the service.\nretention:\n- scope: request and usage records\n  period: null\n  text: We keep request and usage records only as long as needed for security, accurate billing\
  \ and improving the\n    service.\n- scope: billing records\n  period: null\n  text: Billing records are kept as long as the law requires.\n- scope: follow-alert data\n  period: null\n  text: Follow-alert data is deleted when you ask us to.\nresidency:\n- region: United States\n  text: Railway (hosting, in the United States)\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use trusted providers to run Horse Truth: Railway (hosting, in the United States), Stripe (card payments),\n    an x402 payment facilitator (machine payments) and Resend (email).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy address to ask for deletion\n  text: You can ask us to access, correct or delete information we hold about you by emailing the address below.\nrights:\n- right: access\n  text: You can ask us to access, correct or delete information we hold about you by emailing the address below.\n- right: correction\n  text: You can ask us to access, correct\
  \ or delete information we hold about you by emailing the address below.\n- right: deletion\n  text: You can ask us to access, correct or delete information we hold about you by emailing the address below.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell or share your email.\n"
source_yaml_url: https://artifacts.apis.io/horsetruth/privacy/horsetruth-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Horse Truth's own page on 2026-11-09.
synthetic: false
tags:
- Racehorse Intelligence
- Horse Reports
- Developers
- Trainers
---
