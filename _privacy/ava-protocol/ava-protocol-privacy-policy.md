---
api_specs:
- filename: ava-protocol-auth-api-openapi.yml
  format: yaml
  label: Ava Protocol Auth API
  slug: ava-protocol-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-auth-api-openapi.yml
- filename: ava-protocol-executions-api-openapi.yml
  format: yaml
  label: Ava Protocol Executions API
  slug: ava-protocol-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-executions-api-openapi.yml
- filename: ava-protocol-health-api-openapi.yml
  format: yaml
  label: Ava Protocol Health API
  slug: ava-protocol-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-health-api-openapi.yml
- filename: ava-protocol-nodes-api-openapi.yml
  format: yaml
  label: Ava Protocol Nodes API
  slug: ava-protocol-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-nodes-api-openapi.yml
- filename: ava-protocol-operators-api-openapi.yml
  format: yaml
  label: Ava Protocol Operators API
  slug: ava-protocol-operators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-operators-api-openapi.yml
- filename: ava-protocol-secrets-api-openapi.yml
  format: yaml
  label: Ava Protocol Secrets API
  slug: ava-protocol-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-secrets-api-openapi.yml
- filename: ava-protocol-tokens-api-openapi.yml
  format: yaml
  label: Ava Protocol Tokens API
  slug: ava-protocol-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-tokens-api-openapi.yml
- filename: ava-protocol-triggers-api-openapi.yml
  format: yaml
  label: Ava Protocol Triggers API
  slug: ava-protocol-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-triggers-api-openapi.yml
- filename: ava-protocol-wallets-api-openapi.yml
  format: yaml
  label: Ava Protocol Wallets API
  slug: ava-protocol-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-wallets-api-openapi.yml
- filename: ava-protocol-workflows-api-openapi.yml
  format: yaml
  label: Ava Protocol Workflows API
  slug: ava-protocol-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ava-protocol/openapi/ava-protocol-workflows-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Discord user ID Discord username and display name Server role (USER, VERIFIED, AMBASSADOR)
  - category: behavioral
    text: 'Message metadata: channel ID, message ID, timestamp, and the Discord ID of the message author.'
  - category: financial
    text: AP token balance Point transactions, categorized by source (message activity, quest completion, bug bounty, monthly distribution, manual award, purchase, tip)
  - category: financial
    text: Ethereum-compatible wallet address that you voluntarily bind via the /bind-wallet slash command.
  deletion:
    route: Email contact@avaprotocol.org requesting deletion of account record
    text: Delete your account record from our database
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate community features
    text: We use the information above solely to operate the Bot's stated features
  - purpose: Advertising
    text: We do not use your information for advertising.
  - purpose: AI model training
    text: We do not use your information to train AI models.
  residency:
  - region: United States
    text: 'Primary database: PostgreSQL, hosted on Railway (United States region).'
  retention:
  - period: null
    scope: Bot data
    text: We retain the information described in Section 2 for as long as you remain a member of the Ava Protocol Discord server and the community rewards program continues to operate, or until you request deletion under Section 7.
  - period: null
    scope: On-chain records
    text: On-chain transaction records on the Base blockchain are public and permanent and cannot be deleted by us.
  rights:
  - right: Access
    text: Provide a copy of the information we hold about you
  - right: Correction
    text: Correct inaccurate information
  - right: Deletion
    text: Delete your account record from our database
  role:
    text: Ava Protocol is the operator of the Bot and the data controller for the information described below.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ava Protocol
provenance_date: '2026-11-09'
provider_name: Ava Protocol
provider_slug: ava-protocol
slug: ava-protocol-privacy-policy
source_date: '2026-11-09'
source_filename: ava-protocol-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://avaprotocol.org/legal/discord-bot-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ava Protocol\naid: ava-protocol\nurl: https://avaprotocol.org/legal/discord-bot-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Ava Protocol is the operator of the Bot and the data controller for the information described below.\ndata_categories:\n- category: identifying\n  text: Discord user ID Discord username and display name Server role (USER, VERIFIED, AMBASSADOR)\n- category: behavioral\n  text: 'Message metadata: channel ID, message ID, timestamp, and the Discord ID of the message author.'\n- category: financial\n  text: AP token balance Point transactions, categorized by source\
  \ (message activity, quest completion, bug bounty,\n    monthly distribution, manual award, purchase, tip)\n- category: financial\n  text: Ethereum-compatible wallet address that you voluntarily bind via the /bind-wallet slash command.\npurposes:\n- purpose: Operate community features\n  text: We use the information above solely to operate the Bot's stated features\n- purpose: Advertising\n  text: We do not use your information for advertising.\n- purpose: AI model training\n  text: We do not use your information to train AI models.\nretention:\n- scope: Bot data\n  period: null\n  text: We retain the information described in Section 2 for as long as you remain a member of the Ava Protocol\n    Discord server and the community rewards program continues to operate, or until you request deletion under Section\n    7.\n- scope: On-chain records\n  period: null\n  text: On-chain transaction records on the Base blockchain are public and permanent and cannot be deleted by us.\nresidency:\n-\
  \ region: United States\n  text: 'Primary database: PostgreSQL, hosted on Railway (United States region).'\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@avaprotocol.org requesting deletion of account record\n  text: Delete your account record from our database\nrights:\n- right: Access\n  text: Provide a copy of the information we hold about you\n- right: Correction\n  text: Correct inaccurate information\n- right: Deletion\n  text: Delete your account record from our database\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your information.\n"
source_yaml_url: https://artifacts.apis.io/ava-protocol/privacy/ava-protocol-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Ava Protocol's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Blockchain
- DeFi
- Automation
- Web3
- Ethereum
- Smart Wallets
- Workflows
- AI Agents
---
