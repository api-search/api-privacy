---
api_specs:
- filename: forcedream-ai-oracle-api-openapi.yml
  format: yaml
  label: ForceDream Oracle API
  slug: forcedream-ai-oracle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forcedream-ai/openapi/forcedream-ai-oracle-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address at signup.
  - category: behavioral
    text: Usage data (API calls, agent deployments, earnings).
  - category: device
    text: Technical data (IP address, browser type, timestamps).
  - category: financial
    text: Payment data processed by our PSPs — not stored by us directly.
  - category: financial
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: Payment card data, bank account details, transaction records
  - category: identifying
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: User IDs (hashed), earn records, balance data
  - category: contact
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: Phone number, transaction amount
  deletion:
    route: API endpoint DELETE /api/user/data
    text: 'To delete your account: DELETE /api/user/data via the API.'
  dpa:
    available: true
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: All sub-processors are bound by data processing agreements
    url: null
  purposes:
  - purpose: operate the platform
    text: To operate the platform, process earnings and withdrawals, detect fraud, send account notifications, and comply with legal obligations.
  - purpose: Payment processing and subscription billing
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: Payment processing, Stripe Connect payouts, subscription billing
  - purpose: AI model inference
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: Claude AI models — routing engine, earn tasks, agent runtime
  residency:
  - region: eu-west-2 (London)
    text: Primary data stored in eu-west-2 (London).
  - region: eu-west-1 (Ireland)
    text: Backups in eu-west-1 (Ireland).
  - region: USA / London (lhr1)
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: USA / London (lhr1)
  - region: EU (Frankfurt) / USA
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: EU (Frankfurt) / USA
  retention:
  - period: account duration plus 7 years for financial records
    scope: personal data
    text: Personal data retained for account duration plus 7 years for financial records.
  - period: indefinitely
    scope: transaction hashes
    text: cryptographically sealed transaction hashes retained indefinitely as evidence.
  - period: null
    scope: WORM audit hashes
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: WORM audit hashes are retained as required by financial regulations but are disassociated from your personal data.
  rights:
  - right: access
    text: Under UK GDPR you have rights of access, rectification, erasure, portability, and objection.
  - right: access, correction, erasure
    source: https://www.forcedream.com/trust/subprocessors/index.html
    text: Under UK GDPR you have the right to access, correct, or erase your personal data.
  role:
    text: ForceDream Ltd (Company No. 17057770), registered in England and Wales, is the data controller for personal data processed through this platform.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Full list at /trust/subprocessors .
    url: /trust/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ForceDream
provenance_date: '2026-11-09'
provider_name: ForceDream
provider_slug: forcedream-ai
slug: forcedream-ai-privacy-policy
source_date: '2026-11-09'
source_filename: forcedream-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.forcedream.com/privacy/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ForceDream\naid: forcedream-ai\nurl: https://www.forcedream.com/privacy/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.forcedream.com/privacy/index.html\n  - https://www.forcedream.com/trust/subprocessors/index.html\nrole:\n  value: controller\n  text: ForceDream Ltd (Company No. 17057770), registered in England and Wales, is the data controller for personal\n    data processed through this platform.\ndata_categories:\n- category: contact\n  text: Email address at signup.\n- category: behavioral\n  text: Usage data (API calls, agent deployments, earnings).\n- category: device\n  text: Technical\
  \ data (IP address, browser type, timestamps).\n- category: financial\n  text: Payment data processed by our PSPs — not stored by us directly.\n- category: financial\n  text: Payment card data, bank account details, transaction records\n  source: https://www.forcedream.com/trust/subprocessors/index.html\n- category: identifying\n  text: User IDs (hashed), earn records, balance data\n  source: https://www.forcedream.com/trust/subprocessors/index.html\n- category: contact\n  text: Phone number, transaction amount\n  source: https://www.forcedream.com/trust/subprocessors/index.html\npurposes:\n- purpose: operate the platform\n  text: To operate the platform, process earnings and withdrawals, detect fraud, send account notifications, and\n    comply with legal obligations.\n- purpose: Payment processing and subscription billing\n  text: Payment processing, Stripe Connect payouts, subscription billing\n  source: https://www.forcedream.com/trust/subprocessors/index.html\n- purpose: AI model\
  \ inference\n  text: Claude AI models — routing engine, earn tasks, agent runtime\n  source: https://www.forcedream.com/trust/subprocessors/index.html\nretention:\n- scope: personal data\n  period: account duration plus 7 years for financial records\n  text: Personal data retained for account duration plus 7 years for financial records.\n- scope: transaction hashes\n  period: indefinitely\n  text: cryptographically sealed transaction hashes retained indefinitely as evidence.\n- scope: WORM audit hashes\n  period: null\n  text: WORM audit hashes are retained as required by financial regulations but are disassociated from your personal\n    data.\n  source: https://www.forcedream.com/trust/subprocessors/index.html\nresidency:\n- region: eu-west-2 (London)\n  text: Primary data stored in eu-west-2 (London).\n- region: eu-west-1 (Ireland)\n  text: Backups in eu-west-1 (Ireland).\n- region: USA / London (lhr1)\n  text: USA / London (lhr1)\n  source: https://www.forcedream.com/trust/subprocessors/index.html\n\
  - region: EU (Frankfurt) / USA\n  text: EU (Frankfurt) / USA\n  source: https://www.forcedream.com/trust/subprocessors/index.html\ntransfers: []\nsubprocessors:\n  url: /trust/subprocessors\n  text: Full list at /trust/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: All sub-processors are bound by data processing agreements\n  source: https://www.forcedream.com/trust/subprocessors/index.html\ndeletion:\n  route: API endpoint DELETE /api/user/data\n  text: 'To delete your account: DELETE /api/user/data via the API.'\nrights:\n- right: access\n  text: Under UK GDPR you have rights of access, rectification, erasure, portability, and objection.\n- right: access, correction, erasure\n  text: Under UK GDPR you have the right to access, correct, or erase your personal data.\n  source: https://www.forcedream.com/trust/subprocessors/index.html\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/forcedream-ai/privacy/forcedream-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ForceDream's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Agent Marketplace
- MCP
- A2A
- Cryptographic Proofs
- AI Inference Routing
- Agentic Payments
- Agentic Commerce
- Agent-Native
- United Kingdom
---
