---
api_specs:
- filename: arbitron-app-account-api-openapi.yml
  format: yaml
  label: Arbitron Account API
  slug: arbitron-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arbitron-app/openapi/arbitron-app-account-api-openapi.yml
- filename: arbitron-app-funding-api-openapi.yml
  format: yaml
  label: Arbitron Funding API
  slug: arbitron-app-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arbitron-app/openapi/arbitron-app-funding-api-openapi.yml
- filename: arbitron-app-platform-api-openapi.yml
  format: yaml
  label: Arbitron Platform API
  slug: arbitron-app-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arbitron-app/openapi/arbitron-app-platform-api-openapi.yml
- filename: arbitron-app-reference-data-api-openapi.yml
  format: yaml
  label: Arbitron Reference data API
  slug: arbitron-app-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arbitron-app/openapi/arbitron-app-reference-data-api-openapi.yml
- filename: arbitron-app-spreads-api-openapi.yml
  format: yaml
  label: Arbitron Spreads API
  slug: arbitron-app-spreads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arbitron-app/openapi/arbitron-app-spreads-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account credentials — username and password hash (we never store plaintext passwords).
  - category: contact
    text: Telegram chat ID (only if you choose to link Telegram for notifications) and the Telegram username you used at link time.
  - category: financial
    text: Exchange API keys and secrets you provide. These are encrypted at rest with AES-256 and used only to place trades on your behalf.
  - category: financial
    text: 'Trading data generated while using the service: orders, fills, position state, profit/loss, and configured strategy parameters.'
  - category: device
    text: Standard technical logs (IP address, browser user agent, timestamps) used for security monitoring and debugging.
  deletion:
    route: Email support@arbitron.app
    text: Right to deletion — request that we delete your account and associated personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate arbitrage service
    text: To operate the arbitrage service — connect to exchanges via your API keys, execute hedged trades, and report PnL to you.
  - purpose: Fees and subscription
    text: To compute and charge our server subscription and performance fees per our Terms.
  - purpose: Support
    text: To answer your support requests when you contact us.
  - purpose: Security
    text: To detect and prevent abuse, fraud, and security incidents.
  residency:
  - region: Singapore (ap-southeast-1)
    text: Servers are hosted on AWS in the ap-southeast-1 (Singapore) region with private VPC routing for all internal traffic.
  retention:
  - period: null
    scope: Account data
    text: We keep your account data while your account is active.
  - period: 30 days
    scope: Account data after deletion
    text: After account deletion, personal data is removed within 30 days.
  - period: null
    scope: Encrypted API keys
    text: Encrypted API keys are deleted immediately when you remove them from your profile or close your account.
  rights:
  - right: Access
    text: Right to access — request a copy of the personal data we hold about you.
  - right: Deletion
    text: Right to deletion — request that we delete your account and associated personal data.
  - right: Portability
    text: Right to portability — export your trading history in a machine-readable format.
  - right: Correction
    text: Right to correction — update inaccurate personal data.
  role:
    text: The data controller is Arbitron, a UAE-registered entity.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your personal data with third parties for marketing.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Arbitron
provenance_date: '2026-11-09'
provider_name: Arbitron
provider_slug: arbitron-app
slug: arbitron-app-privacy-policy
source_date: '2026-11-09'
source_filename: arbitron-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://arbitron.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Arbitron\naid: arbitron-app\nurl: https://arbitron.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Arbitron, a UAE-registered entity.\ndata_categories:\n- category: identifying\n  text: Account credentials — username and password hash (we never store plaintext passwords).\n- category: contact\n  text: Telegram chat ID (only if you choose to link Telegram for notifications) and the Telegram username you used\n    at link time.\n- category: financial\n  text: Exchange API keys and secrets you provide. These are encrypted at rest with AES-256 and used only to\
  \ place\n    trades on your behalf.\n- category: financial\n  text: 'Trading data generated while using the service: orders, fills, position state, profit/loss, and configured\n    strategy parameters.'\n- category: device\n  text: Standard technical logs (IP address, browser user agent, timestamps) used for security monitoring and debugging.\npurposes:\n- purpose: Operate arbitrage service\n  text: To operate the arbitrage service — connect to exchanges via your API keys, execute hedged trades, and report\n    PnL to you.\n- purpose: Fees and subscription\n  text: To compute and charge our server subscription and performance fees per our Terms.\n- purpose: Support\n  text: To answer your support requests when you contact us.\n- purpose: Security\n  text: To detect and prevent abuse, fraud, and security incidents.\nretention:\n- scope: Account data\n  period: null\n  text: We keep your account data while your account is active.\n- scope: Account data after deletion\n  period: 30 days\n\
  \  text: After account deletion, personal data is removed within 30 days.\n- scope: Encrypted API keys\n  period: null\n  text: Encrypted API keys are deleted immediately when you remove them from your profile or close your account.\nresidency:\n- region: Singapore (ap-southeast-1)\n  text: Servers are hosted on AWS in the ap-southeast-1 (Singapore) region with private VPC routing for all internal\n    traffic.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@arbitron.app\n  text: Right to deletion — request that we delete your account and associated personal data.\nrights:\n- right: Access\n  text: Right to access — request a copy of the personal data we hold about you.\n- right: Deletion\n  text: Right to deletion — request that we delete your account and associated personal data.\n- right: Portability\n  text: Right to portability — export your trading history in a machine-readable format.\n\
  - right: Correction\n  text: Right to correction — update inaccurate personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your personal data with third parties for marketing.\n"
source_yaml_url: https://artifacts.apis.io/arbitron-app/privacy/arbitron-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Arbitron's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Arbitrage
- Finance
- Platform
---
