---
api_specs:
- filename: osis-co-ai-api-openapi.yml
  format: yaml
  label: osis-co AI API
  slug: osis-co-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-ai-api-openapi.yml
- filename: osis-co-calls-api-openapi.yml
  format: yaml
  label: osis-co Calls API
  slug: osis-co-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-calls-api-openapi.yml
- filename: osis-co-capabilities-api-openapi.yml
  format: yaml
  label: osis-co Capabilities API
  slug: osis-co-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-capabilities-api-openapi.yml
- filename: osis-co-conversations-api-openapi.yml
  format: yaml
  label: osis-co Conversations API
  slug: osis-co-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-conversations-api-openapi.yml
- filename: osis-co-events-api-openapi.yml
  format: yaml
  label: osis-co Events API
  slug: osis-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-events-api-openapi.yml
- filename: osis-co-groups-api-openapi.yml
  format: yaml
  label: osis-co Groups API
  slug: osis-co-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-groups-api-openapi.yml
- filename: osis-co-lines-api-openapi.yml
  format: yaml
  label: osis-co Lines API
  slug: osis-co-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-lines-api-openapi.yml
- filename: osis-co-messages-api-openapi.yml
  format: yaml
  label: osis-co Messages API
  slug: osis-co-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-messages-api-openapi.yml
- filename: osis-co-number-changes-api-openapi.yml
  format: yaml
  label: osis-co Number Changes API
  slug: osis-co-number-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-number-changes-api-openapi.yml
- filename: osis-co-payments-api-openapi.yml
  format: yaml
  label: osis-co Payments API
  slug: osis-co-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-payments-api-openapi.yml
- filename: osis-co-webhooks-api-openapi.yml
  format: yaml
  label: osis-co Webhooks API
  slug: osis-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/osis-co/openapi/osis-co-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Your phone number (verified by one-time code), workspace name, team member details, and settings you configure.
  - category: financial
    text: We receive plan, status, and transaction records; we do not receive or store full card numbers.
  - category: device
    text: Log data such as IP address, browser and device information, pages viewed, API calls, timestamps, and error and delivery events.
  - category: communication
    text: The content and metadata of messages sent and received through the Service — including inbound replies from Recipients
  - category: identifying
    text: When you open a merchant checkout, Shopify and the merchant process the information needed for your order, which can include your name, email address, phone number, shipping and billing addresses, payment information, and purchases.
  deletion:
    route: Email the privacy address to request deletion, or delete your workspace
    text: Deletion. You can delete your workspace or ask us to delete your data, subject to the retention rules above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: authenticate you, deliver messages, run agents, and show conversation history'
  - purpose: Operate AI features
    text: 'Operate AI features: message content is processed by machine-learning models to generate agent replies, apply compliance checks, and take configured actions'
  - purpose: Enforce compliance
    text: 'Enforce compliance: process STOP and opt-out keywords, maintain suppression lists, keep consent and audit records'
  - purpose: Bill for paid plans
    text: Bill for paid plans and manage subscriptions
  - purpose: Protect the Service
    text: 'Protect the Service: prevent spam, fraud, and abuse; enforce rate limits; secure accounts; debug and fix problems'
  residency:
  - region: United States
    text: We are based in the United States and process data on servers in the United States.
  retention:
  - period: for the life of the account
    scope: Account and workspace data
    text: 'Account and workspace data: for the life of the account'
  - period: retained even after related content is deleted
    scope: Opt-out and consent records, and audit logs
    text: 'Opt-out and consent records, and audit logs: retained even after related content is deleted'
  - period: for a limited operational window
    scope: Log data
    text: 'Log data: for a limited operational window, then deleted or aggregated.'
  rights:
  - right: Access and portability
    text: Access and portability. You can request a copy or export of the data we hold about you.
  - right: Correction
    text: Correction. You can update workspace information in the product or ask us to correct inaccurate data.
  - right: Deletion
    text: Deletion. You can delete your workspace or ask us to delete your data, subject to the retention rules above.
  - right: Opt out of messages
    text: Recipients can reply STOP on any thread; marketing emails include unsubscribe links.
  role:
    text: For Recipient data — contact lists, subscriber records, and conversation content — the Customer is the data controller and we act as their processor or service provider.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: Subprocessors. Infrastructure vendors that host our systems and databases, deliver SMS/iMessage and email, provide AI model inference, process payments, and provide analytics for reliability.
    url: null
  transfers:
  - mechanism: other
    text: under appropriate safeguards where required by law
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: osis-co
provenance_date: '2026-11-10'
provider_name: osis-co
provider_slug: osis-co
slug: osis-co-privacy-policy
source_date: '2026-11-10'
source_filename: osis-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://comms.osis.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: osis-co\naid: osis-co\nurl: https://comms.osis.co/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For Recipient data — contact lists, subscriber records, and conversation content — the Customer is the data\n    controller and we act as their processor or service provider.\ndata_categories:\n- category: contact\n  text: Your phone number (verified by one-time code), workspace name, team member details, and settings you configure.\n- category: financial\n  text: We receive plan, status, and transaction records; we do not receive or store full card numbers.\n- category: device\n  text: Log data\
  \ such as IP address, browser and device information, pages viewed, API calls, timestamps, and error\n    and delivery events.\n- category: communication\n  text: The content and metadata of messages sent and received through the Service — including inbound replies from\n    Recipients\n- category: identifying\n  text: When you open a merchant checkout, Shopify and the merchant process the information needed for your order,\n    which can include your name, email address, phone number, shipping and billing addresses, payment information,\n    and purchases.\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: authenticate you, deliver messages, run agents, and show conversation history'\n- purpose: Operate AI features\n  text: 'Operate AI features: message content is processed by machine-learning models to generate agent replies,\n    apply compliance checks, and take configured actions'\n- purpose: Enforce compliance\n  text: 'Enforce compliance: process STOP and\
  \ opt-out keywords, maintain suppression lists, keep consent and audit\n    records'\n- purpose: Bill for paid plans\n  text: Bill for paid plans and manage subscriptions\n- purpose: Protect the Service\n  text: 'Protect the Service: prevent spam, fraud, and abuse; enforce rate limits; secure accounts; debug and fix\n    problems'\nretention:\n- scope: Account and workspace data\n  period: for the life of the account\n  text: 'Account and workspace data: for the life of the account'\n- scope: Opt-out and consent records, and audit logs\n  period: retained even after related content is deleted\n  text: 'Opt-out and consent records, and audit logs: retained even after related content is deleted'\n- scope: Log data\n  period: for a limited operational window\n  text: 'Log data: for a limited operational window, then deleted or aggregated.'\nresidency:\n- region: United States\n  text: We are based in the United States and process data on servers in the United States.\ntransfers:\n- mechanism:\
  \ other\n  text: under appropriate safeguards where required by law\nsubprocessors:\n  url: null\n  text: Subprocessors. Infrastructure vendors that host our systems and databases, deliver SMS/iMessage and email,\n    provide AI model inference, process payments, and provide analytics for reliability.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy address to request deletion, or delete your workspace\n  text: Deletion. You can delete your workspace or ask us to delete your data, subject to the retention rules above.\nrights:\n- right: Access and portability\n  text: Access and portability. You can request a copy or export of the data we hold about you.\n- right: Correction\n  text: Correction. You can update workspace information in the product or ask us to correct inaccurate data.\n- right: Deletion\n  text: Deletion. You can delete your workspace or ask us to delete your data, subject to the retention rules above.\n- right: Opt out of messages\n\
  \  text: Recipients can reply STOP on any thread; marketing emails include unsubscribe links.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/osis-co/privacy/osis-co-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from osis-co's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Communications
- Software-as-a-Service
- Customer Service
---
