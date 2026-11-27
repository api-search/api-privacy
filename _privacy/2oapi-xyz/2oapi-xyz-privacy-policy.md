---
api_specs:
- filename: 2oapi-xyz-openapi-generated.yml
  format: yaml
  label: 2O API
  slug: 2oapi-xyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/2oapi-xyz/openapi/_ae-authored/2oapi-xyz-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect the agent name, description, API key (stored only as a cryptographic hash), deposit wallet address, transaction history, and the content of verification requests submitted through the API.
  - category: contact
    text: We collect your email address, display name, biographical information, selected domains of expertise, wallet address (if provided)
  - category: financial
    text: Stripe account identifier (if connected for bank payouts), verification response history, and reputation score and history.
  - category: device
    text: We collect IP addresses, request timestamps, and browser or user agent information for security monitoring and abuse prevention purposes.
  - category: behavioral
    text: We use activity data to prevent fraud and abuse.
  deletion:
    route: contact the provider
    text: You may request deletion of your account and all associated personal data by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate marketplace and process payments
    text: We use your data to operate the verification marketplace, including matching verification requests to qualified Verifiers and processing payments.
  - purpose: reputation scoring
    text: We use verification data to calculate reputation scores and consensus results that improve the quality of the Platform.
  - purpose: fraud and abuse prevention
    text: We use activity data to prevent fraud and abuse.
  - purpose: account communication
    text: We may use your email address to communicate with you about your account.
  retention:
  - period: null
    scope: account data
    text: Account data is retained for the duration that your account remains active on the Platform.
  - period: null
    scope: verification data
    text: Verification data, including requests and responses, is retained for quality assurance, reputation scoring, and dispute resolution purposes.
  rights:
  - right: access
    text: You have the right to access the personal data we hold about you
  - right: correction
    text: to correct any inaccurate information
  - right: deletion
    text: to request deletion of your account and associated data
  - right: portability
    text: to export your data in a portable format
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 2O
provenance_date: '2026-11-09'
provider_name: 2O
provider_slug: 2oapi-xyz
slug: 2oapi-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: 2oapi-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.2oapi.xyz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 2O\naid: 2oapi-xyz\nurl: https://www.2oapi.xyz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect the agent name, description, API key (stored only as a cryptographic hash), deposit wallet address,\n    transaction history, and the content of verification requests submitted through the API.\n- category: contact\n  text: We collect your email address, display name, biographical information, selected domains of expertise, wallet\n    address (if provided)\n- category: financial\n  text: Stripe account identifier (if connected\
  \ for bank payouts), verification response history, and reputation\n    score and history.\n- category: device\n  text: We collect IP addresses, request timestamps, and browser or user agent information for security monitoring\n    and abuse prevention purposes.\n- category: behavioral\n  text: We use activity data to prevent fraud and abuse.\npurposes:\n- purpose: operate marketplace and process payments\n  text: We use your data to operate the verification marketplace, including matching verification requests to qualified\n    Verifiers and processing payments.\n- purpose: reputation scoring\n  text: We use verification data to calculate reputation scores and consensus results that improve the quality of\n    the Platform.\n- purpose: fraud and abuse prevention\n  text: We use activity data to prevent fraud and abuse.\n- purpose: account communication\n  text: We may use your email address to communicate with you about your account.\nretention:\n- scope: account data\n  period: null\n\
  \  text: Account data is retained for the duration that your account remains active on the Platform.\n- scope: verification data\n  period: null\n  text: Verification data, including requests and responses, is retained for quality assurance, reputation scoring,\n    and dispute resolution purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the provider\n  text: You may request deletion of your account and all associated personal data by contacting us.\nrights:\n- right: access\n  text: You have the right to access the personal data we hold about you\n- right: correction\n  text: to correct any inaccurate information\n- right: deletion\n  text: to request deletion of your account and associated data\n- right: portability\n  text: to export your data in a portable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/2oapi-xyz/privacy/2oapi-xyz-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from 2O's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Verification
- Human-in-the-Loop
- Trust
- Agents
---
