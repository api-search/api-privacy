---
api_specs:
- filename: webhook-relay-buckets-api-openapi.yml
  format: yaml
  label: Webhook Relay Buckets API
  slug: webhook-relay-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-buckets-api-openapi.yml
- filename: webhook-relay-domains-api-openapi.yml
  format: yaml
  label: Webhook Relay Domains API
  slug: webhook-relay-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-domains-api-openapi.yml
- filename: webhook-relay-functions-api-openapi.yml
  format: yaml
  label: Webhook Relay Functions API
  slug: webhook-relay-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-functions-api-openapi.yml
- filename: webhook-relay-inputs-api-openapi.yml
  format: yaml
  label: Webhook Relay Inputs API
  slug: webhook-relay-inputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-inputs-api-openapi.yml
- filename: webhook-relay-logs-api-openapi.yml
  format: yaml
  label: Webhook Relay Logs API
  slug: webhook-relay-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-logs-api-openapi.yml
- filename: webhook-relay-outputs-api-openapi.yml
  format: yaml
  label: Webhook Relay Outputs API
  slug: webhook-relay-outputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-outputs-api-openapi.yml
- filename: webhook-relay-tokens-api-openapi.yml
  format: yaml
  label: Webhook Relay Tokens API
  slug: webhook-relay-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-tokens-api-openapi.yml
- filename: webhook-relay-tunnels-api-openapi.yml
  format: yaml
  label: Webhook Relay Tunnels API
  slug: webhook-relay-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webhook-relay/openapi/webhook-relay-tunnels-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: your name, e-mail address and any custom text you have requested we include on your invoices are all visible on your account page
  - category: device
    text: These logs include IP addresses and information about your web browser and operating system version.
  - category: financial
    text: When a payment is made, our payment processors forward to us the information required for us to validate and process your order.
  - category: behavioral
    text: Cookies store a unique token that identifies you.
  - category: communication
    text: Webhooks, forwarded through buckets are recorded in the database (request body, headers and destination) for debugging, auditing or resend purposes.
  deletion:
    route: DELETE ACCOUNT button on the account page
    text: You can also delete your account at any time by using the 'DELETE ACCOUNT' button on that page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operational and troubleshooting logs
    text: Our website generates standard access- and error logs, which are kept for operational reasons.
  - purpose: billing
    text: Webhook Relay service only tracks the amount of webhooks forwarded in the current month for billing purposes.
  - purpose: receipts and account quotas
    text: This information is in turn used to provide you with a receipt and update your account quotas.
  - purpose: debugging, auditing or resend
    text: Webhooks, forwarded through buckets are recorded in the database (request body, headers and destination) for debugging, auditing or resend purposes.
  retention:
  - period: 3 months
    scope: website access and error logs
    text: They are kept for a maximum of 3 months although usually it's a lot shorter period, and then automatically deleted.
  - period: 7 days
    scope: relay meta-data logs
    text: our relays keep logs of the following meta-data for up to 7 days
  - period: as long as account subscription plan allows it
    scope: forwarded webhook content
    text: It is stored as long as account subscription plan allows it and then gets automatically deleted.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Webhook Relay
provenance_date: '2026-11-10'
provider_name: Webhook Relay
provider_slug: webhook-relay
slug: webhook-relay-privacy-policy
source_date: '2026-11-10'
source_filename: webhook-relay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://webhookrelay.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Webhook Relay\naid: webhook-relay\nurl: https://webhookrelay.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your name, e-mail address and any custom text you have requested we include on your invoices are all visible\n    on your account page\n- category: device\n  text: These logs include IP addresses and information about your web browser and operating system version.\n- category: financial\n  text: When a payment is made, our payment processors forward to us the information required for us to validate\n    and process your\
  \ order.\n- category: behavioral\n  text: Cookies store a unique token that identifies you.\n- category: communication\n  text: Webhooks, forwarded through buckets are recorded in the database (request body, headers and destination)\n    for debugging, auditing or resend purposes.\npurposes:\n- purpose: operational and troubleshooting logs\n  text: Our website generates standard access- and error logs, which are kept for operational reasons.\n- purpose: billing\n  text: Webhook Relay service only tracks the amount of webhooks forwarded in the current month for billing purposes.\n- purpose: receipts and account quotas\n  text: This information is in turn used to provide you with a receipt and update your account quotas.\n- purpose: debugging, auditing or resend\n  text: Webhooks, forwarded through buckets are recorded in the database (request body, headers and destination)\n    for debugging, auditing or resend purposes.\nretention:\n- scope: website access and error logs\n  period: 3 months\n\
  \  text: They are kept for a maximum of 3 months although usually it's a lot shorter period, and then automatically\n    deleted.\n- scope: relay meta-data logs\n  period: 7 days\n  text: our relays keep logs of the following meta-data for up to 7 days\n- scope: forwarded webhook content\n  period: as long as account subscription plan allows it\n  text: It is stored as long as account subscription plan allows it and then gets automatically deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DELETE ACCOUNT button on the account page\n  text: You can also delete your account at any time by using the 'DELETE ACCOUNT' button on that page.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/webhook-relay/privacy/webhook-relay-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 13 quoted statements, read from Webhook Relay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Webhook
- API Gateway
- Integration
- Developer Tools
---
