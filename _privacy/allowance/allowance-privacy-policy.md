---
api_specs:
- filename: allowance-mandates-api-openapi.yml
  format: yaml
  label: Allowance Mandates API
  slug: allowance-mandates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allowance/openapi/allowance-mandates-api-openapi.yml
- filename: allowance-pricing-api-openapi.yml
  format: yaml
  label: Allowance Pricing API
  slug: allowance-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allowance/openapi/allowance-pricing-api-openapi.yml
- filename: allowance-status-api-openapi.yml
  format: yaml
  label: Allowance Status API
  slug: allowance-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allowance/openapi/allowance-status-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile information, such as email address, phone number, name, and notification preferences
  - category: financial
    text: Billing information you add to your account, such as billing address details and labels you assign to saved addresses
  - category: financial
    text: Payment and activity information, such as allowance requests, approvals, denials, purchase attempt records, merchant information, amounts, status history, and related account activity
  - category: device
    text: Device registration information used to send app notifications, such as device push tokens and platform details
  - category: communication
    text: Alfie conversations and files, including your messages, assistant responses, requested actions, and information retrieved from services you connect, as described below
  - category: behavioral
    text: Reservation tracking information you choose to provide, such as source URLs, date ranges, party size, time windows, tracker status, and match results
  deletion:
    route: Delete your Allowance account or email support@useallowance.com; disconnect Google in Settings → Connections
    text: Deletion is a process rather than an instantaneous erasure of every copy.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account operation and authentication
    text: To create, maintain, and update your account
  - purpose: Payments and transaction flows
    text: To process allowance requests, approvals, payment controls, wallet setup, and related transaction flows
  - purpose: Notifications
    text: To send transactional email, SMS, push notifications, and other account or activity messages
  - purpose: Fraud and abuse detection
    text: To detect misuse, reduce fraud and abuse, troubleshoot issues, and comply with law
  - purpose: Service improvement
    text: To operate, support, and improve the service
  retention:
  - period: up to 24 hours
    scope: Allowance Rewards recommendations cache
    text: We keep a completed recommendation in a shared cache for up to 24 hours so identical public research can be reused.
  - period: null
    scope: Scribe recent dictations on device
    text: recordings older than 24 hours are cleaned up when the app opens
  rights:
  - right: access, correction, or deletion
    text: You can request access, correction, or deletion of certain account information by emailing support@useallowance.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Allowance
provenance_date: '2026-11-09'
provider_name: Allowance
provider_slug: allowance
slug: allowance-privacy-policy
source_date: '2026-11-09'
source_filename: allowance-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://useallowance.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Allowance\naid: allowance\nurl: https://useallowance.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and profile information, such as email address, phone number, name, and notification preferences\n- category: financial\n  text: Billing information you add to your account, such as billing address details and labels you assign to saved\n    addresses\n- category: financial\n  text: Payment and activity information, such as allowance requests, approvals, denials, purchase attempt records,\n    merchant information, amounts,\
  \ status history, and related account activity\n- category: device\n  text: Device registration information used to send app notifications, such as device push tokens and platform\n    details\n- category: communication\n  text: Alfie conversations and files, including your messages, assistant responses, requested actions, and information\n    retrieved from services you connect, as described below\n- category: behavioral\n  text: Reservation tracking information you choose to provide, such as source URLs, date ranges, party size, time\n    windows, tracker status, and match results\npurposes:\n- purpose: Account operation and authentication\n  text: To create, maintain, and update your account\n- purpose: Payments and transaction flows\n  text: To process allowance requests, approvals, payment controls, wallet setup, and related transaction flows\n- purpose: Notifications\n  text: To send transactional email, SMS, push notifications, and other account or activity messages\n- purpose:\
  \ Fraud and abuse detection\n  text: To detect misuse, reduce fraud and abuse, troubleshoot issues, and comply with law\n- purpose: Service improvement\n  text: To operate, support, and improve the service\nretention:\n- scope: Allowance Rewards recommendations cache\n  period: up to 24 hours\n  text: We keep a completed recommendation in a shared cache for up to 24 hours so identical public research can\n    be reused.\n- scope: Scribe recent dictations on device\n  period: null\n  text: recordings older than 24 hours are cleaned up when the app opens\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your Allowance account or email support@useallowance.com; disconnect Google in Settings → Connections\n  text: Deletion is a process rather than an instantaneous erasure of every copy.\nrights:\n- right: access, correction, or deletion\n  text: You can request access, correction, or deletion\
  \ of certain account information by emailing support@useallowance.com\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/allowance/privacy/allowance-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Allowance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Agentic Payments
- AI Agents
- Virtual Cards
- Fintech
- MCP
- Consumer Trust
- Spending Controls
- AP2
---
