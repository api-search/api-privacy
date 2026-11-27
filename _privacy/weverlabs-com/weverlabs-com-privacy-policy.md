---
api_specs:
- filename: weverlabs-com-openapi.json
  format: json
  label: Wever Labs Agent API
  slug: wever-labs-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weverlabs-com/openapi/weverlabs-com-openapi.json
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address, request time, requested URL, user agent, referrer, TLS and network information, and error or abuse signals
  - category: contact
    text: If you email Wever Labs, we process your address, message, attachments, and related correspondence to respond and maintain a support record.
  - category: financial
    text: Paid calls settle in native USDC on Base mainnet. The service records the wallet address, authorization and receipt.
  - category: behavioral
    text: Compatibility reports store the named client, connection stage, success state, optional bounded notes, and a one-way digest of any reporter value.
  - category: contact
    text: The boutique uses contact details, shipping addresses and order records to fulfill purchases and handle order questions or refunds.
  deletion:
    route: Email hello@weverlabs.com to ask about deletion
    text: You may ask about access, correction, or deletion of information associated with you by contacting hello@weverlabs.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the connector and paid functions
    text: Provide the free connector, discovery, connection, mandate, settlement, fulfillment, verification, receipt, and recovery functions.
  - purpose: Security and abuse prevention
    text: Prevent replay, duplicate economic effects, fraud, abuse, and unauthorized access.
  - purpose: Maintenance and improvement
    text: Maintain availability, measure compatibility, investigate failures, and improve protocol support.
  - purpose: Support and legal requests
    text: Respond to support, security, legal, and operational requests.
  retention:
  - period: operating life of the service
    scope: Durable transaction, ledger, mandate, fulfillment, evidence, receipt, reconciliation, and replay-protection records
    text: Durable transaction, ledger, mandate, fulfillment, evidence, receipt, reconciliation, and replay-protection records, including records associated with mainnet settlement, are retained for the operating life of the service and longer when needed
  - period: while useful
    scope: Operational telemetry and compatibility records
    text: Operational telemetry and compatibility records are retained while useful for service operation, reliability, security, and protocol support.
  - period: indefinitely
    scope: Public blockchain data
    text: Public blockchain data may remain available indefinitely, regardless of Wever Labs retention choices.
  rights:
  - right: access
    text: You may ask about access, correction, or deletion of information associated with you by contacting hello@weverlabs.com .
  - right: correction
    text: You may ask about access, correction, or deletion of information associated with you by contacting hello@weverlabs.com .
  - right: deletion
    text: We may need to verify the request and may retain records where integrity, security, legal obligations, or public blockchain limits prevent deletion.
  role:
    text: Wever Labs is the publisher and operator for these services.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Wever Labs uses Netlify for website hosting and Cloudflare for service infrastructure. Stripe processes boutique card payments.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: weverlabs-com
provenance_date: '2026-11-10'
provider_name: weverlabs-com
provider_slug: weverlabs-com
slug: weverlabs-com-privacy-policy
source_date: '2026-11-10'
source_filename: weverlabs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://weverlabs.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: weverlabs-com\naid: weverlabs-com\nurl: https://weverlabs.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Wever Labs is the publisher and operator for these services.\ndata_categories:\n- category: identifying\n  text: IP address, request time, requested URL, user agent, referrer, TLS and network information, and error or\n    abuse signals\n- category: contact\n  text: If you email Wever Labs, we process your address, message, attachments, and related correspondence to respond\n    and maintain a support record.\n- category: financial\n  text: Paid calls settle in native USDC\
  \ on Base mainnet. The service records the wallet address, authorization\n    and receipt.\n- category: behavioral\n  text: Compatibility reports store the named client, connection stage, success state, optional bounded notes, and\n    a one-way digest of any reporter value.\n- category: contact\n  text: The boutique uses contact details, shipping addresses and order records to fulfill purchases and handle\n    order questions or refunds.\npurposes:\n- purpose: Provide the connector and paid functions\n  text: Provide the free connector, discovery, connection, mandate, settlement, fulfillment, verification, receipt,\n    and recovery functions.\n- purpose: Security and abuse prevention\n  text: Prevent replay, duplicate economic effects, fraud, abuse, and unauthorized access.\n- purpose: Maintenance and improvement\n  text: Maintain availability, measure compatibility, investigate failures, and improve protocol support.\n- purpose: Support and legal requests\n  text: Respond to support,\
  \ security, legal, and operational requests.\nretention:\n- scope: Durable transaction, ledger, mandate, fulfillment, evidence, receipt, reconciliation, and replay-protection\n    records\n  period: operating life of the service\n  text: Durable transaction, ledger, mandate, fulfillment, evidence, receipt, reconciliation, and replay-protection\n    records, including records associated with mainnet settlement, are retained for the operating life of the service\n    and longer when needed\n- scope: Operational telemetry and compatibility records\n  period: while useful\n  text: Operational telemetry and compatibility records are retained while useful for service operation, reliability,\n    security, and protocol support.\n- scope: Public blockchain data\n  period: indefinitely\n  text: Public blockchain data may remain available indefinitely, regardless of Wever Labs retention choices.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Wever Labs uses Netlify for website\
  \ hosting and Cloudflare for service infrastructure. Stripe processes\n    boutique card payments.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@weverlabs.com to ask about deletion\n  text: You may ask about access, correction, or deletion of information associated with you by contacting hello@weverlabs.com\n    .\nrights:\n- right: access\n  text: You may ask about access, correction, or deletion of information associated with you by contacting hello@weverlabs.com\n    .\n- right: correction\n  text: You may ask about access, correction, or deletion of information associated with you by contacting hello@weverlabs.com\n    .\n- right: deletion\n  text: We may need to verify the request and may retain records where integrity, security, legal obligations, or\n    public blockchain limits prevent deletion.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/weverlabs-com/privacy/weverlabs-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from weverlabs-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Payments
- Infrastructure
- Platform
---
