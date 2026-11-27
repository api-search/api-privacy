---
api_specs:
- filename: agentrapay-ai-agents-api-openapi.yml
  format: yaml
  label: Agentra Agents API
  slug: agentrapay-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrapay-ai/openapi/agentrapay-ai-agents-api-openapi.yml
- filename: agentrapay-ai-authorizations-api-openapi.yml
  format: yaml
  label: Agentra Authorizations API
  slug: agentrapay-ai-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrapay-ai/openapi/agentrapay-ai-authorizations-api-openapi.yml
- filename: agentrapay-ai-health-api-openapi.yml
  format: yaml
  label: Agentra Health API
  slug: agentrapay-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrapay-ai/openapi/agentrapay-ai-health-api-openapi.yml
- filename: agentrapay-ai-trust-api-openapi.yml
  format: yaml
  label: Agentra Trust API
  slug: agentrapay-ai-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrapay-ai/openapi/agentrapay-ai-trust-api-openapi.yml
- filename: agentrapay-ai-wallets-api-openapi.yml
  format: yaml
  label: Agentra Wallets API
  slug: agentrapay-ai-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentrapay-ai/openapi/agentrapay-ai-wallets-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register an agent via the API, we collect the agent name, purpose, and operator name you provide.
  - category: contact
    text: we collect the identity fields you provide (agent name, purpose, operator name, operator contact, attestations)
  - category: financial
    text: We record authorization requests, settlement reports, trust score lookups, and referral events. This includes agent IDs, counterparty addresses, transaction amounts, timestamps, and status.
  - category: device
    text: We log API endpoint usage, request timestamps, and IP addresses for rate limiting, abuse prevention, and service monitoring.
  - category: financial
    text: When you provision a wallet, we store a reference to the wallet (external wallet ID, wallet address, provider name).
  deletion:
    route: Email support@agentrapay.ai to request deletion of your agent account
    text: If you request deletion of your agent account, we will delete your registration data and API key hash.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Trust tiers and reputation
    text: Calculate and update trust tiers and reputation scores
  - purpose: Abuse and fraud prevention
    text: Detect and prevent abuse, fraud, and unauthorized access
  - purpose: Analytics
    text: Generate aggregate, anonymized analytics (e.g., network stats, performance metrics)
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: United States
    text: The Service is operated from the United States.
  retention:
  - period: lifetime of the Service
    scope: Agent registration data, transaction records, reputation history
    text: We retain agent registration data, transaction records, and reputation history for the lifetime of the Service.
  - period: 90 days
    scope: API usage logs
    text: API usage logs are retained for 90 days.
  - period: 30 days
    scope: IP addresses in access logs
    text: IP addresses in access logs are retained for 30 days.
  rights:
  - right: Access
    text: Access. Request a copy of the data we hold about your agent(s).
  - right: Correction
    text: Correction. Request correction of inaccurate data via KYA resubmission.
  - right: Deletion
    text: Deletion. Request deletion of your agent account (subject to the limitations in Section 4).
  - right: Portability
    text: Portability. Request your transaction history in a machine-readable format.
  - right: Opt out of sale (California)
    text: opt out of the sale of personal information
  role:
    text: This Privacy Policy describes how ProTech Data Security Services LLC d/b/a Agentra ("Agentra," "we," "us," or "our") collects, uses, and shares information
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: We use third-party infrastructure providers including Railway (hosting), Turnkey (wallet provisioning), and Cloudflare (DNS and CDN).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentra
provenance_date: '2026-11-09'
provider_name: Agentra
provider_slug: agentrapay-ai
slug: agentrapay-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agentrapay-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentrapay.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentra\naid: agentrapay-ai\nurl: https://agentrapay.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy describes how ProTech Data Security Services LLC d/b/a Agentra (\"Agentra,\" \"we,\" \"us,\"\n    or \"our\") collects, uses, and shares information\ndata_categories:\n- category: identifying\n  text: When you register an agent via the API, we collect the agent name, purpose, and operator name you provide.\n- category: contact\n  text: we collect the identity fields you provide (agent name, purpose, operator name, operator contact, attestations)\n- category: financial\n\
  \  text: We record authorization requests, settlement reports, trust score lookups, and referral events. This includes\n    agent IDs, counterparty addresses, transaction amounts, timestamps, and status.\n- category: device\n  text: We log API endpoint usage, request timestamps, and IP addresses for rate limiting, abuse prevention, and\n    service monitoring.\n- category: financial\n  text: When you provision a wallet, we store a reference to the wallet (external wallet ID, wallet address, provider\n    name).\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service\n- purpose: Trust tiers and reputation\n  text: Calculate and update trust tiers and reputation scores\n- purpose: Abuse and fraud prevention\n  text: Detect and prevent abuse, fraud, and unauthorized access\n- purpose: Analytics\n  text: Generate aggregate, anonymized analytics (e.g., network stats, performance metrics)\n- purpose: Legal compliance\n  text: Comply with legal\
  \ obligations\nretention:\n- scope: Agent registration data, transaction records, reputation history\n  period: lifetime of the Service\n  text: We retain agent registration data, transaction records, and reputation history for the lifetime of the Service.\n- scope: API usage logs\n  period: 90 days\n  text: API usage logs are retained for 90 days.\n- scope: IP addresses in access logs\n  period: 30 days\n  text: IP addresses in access logs are retained for 30 days.\nresidency:\n- region: United States\n  text: The Service is operated from the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use third-party infrastructure providers including Railway (hosting), Turnkey (wallet provisioning),\n    and Cloudflare (DNS and CDN).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@agentrapay.ai to request deletion of your agent account\n  text: If you request deletion of your agent account, we will delete your registration data and API\
  \ key hash.\nrights:\n- right: Access\n  text: Access. Request a copy of the data we hold about your agent(s).\n- right: Correction\n  text: Correction. Request correction of inaccurate data via KYA resubmission.\n- right: Deletion\n  text: Deletion. Request deletion of your agent account (subject to the limitations in Section 4).\n- right: Portability\n  text: Portability. Request your transaction history in a machine-readable format.\n- right: Opt out of sale (California)\n  text: opt out of the sale of personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/agentrapay-ai/privacy/agentrapay-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Agentra's own page on 2026-11-09.
synthetic: false
tags:
- Identity Verification
- Reputation Scoring
- Transaction Authorization
- Non-Custodial Wallet
- Agent Infrastructure
---
