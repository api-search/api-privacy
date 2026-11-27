---
api_specs:
- filename: chainflip-broker-io-assets-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Assets API
  slug: chainflip-broker-io-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-assets-api-openapi.yml
- filename: chainflip-broker-io-fees-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Fees API
  slug: chainflip-broker-io-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-fees-api-openapi.yml
- filename: chainflip-broker-io-networks-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Networks API
  slug: chainflip-broker-io-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-networks-api-openapi.yml
- filename: chainflip-broker-io-onboarding-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Onboarding API
  slug: chainflip-broker-io-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-onboarding-api-openapi.yml
- filename: chainflip-broker-io-quote-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Quote API
  slug: chainflip-broker-io-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-quote-api-openapi.yml
- filename: chainflip-broker-io-rpc-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Rpc API
  slug: chainflip-broker-io-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-rpc-api-openapi.yml
- filename: chainflip-broker-io-status-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Status API
  slug: chainflip-broker-io-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-status-api-openapi.yml
- filename: chainflip-broker-io-swap-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Swap API
  slug: chainflip-broker-io-swap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-swap-api-openapi.yml
- filename: chainflip-broker-io-swaps-api-openapi.yml
  format: yaml
  label: Chainflip Broker as a Service Swaps API
  slug: chainflip-broker-io-swaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainflip-broker-io/openapi/chainflip-broker-io-swaps-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address, if you give one
  - category: identifying
    text: the API key and admin key we issue to you
  - category: financial
    text: your commission and the Ethereum address your commissions are paid to
  - category: location
    text: the IP address of the request that opened it
  - category: device
    text: browser user agent and full URL, including the query string
  - category: behavioral
    text: recorded channel and swap-completion activity
  deletion:
    route: email request to info@chainflip-broker.io
    text: To ask what we hold about you, or to have it corrected or deleted, write to info@chainflip-broker.io from the email address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account emails
    text: We use your email address to send account emails
  - purpose: abuse investigation and debugging
    text: We use it to investigate problems you report and to spot abuse.
  - purpose: acquisition analysis
    text: We save acquisition information with your partner account to understand which sources lead to registrations and swap activation.
  retention:
  - period: 15 days
    scope: request log
    text: This log is kept for 15 days and then deleted.
  - period: 15 days
    scope: swap IP address
    text: Like the request log below, it is deleted after 15 days; the swap record itself stays.
  - period: null
    scope: partner acquisition information
    text: We retain this acquisition and activation information with the partner account until account-data correction or deletion through the contact process below; it has no automatic analytics expiry.
  - period: years
    scope: daily usage totals
    text: We keep the daily totals for years.
  - period: null
    scope: Umami history
    text: 'History has no automatic expiry: it is retained indefinitely until an operator deletes or resets it'
  rights:
  - right: access
    text: To ask what we hold about you
  - right: correction
    text: or to have it corrected or deleted
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chainflip Broker as a Service
provenance_date: '2026-11-09'
provider_name: Chainflip Broker as a Service
provider_slug: chainflip-broker-io
slug: chainflip-broker-io-privacy-policy
source_date: '2026-11-09'
source_filename: chainflip-broker-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.chainflip-broker.io/resources/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chainflip Broker as a Service\naid: chainflip-broker-io\nurl: https://docs.chainflip-broker.io/resources/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email address, if you give one\n- category: identifying\n  text: the API key and admin key we issue to you\n- category: financial\n  text: your commission and the Ethereum address your commissions are paid to\n- category: location\n  text: the IP address of the request that opened it\n- category: device\n  text: browser user agent and full URL, including the query string\n- category:\
  \ behavioral\n  text: recorded channel and swap-completion activity\npurposes:\n- purpose: account emails\n  text: We use your email address to send account emails\n- purpose: abuse investigation and debugging\n  text: We use it to investigate problems you report and to spot abuse.\n- purpose: acquisition analysis\n  text: We save acquisition information with your partner account to understand which sources lead to registrations\n    and swap activation.\nretention:\n- scope: request log\n  period: 15 days\n  text: This log is kept for 15 days and then deleted.\n- scope: swap IP address\n  period: 15 days\n  text: Like the request log below, it is deleted after 15 days; the swap record itself stays.\n- scope: partner acquisition information\n  period: null\n  text: We retain this acquisition and activation information with the partner account until account-data correction\n    or deletion through the contact process below; it has no automatic analytics expiry.\n- scope: daily usage totals\n\
  \  period: years\n  text: We keep the daily totals for years.\n- scope: Umami history\n  period: null\n  text: 'History has no automatic expiry: it is retained indefinitely until an operator deletes or resets it'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to info@chainflip-broker.io\n  text: To ask what we hold about you, or to have it corrected or deleted, write to info@chainflip-broker.io from\n    the email address on your account.\nrights:\n- right: access\n  text: To ask what we hold about you\n- right: correction\n  text: or to have it corrected or deleted\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chainflip-broker-io/privacy/chainflip-broker-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from Chainflip Broker as a Service's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- DeFi
- Cryptocurrency
- Brokerage
- Infrastructure
- Company
---
