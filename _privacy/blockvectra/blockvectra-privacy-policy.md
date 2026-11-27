---
api_specs:
- filename: blockvectra-account-api-openapi.yml
  format: yaml
  label: BlockVectra Account API
  slug: blockvectra-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-account-api-openapi.yml
- filename: blockvectra-addresses-api-openapi.yml
  format: yaml
  label: BlockVectra Addresses API
  slug: blockvectra-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-addresses-api-openapi.yml
- filename: blockvectra-auth-api-openapi.yml
  format: yaml
  label: BlockVectra Auth API
  slug: blockvectra-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-auth-api-openapi.yml
- filename: blockvectra-billing-api-openapi.yml
  format: yaml
  label: BlockVectra Billing API
  slug: blockvectra-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-billing-api-openapi.yml
- filename: blockvectra-chain-api-openapi.yml
  format: yaml
  label: BlockVectra Chain API
  slug: blockvectra-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-chain-api-openapi.yml
- filename: blockvectra-chains-api-openapi.yml
  format: yaml
  label: BlockVectra Chains API
  slug: blockvectra-chains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-chains-api-openapi.yml
- filename: blockvectra-dex-api-openapi.yml
  format: yaml
  label: BlockVectra DEX API
  slug: blockvectra-dex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-dex-api-openapi.yml
- filename: blockvectra-faucet-api-openapi.yml
  format: yaml
  label: BlockVectra Faucet API
  slug: blockvectra-faucet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-faucet-api-openapi.yml
- filename: blockvectra-json-rpc-api-openapi.yml
  format: yaml
  label: BlockVectra JSON RPC API
  slug: blockvectra-json-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-json-rpc-api-openapi.yml
- filename: blockvectra-keys-api-openapi.yml
  format: yaml
  label: BlockVectra Keys API
  slug: blockvectra-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-keys-api-openapi.yml
- filename: blockvectra-me-api-openapi.yml
  format: yaml
  label: BlockVectra Me API
  slug: blockvectra-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-me-api-openapi.yml
- filename: blockvectra-nfts-api-openapi.yml
  format: yaml
  label: BlockVectra NFTs API
  slug: blockvectra-nfts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-nfts-api-openapi.yml
- filename: blockvectra-status-api-openapi.yml
  format: yaml
  label: BlockVectra Status API
  slug: blockvectra-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-status-api-openapi.yml
- filename: blockvectra-stocks-api-openapi.yml
  format: yaml
  label: BlockVectra Stocks API
  slug: blockvectra-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-stocks-api-openapi.yml
- filename: blockvectra-subscriptions-api-openapi.yml
  format: yaml
  label: BlockVectra Subscriptions API
  slug: blockvectra-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-subscriptions-api-openapi.yml
- filename: blockvectra-tokens-api-openapi.yml
  format: yaml
  label: BlockVectra Tokens API
  slug: blockvectra-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-tokens-api-openapi.yml
- filename: blockvectra-traces-api-openapi.yml
  format: yaml
  label: BlockVectra Traces API
  slug: blockvectra-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-traces-api-openapi.yml
- filename: blockvectra-top-up-api-openapi.yml
  format: yaml
  label: BlockVectra Top Up API
  slug: blockvectra-top-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockvectra/openapi/blockvectra-top-up-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your wallet address
  - category: identifying
    text: we store the numeric ID and username of your GitHub account
  - category: identifying
    text: we store the unique identifier (subject ID) of your Google account
  - category: contact
    text: the email address, email content, and attachments you provide when you contact us
  - category: device
    text: the browser stores WalletConnect connection data in local storage
  - category: behavioral
    text: we record the type of action, the time and your IP address, for security auditing
  - category: financial
    text: Charge records, top-up records (amount, currency, time and type) and your Credits balance.
  - category: financial
    text: on-chain transfer records (payment address, transaction hash, amount, network, and time, which are publicly visible on the blockchain by their nature)
  deletion:
    route: Write to the contact email
    text: The Service currently has no self-service deletion or export
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and operating the Service
    text: Creating Accounts and signing you in, issuing and managing API keys, routing requests and enforcing limits, metering, billing and settlement, and showing usage and balance.
  - purpose: Handling top-ups and billing disputes
    text: Checking payments, handling metering disputes, dealing with payments that are reversed or charged back
  - purpose: Security, abuse prevention and enforcing the Terms
    text: Security auditing, rate limiting and limits on account opening, detecting and dealing with leaked API keys
  - purpose: Legal compliance
    text: Verifying identity and source of funds where necessary, keeping accounting and tax records
  - purpose: Communications and notices
    text: Replying to your emails and sending you service-related notices.
  - purpose: Operations and improvement
    text: Troubleshooting, capacity planning and improving the Service.
  retention:
  - period: null
    scope: Logs and audit records
    text: 'Logs and audit records: kept as needed; information processed by Cloudflare is kept under its own policy.'
  - period: null
    scope: Account closure
    text: Closing an Account does not mean all data is deleted immediately
  rights:
  - right: access
    text: to access your personal information, obtain a copy and learn how we process it
  - right: correction
    text: to have inaccurate or incomplete personal information corrected
  - right: deletion
    text: to ask for your personal information to be deleted
  - right: restriction or objection
    text: to ask us to restrict processing, or to object to processing that we carry out on the basis of our legitimate interests
  - right: portability
    text: to receive the personal information you provided to us in a commonly used, structured and machine-readable format
  - right: withdraw consent
    text: to withdraw your consent
  - right: complaint
    text: to lodge a complaint with the data protection authority where you live
  role:
    text: the controller of the personal information described in this Policy
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Infrastructure providers. Providers of hosting, storage and backup, and Cloudflare, which provides network acceleration (CDN) and security protection; they process information for us.
    url: null
  transfers:
  - mechanism: other
    text: We and the providers above may process your personal information outside the country or region where you live
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BlockVectra
provenance_date: '2026-11-09'
provider_name: BlockVectra
provider_slug: blockvectra
slug: blockvectra-privacy-policy
source_date: '2026-11-09'
source_filename: blockvectra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blockvectra.com/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BlockVectra\naid: blockvectra\nurl: https://blockvectra.com/en/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the controller of the personal information described in this Policy\ndata_categories:\n- category: identifying\n  text: we store your wallet address\n- category: identifying\n  text: we store the numeric ID and username of your GitHub account\n- category: identifying\n  text: we store the unique identifier (subject ID) of your Google account\n- category: contact\n  text: the email address, email content, and attachments you provide when you contact us\n- category: device\n\
  \  text: the browser stores WalletConnect connection data in local storage\n- category: behavioral\n  text: we record the type of action, the time and your IP address, for security auditing\n- category: financial\n  text: Charge records, top-up records (amount, currency, time and type) and your Credits balance.\n- category: financial\n  text: on-chain transfer records (payment address, transaction hash, amount, network, and time, which are publicly\n    visible on the blockchain by their nature)\npurposes:\n- purpose: Providing and operating the Service\n  text: Creating Accounts and signing you in, issuing and managing API keys, routing requests and enforcing limits,\n    metering, billing and settlement, and showing usage and balance.\n- purpose: Handling top-ups and billing disputes\n  text: Checking payments, handling metering disputes, dealing with payments that are reversed or charged back\n- purpose: Security, abuse prevention and enforcing the Terms\n  text: Security auditing,\
  \ rate limiting and limits on account opening, detecting and dealing with leaked API keys\n- purpose: Legal compliance\n  text: Verifying identity and source of funds where necessary, keeping accounting and tax records\n- purpose: Communications and notices\n  text: Replying to your emails and sending you service-related notices.\n- purpose: Operations and improvement\n  text: Troubleshooting, capacity planning and improving the Service.\nretention:\n- scope: Logs and audit records\n  period: null\n  text: 'Logs and audit records: kept as needed; information processed by Cloudflare is kept under its own policy.'\n- scope: Account closure\n  period: null\n  text: Closing an Account does not mean all data is deleted immediately\nresidency: []\ntransfers:\n- mechanism: other\n  text: We and the providers above may process your personal information outside the country or region where you\n    live\nsubprocessors:\n  url: null\n  text: Infrastructure providers. Providers of hosting, storage\
  \ and backup, and Cloudflare, which provides network\n    acceleration (CDN) and security protection; they process information for us.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to the contact email\n  text: The Service currently has no self-service deletion or export\nrights:\n- right: access\n  text: to access your personal information, obtain a copy and learn how we process it\n- right: correction\n  text: to have inaccurate or incomplete personal information corrected\n- right: deletion\n  text: to ask for your personal information to be deleted\n- right: restriction or objection\n  text: to ask us to restrict processing, or to object to processing that we carry out on the basis of our legitimate\n    interests\n- right: portability\n  text: to receive the personal information you provided to us in a commonly used, structured and machine-readable\n    format\n- right: withdraw consent\n  text: to withdraw your consent\n- right: complaint\n  text:\
  \ to lodge a complaint with the data protection authority where you live\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blockvectra/privacy/blockvectra-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 27 quoted statements, read from BlockVectra's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Data API
- Multi-Chain
- Cryptocurrency
- Developer Platform
---
