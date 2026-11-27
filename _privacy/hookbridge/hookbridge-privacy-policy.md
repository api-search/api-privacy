---
api_specs:
- filename: hookbridge-api-openapi.yml
  format: yaml
  label: HookBridge API API
  slug: hookbridge-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hookbridge/openapi/_original/hookbridge-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, work email, company name, account credentials, and user roles.'
  - category: financial
    text: 'Billing information: billing address, subscription details, and transaction metadata.'
  - category: device
    text: 'Device data: browser type, operating system, device identifiers, and similar technical data.'
  - category: behavioral
    text: 'Analytics data: pages viewed and interaction metadata on our marketing website via Google Analytics.'
  - category: communication
    text: 'Communications: support requests, feedback, and other communications with our team.'
  deletion:
    route: null
    text: When data is no longer needed, we delete or anonymize it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and secure the Services
    text: Provide, maintain, and secure the Services.
  - purpose: Deliver webhooks and observability
    text: Deliver webhooks, retries, and observability features.
  - purpose: Process subscriptions and payments
    text: Process subscriptions, invoices, and payments.
  - purpose: Improve and develop the Services
    text: Improve and develop the Services.
  retention:
  - period: null
    scope: Webhook payloads and delivery logs
    text: Webhook payloads and delivery logs are automatically purged after the retention window configured by the customer.
  rights:
  - right: Access, correct, or delete personal data
    text: Access, correct, or delete personal data.
  - right: Object to or restrict processing
    text: Object to or restrict certain processing.
  - right: Portability
    text: Portability of your data.
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  role:
    text: For account, billing, and operational data collected directly by Hookbridge, we are the data controller .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data. We do not share customer data with third parties for advertising or marketing purposes.
  subprocessors:
    text: Subprocessors Provider Purpose Data Processed Stripe Payment processing Billing name, email, payment method, transaction details Postmark Transactional email Email address, message content Google Analytics Marketing website analytics Anonymous usage data on hookbridge.io (not the application)
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use appropriate safeguards such as Standard Contractual Clauses or other lawful transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hookbridge
provenance_date: '2026-11-09'
provider_name: Hookbridge
provider_slug: hookbridge
slug: hookbridge-privacy-policy
source_date: '2026-11-09'
source_filename: hookbridge-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.hookbridge.io/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hookbridge\naid: hookbridge\nurl: https://www.hookbridge.io/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account, billing, and operational data collected directly by Hookbridge, we are the data controller\n    .\ndata_categories:\n- category: identifying\n  text: 'Account information: name, work email, company name, account credentials, and user roles.'\n- category: financial\n  text: 'Billing information: billing address, subscription details, and transaction metadata.'\n- category: device\n  text: 'Device data: browser type, operating system, device identifiers, and similar\
  \ technical data.'\n- category: behavioral\n  text: 'Analytics data: pages viewed and interaction metadata on our marketing website via Google Analytics.'\n- category: communication\n  text: 'Communications: support requests, feedback, and other communications with our team.'\npurposes:\n- purpose: Provide, maintain, and secure the Services\n  text: Provide, maintain, and secure the Services.\n- purpose: Deliver webhooks and observability\n  text: Deliver webhooks, retries, and observability features.\n- purpose: Process subscriptions and payments\n  text: Process subscriptions, invoices, and payments.\n- purpose: Improve and develop the Services\n  text: Improve and develop the Services.\nretention:\n- scope: Webhook payloads and delivery logs\n  period: null\n  text: Webhook payloads and delivery logs are automatically purged after the retention window configured by the\n    customer.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we use appropriate safeguards\
  \ such as Standard Contractual Clauses or other lawful transfer\n    mechanisms.\nsubprocessors:\n  url: null\n  text: Subprocessors Provider Purpose Data Processed Stripe Payment processing Billing name, email, payment method,\n    transaction details Postmark Transactional email Email address, message content Google Analytics Marketing website\n    analytics Anonymous usage data on hookbridge.io (not the application)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: When data is no longer needed, we delete or anonymize it.\nrights:\n- right: Access, correct, or delete personal data\n  text: Access, correct, or delete personal data.\n- right: Object to or restrict processing\n  text: Object to or restrict certain processing.\n- right: Portability\n  text: Portability of your data.\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\
  \ We do not share customer data with third parties for advertising or marketing\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/hookbridge/privacy/hookbridge-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Hookbridge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Webhook
- Software-as-a-Service
- Integration
---
