---
api_specs:
- filename: tomorrowlives-com-account-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Account API
  slug: tomorrowlives-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-account-api-openapi.yml
- filename: tomorrowlives-com-jobs-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Jobs API
  slug: tomorrowlives-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-jobs-api-openapi.yml
- filename: tomorrowlives-com-lab-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Lab API
  slug: tomorrowlives-com-lab-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-lab-api-openapi.yml
- filename: tomorrowlives-com-mcp-api-openapi.yml
  format: yaml
  label: tomorrowlives-com MCP API
  slug: tomorrowlives-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-mcp-api-openapi.yml
- filename: tomorrowlives-com-production-engines-api-openapi.yml
  format: yaml
  label: tomorrowlives-com Production engines API
  slug: tomorrowlives-com-production-engines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tomorrowlives-com/openapi/tomorrowlives-com-production-engines-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: your email address (used to sign you in)'
  - category: identifying
    text: the account id Google gives us if you sign in with Google
  - category: financial
    text: If Stripe has told us about a payment or a subscription of yours, your account can carry the customer id Stripe gave us.
  - category: communication
    text: the sent, delivered, delayed, opened, clicked, bounced, complaint and failure events our mail provider reports for email we send you
  - category: device
    text: 'IP addresses: your IP address is processed transiently for abuse limits and analytics, and is not stored against your account.'
  deletion:
    route: delete account flow at /account/settings
    text: 'To exercise any of these rights: use the delete account flow at /account/settings'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation
    text: 'Transactional email and service operation: performance of a contract (you signed up for an account).'
  - purpose: marketing email
    text: 'Marketing email: consent (you opted in).'
  - purpose: operating and improving the service
    text: 'Usage records, retained history, events and analytics: legitimate interest in operating, securing, and improving the service.'
  retention:
  - period: while your account is open
    scope: account data
    text: What is stored with your account is kept while your account is open.
  rights:
  - right: access
    text: Access the personal data we hold about you
  - right: correction
    text: Request correction of inaccurate data
  - right: deletion
    text: Request deletion of your account and data
  - right: restrict or object
    text: Restrict or object to certain processing
  - right: portability
    text: Port your data to another service
  - right: withdraw marketing consent
    text: Withdraw consent to marketing at any time
  role:
    text: Tomorrow Lives Studio is the data controller for personal data processed through tomorrowlives.com and your account.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare provides DNS, CDN and inbound email routing.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tomorrowlives-com
provenance_date: '2026-11-10'
provider_name: tomorrowlives-com
provider_slug: tomorrowlives-com
slug: tomorrowlives-com-privacy-policy
source_date: '2026-11-10'
source_filename: tomorrowlives-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tomorrowlives.com/account/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tomorrowlives-com\naid: tomorrowlives-com\nurl: https://tomorrowlives.com/account/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Tomorrow Lives Studio is the data controller for personal data processed through tomorrowlives.com and your\n    account.\ndata_categories:\n- category: contact\n  text: 'Account data: your email address (used to sign you in)'\n- category: identifying\n  text: the account id Google gives us if you sign in with Google\n- category: financial\n  text: If Stripe has told us about a payment or a subscription of yours, your account can carry the customer id\n \
  \   Stripe gave us.\n- category: communication\n  text: the sent, delivered, delayed, opened, clicked, bounced, complaint and failure events our mail provider reports\n    for email we send you\n- category: device\n  text: 'IP addresses: your IP address is processed transiently for abuse limits and analytics, and is not stored\n    against your account.'\npurposes:\n- purpose: service operation\n  text: 'Transactional email and service operation: performance of a contract (you signed up for an account).'\n- purpose: marketing email\n  text: 'Marketing email: consent (you opted in).'\n- purpose: operating and improving the service\n  text: 'Usage records, retained history, events and analytics: legitimate interest in operating, securing, and\n    improving the service.'\nretention:\n- scope: account data\n  period: while your account is open\n  text: What is stored with your account is kept while your account is open.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare\
  \ provides DNS, CDN and inbound email routing.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account flow at /account/settings\n  text: 'To exercise any of these rights: use the delete account flow at /account/settings'\nrights:\n- right: access\n  text: Access the personal data we hold about you\n- right: correction\n  text: Request correction of inaccurate data\n- right: deletion\n  text: Request deletion of your account and data\n- right: restrict or object\n  text: Restrict or object to certain processing\n- right: portability\n  text: Port your data to another service\n- right: withdraw marketing consent\n  text: Withdraw consent to marketing at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tomorrowlives-com/privacy/tomorrowlives-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from tomorrowlives-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Generative
- Engines
- Creative
---
