---
api_specs:
- filename: cex-io-accounts-api-openapi.yml
  format: yaml
  label: CEX.IO Accounts API
  slug: cex-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-accounts-api-openapi.yml
- filename: cex-io-fees-api-openapi.yml
  format: yaml
  label: CEX.IO Fees API
  slug: cex-io-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-fees-api-openapi.yml
- filename: cex-io-funding-api-openapi.yml
  format: yaml
  label: CEX.IO Funding API
  slug: cex-io-funding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-funding-api-openapi.yml
- filename: cex-io-history-api-openapi.yml
  format: yaml
  label: CEX.IO History API
  slug: cex-io-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-history-api-openapi.yml
- filename: cex-io-market-data-api-openapi.yml
  format: yaml
  label: CEX.IO Market Data API
  slug: cex-io-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-market-data-api-openapi.yml
- filename: cex-io-orders-api-openapi.yml
  format: yaml
  label: CEX.IO Orders API
  slug: cex-io-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-orders-api-openapi.yml
- filename: cex-io-private-api-openapi.yml
  format: yaml
  label: CEX.IO Private API
  slug: cex-io-private-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-private-api-openapi.yml
- filename: cex-io-public-api-openapi.yml
  format: yaml
  label: CEX.IO Public API
  slug: cex-io-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-public-api-openapi.yml
- filename: cex-io-public-market-data-api-openapi.yml
  format: yaml
  label: CEX.IO Public Market Data API
  slug: cex-io-public-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cex-io/openapi/cex-io-public-market-data-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: username, name, corporate legal name (including d/b/a name), date of birth, contact information, address(es), phone number
  - category: identifying
    text: government-issued identification documents (e.g. drivers license, passport, social security number, employer identification number, and taxpayer identification number)
  - category: biometric
    text: biometric identifiers (facial recognition and facial geometry data derived from photographs or videos you submit to us during the onboarding process)
  - category: financial
    text: Certain services require financial information such as your credit/debit card information, digital asset wallet addresses, information about your income/source of funds, tax information.
  - category: location
    text: We collect your IP address automatically when you use our Services, from which we or third parties operating on our behalf may be able to determine your approximate location (e.g. country and city).
  - category: device
    text: We collect your device information, such as browser type and operating system, to analyze trends, administer the website and gather demographic information.
  - category: communication
    text: When you contact us, we collect information concerning the contents of your communications, whether by email, chat, social media, telephone or otherwise.
  - category: behavioral
    text: We may collect information about the pages you visit on our website, and other actions you take while navigating through our website.
  deletion:
    route: Contact Support Team or dpo@cex.io
    text: Users can access, correct, or request the deletion of their face data by contacting our Support Team.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain services
    text: To provide and maintain our services , including to allow you to open and operate an account and monitor the usage of services
  - purpose: Legal and regulatory obligations
    text: To comply with legal obligation purposes such as tax reporting, fraud prevention, our reporting obligations etc.
  - purpose: Marketing
    text: 'Marketing : To provide you with news, special offers and general information about other goods, services, and events which we offer that are similar to those that you have already purchased or enquired about unless you have opted not to receive such information'
  - purpose: Face data for identity verification
    text: At CEX.IO, we use face data as part of our liveness check during the user verification process.
  - purpose: Advertising and analytics
    text: we may share hashed data, including personal data such as email addresses and phone numbers, with third-party entities for data analytics, profiling, and user acquisition purposes
  retention:
  - period: null
    scope: Personal Information generally
    text: CEX.IO will retain your Personal Information for as long as is necessary to complete the purposes for which it was collected, or as may be required by law.
  - period: five to eight years
    scope: Face data
    text: We retain face data for a period of five to eight years, depending on local regulatory body requirements.
  rights:
  - right: Access
    text: You have the right to access the Personal Information we collect about you
  - right: Correct
    text: the right to correct any inaccuracies in your Personal Information
  - right: Delete
    text: Right to delete. You have the right to request the deletion of your Personal Information.
  - right: Opt-out of sale or sharing
    text: Right to opt-out of the Sale of Personal Information. We do not sell the Personal Information of consumers.
  - right: Limit sensitive personal information
    text: Right to limit. You have the right to request us to only use your sensitive personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell the Personal Information of consumers. However, if we begin to sell personal information in the future, you have the right to direct us to not sell your Personal Information at any time.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 'Third Party Service Providers : We may share Personal Information with third-party service providers (including those that may be located outside of the United States or your country)'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CEX.IO
provenance_date: '2026-11-09'
provider_name: CEX.IO
provider_slug: cex-io
slug: cex-io-privacy-policy
source_date: '2026-11-09'
source_filename: cex-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cex.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CEX.IO\naid: cex-io\nurl: https://cex.io/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: username, name, corporate legal name (including d/b/a name), date of birth, contact information, address(es),\n    phone number\n- category: identifying\n  text: government-issued identification documents (e.g. drivers license, passport, social security number, employer\n    identification number, and taxpayer identification number)\n- category: biometric\n  text: biometric identifiers (facial recognition and facial\
  \ geometry data derived from photographs or videos you\n    submit to us during the onboarding process)\n- category: financial\n  text: Certain services require financial information such as your credit/debit card information, digital asset\n    wallet addresses, information about your income/source of funds, tax information.\n- category: location\n  text: We collect your IP address automatically when you use our Services, from which we or third parties operating\n    on our behalf may be able to determine your approximate location (e.g. country and city).\n- category: device\n  text: We collect your device information, such as browser type and operating system, to analyze trends, administer\n    the website and gather demographic information.\n- category: communication\n  text: When you contact us, we collect information concerning the contents of your communications, whether by email,\n    chat, social media, telephone or otherwise.\n- category: behavioral\n  text: We may collect information\
  \ about the pages you visit on our website, and other actions you take while navigating\n    through our website.\npurposes:\n- purpose: Provide and maintain services\n  text: To provide and maintain our services , including to allow you to open and operate an account and monitor\n    the usage of services\n- purpose: Legal and regulatory obligations\n  text: To comply with legal obligation purposes such as tax reporting, fraud prevention, our reporting obligations\n    etc.\n- purpose: Marketing\n  text: 'Marketing : To provide you with news, special offers and general information about other goods, services,\n    and events which we offer that are similar to those that you have already purchased or enquired about unless\n    you have opted not to receive such information'\n- purpose: Face data for identity verification\n  text: At CEX.IO, we use face data as part of our liveness check during the user verification process.\n- purpose: Advertising and analytics\n  text: we may share hashed\
  \ data, including personal data such as email addresses and phone numbers, with third-party\n    entities for data analytics, profiling, and user acquisition purposes\nretention:\n- scope: Personal Information generally\n  period: null\n  text: CEX.IO will retain your Personal Information for as long as is necessary to complete the purposes for which\n    it was collected, or as may be required by law.\n- scope: Face data\n  period: five to eight years\n  text: We retain face data for a period of five to eight years, depending on local regulatory body requirements.\nresidency: []\ntransfers:\n- mechanism: other\n  text: 'Third Party Service Providers : We may share Personal Information with third-party service providers (including\n    those that may be located outside of the United States or your country)'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Support Team or dpo@cex.io\n  text: Users can access, correct,\
  \ or request the deletion of their face data by contacting our Support Team.\nrights:\n- right: Access\n  text: You have the right to access the Personal Information we collect about you\n- right: Correct\n  text: the right to correct any inaccuracies in your Personal Information\n- right: Delete\n  text: Right to delete. You have the right to request the deletion of your Personal Information.\n- right: Opt-out of sale or sharing\n  text: Right to opt-out of the Sale of Personal Information. We do not sell the Personal Information of consumers.\n- right: Limit sensitive personal information\n  text: Right to limit. You have the right to request us to only use your sensitive personal information\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell the Personal Information of consumers. However, if we begin to sell personal information\n    in the future, you have the right to direct us to not sell your Personal Information at any time.\n"
source_yaml_url: https://artifacts.apis.io/cex-io/privacy/cex-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from CEX.IO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Market Data
- WebSocket
- Financial Services
---
