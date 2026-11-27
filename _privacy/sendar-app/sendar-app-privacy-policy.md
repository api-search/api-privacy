---
api_specs:
- filename: sendar-app-emails-api-openapi.yml
  format: yaml
  label: sendar-app Emails API
  slug: sendar-app-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-emails-api-openapi.yml
- filename: sendar-app-headless-api-openapi.yml
  format: yaml
  label: sendar-app Headless API
  slug: sendar-app-headless-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-headless-api-openapi.yml
- filename: sendar-app-inboxes-api-openapi.yml
  format: yaml
  label: sendar-app Inboxes API
  slug: sendar-app-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-inboxes-api-openapi.yml
- filename: sendar-app-link-checks-api-openapi.yml
  format: yaml
  label: sendar-app Link Checks API
  slug: sendar-app-link-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendar-app/openapi/sendar-app-link-checks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, and a cryptographic hash of your password (we never store the password itself).
  - category: financial
    text: We retain payment-provider references, subscription details, transaction records and any payment-method summary supplied by PayPal for billing and account history.
  - category: communication
    text: When you send email, we process and store the message
  - category: device
    text: we keep API request logs and server logs that include IP address, user-agent, endpoint, response status, and timestamps
  - category: behavioral
    text: Our first-party website measurement records page paths, referring-site origins, campaign parameters and events such as signup or completion of a public tool.
  deletion:
    route: Settings → Account
    text: deletion is immediate and permanent
  dpa:
    available: true
    text: governed by our Data Processing Addendum
    url: null
  purposes:
  - purpose: provide and operate the Service
    text: To provide, operate, and maintain the Service, including delivering the emails you ask us to send and showing you logs and metrics.
  - purpose: payments and billing
    text: To process subscriptions and payments, send receipts, and manage renewals and payment failures.
  - purpose: platform security
    text: 'To secure the platform: authenticating sessions and API keys, rate limiting, detecting and preventing abuse and fraud.'
  - purpose: legal compliance
    text: To comply with legal obligations and enforce our agreements, including the Terms of Service and Acceptable Use Policy
  residency:
  - region: South Africa (email delivery)
    text: hosted in the Johannesburg, South Africa region
  - region: United States (database)
    text: provides our managed PostgreSQL database in the United States (AWS US East, Ohio)
  retention:
  - period: null
    scope: account information
    text: We keep your account information for as long as your account exists.
  - period: null
    scope: server and request logs
    text: Server and request logs are kept for a limited period for security and troubleshooting.
  - period: null
    scope: deleted account data
    text: deletion is immediate and permanent
  rights:
  - right: access, correction, export, deletion, restriction
    text: you may have rights to access, correct, export, delete, or restrict the processing of your personal information
  - right: objection and withdrawal of consent
    text: to object to certain processing or withdraw consent
  - right: complaint to data protection authority
    text: you may lodge a complaint with your local data protection authority
  role:
    text: For the information of our customers — the people and organizations who hold Sendar accounts — we act as the data controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information
  subprocessors:
    text: We share information only with the service providers that make Sendar work, under agreements that restrict their use of it
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as standard contractual clauses with our providers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: sendar-app
provenance_date: '2026-11-10'
provider_name: sendar-app
provider_slug: sendar-app
slug: sendar-app-privacy-policy
source_date: '2026-11-10'
source_filename: sendar-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sendar.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: sendar-app\naid: sendar-app\nurl: https://sendar.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the information of our customers — the people and organizations who hold Sendar accounts — we act as\n    the data controller\ndata_categories:\n- category: identifying\n  text: Your name, email address, and a cryptographic hash of your password (we never store the password itself).\n- category: financial\n  text: We retain payment-provider references, subscription details, transaction records and any payment-method\n    summary supplied by PayPal for billing and account history.\n- category:\
  \ communication\n  text: When you send email, we process and store the message\n- category: device\n  text: we keep API request logs and server logs that include IP address, user-agent, endpoint, response status,\n    and timestamps\n- category: behavioral\n  text: Our first-party website measurement records page paths, referring-site origins, campaign parameters and\n    events such as signup or completion of a public tool.\npurposes:\n- purpose: provide and operate the Service\n  text: To provide, operate, and maintain the Service, including delivering the emails you ask us to send and showing\n    you logs and metrics.\n- purpose: payments and billing\n  text: To process subscriptions and payments, send receipts, and manage renewals and payment failures.\n- purpose: platform security\n  text: 'To secure the platform: authenticating sessions and API keys, rate limiting, detecting and preventing abuse\n    and fraud.'\n- purpose: legal compliance\n  text: To comply with legal obligations\
  \ and enforce our agreements, including the Terms of Service and Acceptable\n    Use Policy\nretention:\n- scope: account information\n  period: null\n  text: We keep your account information for as long as your account exists.\n- scope: server and request logs\n  period: null\n  text: Server and request logs are kept for a limited period for security and troubleshooting.\n- scope: deleted account data\n  period: null\n  text: deletion is immediate and permanent\nresidency:\n- region: South Africa (email delivery)\n  text: hosted in the Johannesburg, South Africa region\n- region: United States (database)\n  text: provides our managed PostgreSQL database in the United States (AWS US East, Ohio)\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as standard contractual clauses with our providers\nsubprocessors:\n  url: null\n  text: We share information only with the service providers that make Sendar work, under agreements that restrict\n    their use of it\n\
  dpa:\n  available: true\n  url: null\n  text: governed by our Data Processing Addendum\ndeletion:\n  route: Settings → Account\n  text: deletion is immediate and permanent\nrights:\n- right: access, correction, export, deletion, restriction\n  text: you may have rights to access, correct, export, delete, or restrict the processing of your personal information\n- right: objection and withdrawal of consent\n  text: to object to certain processing or withdraw consent\n- right: complaint to data protection authority\n  text: you may lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information\n"
source_yaml_url: https://artifacts.apis.io/sendar-app/privacy/sendar-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from sendar-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Delivery
- Automation
---
