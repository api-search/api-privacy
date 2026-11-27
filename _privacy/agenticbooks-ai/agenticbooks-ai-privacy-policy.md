---
api_specs:
- filename: agenticbooks-ai-openapi-generated.yml
  format: yaml
  label: AgenticBooks API
  slug: agenticbooks-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticbooks-ai/openapi/_ae-authored/agenticbooks-ai-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, organization, and authentication metadata
  - category: financial
    text: financial event data such as transactions, charges, payouts, transfers, currency conversions, account balances
  - category: contact
    text: communications with us
  - category: device
    text: IP address, browser/device information, pages and features used, API and MCP request metadata
  - category: behavioral
    text: Service usage data
  - category: other
    text: personal data of your counterparties that appears within them
  deletion:
    route: Contact us via the Contact page
    text: When you exercise deletion rights or close your account, we will, consistent with applicable law
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: ingest, normalize, classify, and present your financial events as three-statement accounting
  - purpose: Security
    text: detect, prevent, and investigate fraud, abuse, and security incidents
  - purpose: Billing and account management
    text: Bill you and manage your account.
  - purpose: Product improvement
    text: Improve the Service and develop new features, using aggregated or de-identified data wherever practical.
  - purpose: Legal compliance
    text: Comply with legal obligations and enforce our terms.
  residency:
  - region: EU (Frankfurt)
    text: our primary database is hosted in the EU (Frankfurt)
  - region: EU
    text: your documents and books are stored in the EU
  retention:
  - period: null
    scope: Account personal data
    text: We retain personal data for as long as your account is active and as needed to provide the Service
  - period: null
    scope: Raw source events and audit trail
    text: Raw source events ( raw_events ) and the audit trail ( audit_trail ) are never modified or deleted.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Rectify
    text: Rectify inaccurate or incomplete data
  - right: Erase
    text: Erase data, where applicable and not subject to a legal retention or immutable-audit requirement.
  - right: Restrict or object
    text: Restrict or object to certain processing.
  - right: Portability
    text: Data portability — receive certain data in a structured, machine-readable format
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  - right: Complain
    text: Lodge a complaint with a supervisory authority
  role:
    text: We act as a controller for the data we collect to operate our business
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Neon — primary database hosting (EU, Frankfurt). Railway — application hosting. Clerk — authentication (see Section 2). Stripe — payment processing for your subscription.
    url: null
  transfers:
  - mechanism: SCC
    text: the Standard Contractual Clauses recognized by the Swiss Federal Council and the European Commission (with the Swiss addendum where required)
  - mechanism: adequacy
    text: Switzerland is recognized by the EU as providing an adequate level of data protection
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgenticBooks
provenance_date: '2026-11-09'
provider_name: AgenticBooks
provider_slug: agenticbooks-ai
slug: agenticbooks-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agenticbooks-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agenticbooks.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgenticBooks\naid: agenticbooks-ai\nurl: https://www.agenticbooks.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as a controller for the data we collect to operate our business\ndata_categories:\n- category: identifying\n  text: your name, email address, organization, and authentication metadata\n- category: financial\n  text: financial event data such as transactions, charges, payouts, transfers, currency conversions, account balances\n- category: contact\n  text: communications with us\n- category: device\n  text: IP address, browser/device information, pages and features used,\
  \ API and MCP request metadata\n- category: behavioral\n  text: Service usage data\n- category: other\n  text: personal data of your counterparties that appears within them\npurposes:\n- purpose: Provide the Service\n  text: ingest, normalize, classify, and present your financial events as three-statement accounting\n- purpose: Security\n  text: detect, prevent, and investigate fraud, abuse, and security incidents\n- purpose: Billing and account management\n  text: Bill you and manage your account.\n- purpose: Product improvement\n  text: Improve the Service and develop new features, using aggregated or de-identified data wherever practical.\n- purpose: Legal compliance\n  text: Comply with legal obligations and enforce our terms.\nretention:\n- scope: Account personal data\n  period: null\n  text: We retain personal data for as long as your account is active and as needed to provide the Service\n- scope: Raw source events and audit trail\n  period: null\n  text: Raw source events ( raw_events\
  \ ) and the audit trail ( audit_trail ) are never modified or deleted.\nresidency:\n- region: EU (Frankfurt)\n  text: our primary database is hosted in the EU (Frankfurt)\n- region: EU\n  text: your documents and books are stored in the EU\ntransfers:\n- mechanism: SCC\n  text: the Standard Contractual Clauses recognized by the Swiss Federal Council and the European Commission (with\n    the Swiss addendum where required)\n- mechanism: adequacy\n  text: Switzerland is recognized by the EU as providing an adequate level of data protection\nsubprocessors:\n  url: null\n  text: Neon — primary database hosting (EU, Frankfurt). Railway — application hosting. Clerk — authentication (see\n    Section 2). Stripe — payment processing for your subscription.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us via the Contact page\n  text: When you exercise deletion rights or close your account, we will, consistent with applicable law\nrights:\n- right: Access\n  text:\
  \ Access the personal data we hold about you.\n- right: Rectify\n  text: Rectify inaccurate or incomplete data\n- right: Erase\n  text: Erase data, where applicable and not subject to a legal retention or immutable-audit requirement.\n- right: Restrict or object\n  text: Restrict or object to certain processing.\n- right: Portability\n  text: Data portability — receive certain data in a structured, machine-readable format\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\n- right: Complain\n  text: Lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/agenticbooks-ai/privacy/agenticbooks-ai-privacy-policy.yml
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
summary_line: 28 quoted statements, read from AgenticBooks's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Bookkeeping
- Finance
- Automation
- Software-as-a-Service
---
