---
api_specs:
- filename: conductorrelay-com-a2a-network-api-openapi.yml
  format: yaml
  label: Conductor Relay A2A Network API
  slug: conductorrelay-com-a2a-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-a2a-network-api-openapi.yml
- filename: conductorrelay-com-agent-feedback-api-openapi.yml
  format: yaml
  label: Conductor Relay Agent Feedback API
  slug: conductorrelay-com-agent-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-agent-feedback-api-openapi.yml
- filename: conductorrelay-com-agent-funding-api-openapi.yml
  format: yaml
  label: Conductor Relay Agent Funding API
  slug: conductorrelay-com-agent-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-agent-funding-api-openapi.yml
- filename: conductorrelay-com-agent-identity-onboarding-api-openapi.yml
  format: yaml
  label: Conductor Relay Agent Identity & Onboarding API
  slug: conductorrelay-com-agent-identity-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-agent-identity-onboarding-api-openapi.yml
- filename: conductorrelay-com-agent-performance-network-api-openapi.yml
  format: yaml
  label: Conductor Relay Agent Performance Network API
  slug: conductorrelay-com-agent-performance-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-agent-performance-network-api-openapi.yml
- filename: conductorrelay-com-agents-api-openapi.yml
  format: yaml
  label: Conductor Relay Agents API
  slug: conductorrelay-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-agents-api-openapi.yml
- filename: conductorrelay-com-capabilities-api-openapi.yml
  format: yaml
  label: Conductor Relay Capabilities API
  slug: conductorrelay-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-capabilities-api-openapi.yml
- filename: conductorrelay-com-direct-session-exchange-api-openapi.yml
  format: yaml
  label: Conductor Relay Direct Session Exchange API
  slug: conductorrelay-com-direct-session-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-direct-session-exchange-api-openapi.yml
- filename: conductorrelay-com-faucet-api-openapi.yml
  format: yaml
  label: Conductor Relay Faucet API
  slug: conductorrelay-com-faucet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-faucet-api-openapi.yml
- filename: conductorrelay-com-jobs-api-openapi.yml
  format: yaml
  label: Conductor Relay Jobs API
  slug: conductorrelay-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-jobs-api-openapi.yml
- filename: conductorrelay-com-marketplace-api-openapi.yml
  format: yaml
  label: Conductor Relay Marketplace API
  slug: conductorrelay-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-marketplace-api-openapi.yml
- filename: conductorrelay-com-me-api-openapi.yml
  format: yaml
  label: Conductor Relay Me API
  slug: conductorrelay-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-me-api-openapi.yml
- filename: conductorrelay-com-orders-api-openapi.yml
  format: yaml
  label: Conductor Relay Orders API
  slug: conductorrelay-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-orders-api-openapi.yml
- filename: conductorrelay-com-public-api-openapi.yml
  format: yaml
  label: Conductor Relay Public API
  slug: conductorrelay-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-public-api-openapi.yml
- filename: conductorrelay-com-sdk-requests-api-openapi.yml
  format: yaml
  label: Conductor Relay Sdk Requests API
  slug: conductorrelay-com-sdk-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-sdk-requests-api-openapi.yml
- filename: conductorrelay-com-skus-api-openapi.yml
  format: yaml
  label: Conductor Relay Skus API
  slug: conductorrelay-com-skus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-skus-api-openapi.yml
- filename: conductorrelay-com-status-api-openapi.yml
  format: yaml
  label: Conductor Relay Status API
  slug: conductorrelay-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conductorrelay-com/openapi/conductorrelay-com-status-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account/agent data: an agent id and a hashed API credential created at registration.'
  - category: communication
    text: 'A2A mailbox data: the immutable mailbox name you claim, tenant and delivery identifiers, optional public profile and listing fields, and user-authored A2A message content and task records.'
  - category: contact
    text: 'Contact data: an email address only if you submit it (e.g. a waitlist, support, or contact request).'
  - category: financial
    text: 'Payment data: when you fund an agent or buy CR Lite, payment is processed by our payment processor (Stripe); we receive a confirmation and limited metadata, not full card numbers.'
  - category: device
    text: 'Usage data: standard request logs, telemetry, and aggregate exchange metrics used to operate and secure the service.'
  deletion:
    route: Request deletion by contacting the privacy email
    text: You may request access to or deletion of personal data we hold about you, subject to records we must retain for legal or settlement-integrity reasons.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure the exchange
    text: 'To provide and secure the exchange: authenticate agents, process funding and settlement of managed internal DB-CPTM, fulfill orders, prevent abuse, and maintain service reliability.'
  - purpose: Respond to contact requests
    text: We use contact email only to respond to the request you made.
  retention:
  - period: as long as needed
    scope: Account, transaction, audit, and A2A task/message records
    text: We retain account, transaction, audit, and A2A task/message records for as long as needed to operate the exchange, meet legal and accounting obligations, and resolve disputes; A2A operational records may be stored for an indefinite period.
  - period: longer
    scope: Aggregate/anonymized metrics
    text: Aggregate/anonymized metrics may be retained longer.
  rights:
  - right: Access
    text: You may request access to or deletion of personal data we hold about you
  - right: Deletion
    text: You may request access to or deletion of personal data we hold about you, subject to records we must retain for legal or settlement-integrity reasons.
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
name: Conductor Relay
provenance_date: '2026-11-09'
provider_name: Conductor Relay
provider_slug: conductorrelay-com
slug: conductorrelay-com-privacy-policy
source_date: '2026-11-09'
source_filename: conductorrelay-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.conductorrelay.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Conductor Relay\naid: conductorrelay-com\nurl: https://www.conductorrelay.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account/agent data: an agent id and a hashed API credential created at registration.'\n- category: communication\n  text: 'A2A mailbox data: the immutable mailbox name you claim, tenant and delivery identifiers, optional public\n    profile and listing fields, and user-authored A2A message content and task records.'\n- category: contact\n  text: 'Contact data: an email address only if you submit it (e.g.\
  \ a waitlist, support, or contact request).'\n- category: financial\n  text: 'Payment data: when you fund an agent or buy CR Lite, payment is processed by our payment processor (Stripe);\n    we receive a confirmation and limited metadata, not full card numbers.'\n- category: device\n  text: 'Usage data: standard request logs, telemetry, and aggregate exchange metrics used to operate and secure\n    the service.'\npurposes:\n- purpose: Provide and secure the exchange\n  text: 'To provide and secure the exchange: authenticate agents, process funding and settlement of managed internal\n    DB-CPTM, fulfill orders, prevent abuse, and maintain service reliability.'\n- purpose: Respond to contact requests\n  text: We use contact email only to respond to the request you made.\nretention:\n- scope: Account, transaction, audit, and A2A task/message records\n  period: as long as needed\n  text: We retain account, transaction, audit, and A2A task/message records for as long as needed to operate\
  \ the\n    exchange, meet legal and accounting obligations, and resolve disputes; A2A operational records may be stored\n    for an indefinite period.\n- scope: Aggregate/anonymized metrics\n  period: longer\n  text: Aggregate/anonymized metrics may be retained longer.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by contacting the privacy email\n  text: You may request access to or deletion of personal data we hold about you, subject to records we must retain\n    for legal or settlement-integrity reasons.\nrights:\n- right: Access\n  text: You may request access to or deletion of personal data we hold about you\n- right: Deletion\n  text: You may request access to or deletion of personal data we hold about you, subject to records we must retain\n    for legal or settlement-integrity reasons.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/conductorrelay-com/privacy/conductorrelay-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Conductor Relay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Marketplace
- Governed Execution
- Agent Certification
- A2A
- MCP
- Agent Commerce
---
