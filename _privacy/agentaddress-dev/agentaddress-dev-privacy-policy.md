---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: communication
    text: We store address records, optional task identifiers, received HTTP event data and email content, message metadata, acknowledgement records, small JSON task context, contact verification records, and pending outbound messages.
  - category: device
    text: We also process technical information, such as IP addresses, request information, and usage counts, to operate the service, enforce limits, and prevent abuse.
  - category: behavioral
    text: Google Analytics may use cookies and collect browser, device, and usage information.
  deletion:
    route: authenticated API
    text: you can set an expiry when creating one or delete an address and its events through the authenticated API.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and deliver events
    text: We use information to receive and deliver events, maintain the service, troubleshoot problems, and protect against misuse.
  - purpose: website analytics
    text: Public website pages use Google Analytics to understand visits and navigation.
  residency:
  - region: other countries
    text: Information may be processed in countries other than your own.
  retention:
  - period: 30 days
    scope: events
    text: Events are retained for 30 days.
  - period: no expiry by default
    scope: addresses
    text: Addresses have no expiry by default, but you can set an expiry when creating one
  - period: 30 days
    scope: recovery receipts
    text: Recovery receipts expire after 30 days.
  - period: at least 24 hours
    scope: outbound idempotency records
    text: Outbound idempotency records are retained for at least 24 hours
  rights:
  - right: access, correct, or delete
    text: Depending on your location, you may have rights to access, correct, or delete personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Service providers process information on our behalf, including Render for hosting, MongoDB for storage, and Resend for receiving email, sending authorized messages, and contact verification.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentAddress
provenance_date: '2026-11-09'
provider_name: AgentAddress
provider_slug: agentaddress-dev
slug: agentaddress-dev-privacy-policy
source_date: '2026-11-09'
source_filename: agentaddress-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentaddress.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentAddress\naid: agentaddress-dev\nurl: https://agentaddress.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: communication\n  text: We store address records, optional task identifiers, received HTTP event data and email content, message\n    metadata, acknowledgement records, small JSON task context, contact verification records, and pending outbound\n    messages.\n- category: device\n  text: We also process technical information, such as IP addresses, request information, and usage counts, to operate\n    the service, enforce limits, and prevent\
  \ abuse.\n- category: behavioral\n  text: Google Analytics may use cookies and collect browser, device, and usage information.\npurposes:\n- purpose: operate and deliver events\n  text: We use information to receive and deliver events, maintain the service, troubleshoot problems, and protect\n    against misuse.\n- purpose: website analytics\n  text: Public website pages use Google Analytics to understand visits and navigation.\nretention:\n- scope: events\n  period: 30 days\n  text: Events are retained for 30 days.\n- scope: addresses\n  period: no expiry by default\n  text: Addresses have no expiry by default, but you can set an expiry when creating one\n- scope: recovery receipts\n  period: 30 days\n  text: Recovery receipts expire after 30 days.\n- scope: outbound idempotency records\n  period: at least 24 hours\n  text: Outbound idempotency records are retained for at least 24 hours\nresidency:\n- region: other countries\n  text: Information may be processed in countries other than\
  \ your own.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers process information on our behalf, including Render for hosting, MongoDB for storage,\n    and Resend for receiving email, sending authorized messages, and contact verification.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: authenticated API\n  text: you can set an expiry when creating one or delete an address and its events through the authenticated API.\nrights:\n- right: access, correct, or delete\n  text: Depending on your location, you may have rights to access, correct, or delete personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/agentaddress-dev/privacy/agentaddress-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from AgentAddress's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Webhook
- Email
- Agents
---
