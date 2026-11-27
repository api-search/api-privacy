---
api_specs:
- filename: chainaware-ai-behaviour-prediction-api-api-openapi.yml
  format: yaml
  label: ChainAware.ai Behaviour Prediction API
  slug: chainaware-ai-behaviour-prediction-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainaware-ai/openapi/chainaware-ai-behaviour-prediction-api-api-openapi.yml
- filename: chainaware-ai-credit-score-api-api-openapi.yml
  format: yaml
  label: ChainAware.ai Credit Score API
  slug: chainaware-ai-credit-score-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainaware-ai/openapi/chainaware-ai-credit-score-api-api-openapi.yml
- filename: chainaware-ai-fraud-api-api-openapi.yml
  format: yaml
  label: ChainAware.ai Fraud API
  slug: chainaware-ai-fraud-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainaware-ai/openapi/chainaware-ai-fraud-api-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Wallet addresses you choose to connect or submit for analysis.
  - category: contact
    text: Email address, only if you voluntarily provide one (for example, to contact support or subscribe to updates).
  - category: device
    text: Technical and usage information collected automatically when you visit the Platform, including IP address, approximate location derived from IP address, browser and device type, referring pages, and pages visited on the Platform.
  - category: behavioral
    text: Session and visitor identifiers, and information about the pages and tools you interact with on the Platform, used to personalize on-page content as described in Sections 3 and 4.
  - category: professional
    text: To register an Enterprise Account, we additionally collect company name, registered business address, and contact details for the individuals managing the account
  deletion:
    route: Email support@chainaware.ai to request deletion
    text: ask us to delete it
  dpa:
    available: true
    text: our processing is governed by a separate Data Processing Agreement with that Business Client
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the Platform
    text: Provide, maintain, and improve the Platform and its Services
  - purpose: Wallet screening for fraud and risk
    text: Screen connected wallets for fraud and risk indicators, and restrict access where warranted
  - purpose: Enterprise account administration and billing
    text: Register and administer Enterprise Accounts, including billing for paid Services
  - purpose: Personalization via Growth Agents
    text: these identifiers are used by our own Growth Agents technology to personalize the messages, prompts, and content shown to you directly on the Platform.
  - purpose: Legal compliance
    text: Comply with applicable law and respond to lawful requests from public authorities
  retention:
  - period: null
    scope: Personal data generally
    text: We retain personal data only for as long as necessary for the purposes described in this Policy, or as required by applicable law
  - period: without time limit
    scope: Aggregated or anonymized data
    text: Aggregated or anonymized data that no longer identifies an individual may be retained without time limit.
  rights:
  - right: Access
    text: access the personal data we hold about you
  - right: Correction
    text: request correction of inaccurate data
  - right: Erasure
    text: request erasure of your data
  - right: Restriction
    text: request restriction of processing in certain circumstances
  - right: Objection
    text: object to processing based on legitimate interests
  - right: Withdraw consent
    text: you may withdraw that consent at any time
  - right: Opt out of sale or sharing (US states)
    text: opt out of the “sale” or “sharing” of your personal information, where applicable
  role:
    text: 'We act as controller of personal data relating to: visitors to the Platform’s website and free tools (“Individual Users”); and the account, billing, and contact information of Business Clients who register an Enterprise Account.'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where we transfer personal data internationally, we take reasonable steps to ensure it receives an appropriate level of protection consistent with applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ChainAware.ai
provenance_date: '2026-11-09'
provider_name: ChainAware.ai
provider_slug: chainaware-ai
slug: chainaware-ai-privacy-policy
source_date: '2026-11-09'
source_filename: chainaware-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chainaware.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChainAware.ai\naid: chainaware-ai\nurl: https://chainaware.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'We act as controller of personal data relating to: visitors to the Platform’s website and free tools (“Individual\n    Users”); and the account, billing, and contact information of Business Clients who register an Enterprise Account.'\ndata_categories:\n- category: identifying\n  text: Wallet addresses you choose to connect or submit for analysis.\n- category: contact\n  text: Email address, only if you voluntarily provide one (for example, to contact support or subscribe to updates).\n\
  - category: device\n  text: Technical and usage information collected automatically when you visit the Platform, including IP address,\n    approximate location derived from IP address, browser and device type, referring pages, and pages visited on\n    the Platform.\n- category: behavioral\n  text: Session and visitor identifiers, and information about the pages and tools you interact with on the Platform,\n    used to personalize on-page content as described in Sections 3 and 4.\n- category: professional\n  text: To register an Enterprise Account, we additionally collect company name, registered business address, and\n    contact details for the individuals managing the account\npurposes:\n- purpose: Provide, maintain, and improve the Platform\n  text: Provide, maintain, and improve the Platform and its Services\n- purpose: Wallet screening for fraud and risk\n  text: Screen connected wallets for fraud and risk indicators, and restrict access where warranted\n- purpose: Enterprise account\
  \ administration and billing\n  text: Register and administer Enterprise Accounts, including billing for paid Services\n- purpose: Personalization via Growth Agents\n  text: these identifiers are used by our own Growth Agents technology to personalize the messages, prompts, and\n    content shown to you directly on the Platform.\n- purpose: Legal compliance\n  text: Comply with applicable law and respond to lawful requests from public authorities\nretention:\n- scope: Personal data generally\n  period: null\n  text: We retain personal data only for as long as necessary for the purposes described in this Policy, or as required\n    by applicable law\n- scope: Aggregated or anonymized data\n  period: without time limit\n  text: Aggregated or anonymized data that no longer identifies an individual may be retained without time limit.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where we transfer personal data internationally, we take reasonable steps to ensure it receives an appropriate\n\
  \    level of protection consistent with applicable law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: our processing is governed by a separate Data Processing Agreement with that Business Client\ndeletion:\n  route: Email support@chainaware.ai to request deletion\n  text: ask us to delete it\nrights:\n- right: Access\n  text: access the personal data we hold about you\n- right: Correction\n  text: request correction of inaccurate data\n- right: Erasure\n  text: request erasure of your data\n- right: Restriction\n  text: request restriction of processing in certain circumstances\n- right: Objection\n  text: object to processing based on legitimate interests\n- right: Withdraw consent\n  text: you may withdraw that consent at any time\n- right: Opt out of sale or sharing (US states)\n  text: opt out of the “sale” or “sharing” of your personal information, where applicable\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal\
  \ data.\n"
source_yaml_url: https://artifacts.apis.io/chainaware-ai/privacy/chainaware-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ChainAware.ai's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Web3
- DeFi
- Fraud Prevention
- AML
- Compliance
- Credit Scoring
- Risk Scoring
- Smart Contract Security
- Agent Trust
- MCP
- A2A
- x402
- Agents
- Agent-Native
- Estonia
---
