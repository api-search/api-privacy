---
api_specs:
- filename: bolt-financial-account-api-openapi.yml
  format: yaml
  label: Bolt Financial Account API
  slug: bolt-financial-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-account-api-openapi.yml
- filename: bolt-financial-callbacks-api-openapi.yml
  format: yaml
  label: Bolt Financial Callbacks API
  slug: bolt-financial-callbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-callbacks-api-openapi.yml
- filename: bolt-financial-configuration-api-openapi.yml
  format: yaml
  label: Bolt Financial Configuration API
  slug: bolt-financial-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-configuration-api-openapi.yml
- filename: bolt-financial-orders-api-openapi.yml
  format: yaml
  label: Bolt Financial Orders API
  slug: bolt-financial-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-orders-api-openapi.yml
- filename: bolt-financial-payments-api-openapi.yml
  format: yaml
  label: Bolt Financial Payments API
  slug: bolt-financial-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-payments-api-openapi.yml
- filename: bolt-financial-statements-api-openapi.yml
  format: yaml
  label: Bolt Financial Statements API
  slug: bolt-financial-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-statements-api-openapi.yml
- filename: bolt-financial-subscriptions-api-openapi.yml
  format: yaml
  label: Bolt Financial Subscriptions API
  slug: bolt-financial-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-subscriptions-api-openapi.yml
- filename: bolt-financial-testing-api-openapi.yml
  format: yaml
  label: Bolt Financial Testing API
  slug: bolt-financial-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-testing-api-openapi.yml
- filename: bolt-financial-tokenizer-api-openapi.yml
  format: yaml
  label: Bolt Financial Tokenizer API
  slug: bolt-financial-tokenizer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-tokenizer-api-openapi.yml
- filename: bolt-financial-transactions-api-openapi.yml
  format: yaml
  label: Bolt Financial Transactions API
  slug: bolt-financial-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-transactions-api-openapi.yml
- filename: bolt-financial-webhooks-api-openapi.yml
  format: yaml
  label: Bolt Financial Webhooks API
  slug: bolt-financial-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-webhooks-api-openapi.yml
- filename: bolt-financial-oauth-api-openapi.yml
  format: yaml
  label: Bolt Financial O Auth API
  slug: bolt-financial-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bolt-financial/openapi/bolt-financial-oauth-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: account information (such as your name, phone number, email address, login credentials, and linked payment methods)
  - category: identifying
    text: verification information (such as government-issued identification, date of birth, and Social Security Number or ITIN)
  - category: device
    text: device identifiers (IMEI, MAC address), advertising identifiers (IDFA/GAID), operating system version, carrier, and crash diagnostics
  - category: location
    text: If you enable location services, we may collect precise geolocation data.
  - category: behavioral
    text: information about your interactions with the App, including session duration, features used, screens visited, and push notification tokens
  - category: financial
    text: when you initiate a transfer through the App, Bolt processes your financial account information
  - category: communication
    text: We also collect communications data when you contact customer support by chat, email, or phone.
  deletion:
    route: null
    text: Once retention periods expire, Bolt securely deletes or anonymizes the data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the services
    text: Bolt uses your Personal Information to facilitate transactions, process payments, manage wallets, determine eligibility for certain features or services, and link accounts.
  - purpose: Verify identity and prevent fraud
    text: to verify your identity, conduct “Know Your Customer” checks, screen against OFAC and other sanctions lists, and detect fraudulent or suspicious activity.
  - purpose: Marketing
    text: we may use your Personal Information to notify you of promotions, personalize in-App offers, engage in targeted advertising, and measure interest in Bolt’s products.
  - purpose: Compliance and legal obligations
    text: Bolt processes your Personal Information to comply with BSA/AML, OFAC, FinCEN, CFPB, and state Money Transmitter License requirements.
  - purpose: Improvement and analytics
    text: We use information to improve the App, conduct analytics, develop new financial products, and generate de-identified or aggregated information that we will not re-identify.
  retention:
  - period: 5–7 years
    scope: Financial records
    text: Financial records are generally maintained for 5–7 years as required under BSA/AML and state MTL laws.
  - period: 12–24 months
    scope: Diagnostic and device data
    text: Diagnostic and device data collected through the App is typically retained for 12–24 months.
  - period: 3 years
    scope: Third-party biometric verification data
    text: Unless required by law, the provider will retain your biometric data for no more than 3 years.
  rights:
  - right: access, correct, delete
    text: access, correct, or delete that information
  - right: portability
    text: request portability
  - right: object to processing
    text: object to processing
  - right: withdraw consent
    text: or withdraw consent
  role:
    text: this Website Privacy Policy applies only to Personal Information that is Processed by Bolt in our capacity as a “business” or similar term under applicable data protection laws
    value: controller
  sale_or_sharing:
    stance: unstated
    text: Bolt does not sell Personal Information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where Bolt transfers data outside the EEA, Switzerland, and UK, we rely on Standard Contractual Clauses, adequacy decisions, or equivalent safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bolt Financial
provenance_date: '2026-11-09'
provider_name: Bolt Financial
provider_slug: bolt-financial
slug: bolt-financial-privacy-policy
source_date: '2026-11-09'
source_filename: bolt-financial-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.boltapp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bolt Financial\naid: bolt-financial\nurl: https://www.boltapp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: this Website Privacy Policy applies only to Personal Information that is Processed by Bolt in our capacity\n    as a “business” or similar term under applicable data protection laws\ndata_categories:\n- category: identifying\n  text: account information (such as your name, phone number, email address, login credentials, and linked payment\n    methods)\n- category: identifying\n  text: verification information (such as government-issued identification, date of birth, and\
  \ Social Security Number\n    or ITIN)\n- category: device\n  text: device identifiers (IMEI, MAC address), advertising identifiers (IDFA/GAID), operating system version, carrier,\n    and crash diagnostics\n- category: location\n  text: If you enable location services, we may collect precise geolocation data.\n- category: behavioral\n  text: information about your interactions with the App, including session duration, features used, screens visited,\n    and push notification tokens\n- category: financial\n  text: when you initiate a transfer through the App, Bolt processes your financial account information\n- category: communication\n  text: We also collect communications data when you contact customer support by chat, email, or phone.\npurposes:\n- purpose: Provide the services\n  text: Bolt uses your Personal Information to facilitate transactions, process payments, manage wallets, determine\n    eligibility for certain features or services, and link accounts.\n- purpose: Verify identity\
  \ and prevent fraud\n  text: to verify your identity, conduct “Know Your Customer” checks, screen against OFAC and other sanctions lists,\n    and detect fraudulent or suspicious activity.\n- purpose: Marketing\n  text: we may use your Personal Information to notify you of promotions, personalize in-App offers, engage in targeted\n    advertising, and measure interest in Bolt’s products.\n- purpose: Compliance and legal obligations\n  text: Bolt processes your Personal Information to comply with BSA/AML, OFAC, FinCEN, CFPB, and state Money Transmitter\n    License requirements.\n- purpose: Improvement and analytics\n  text: We use information to improve the App, conduct analytics, develop new financial products, and generate de-identified\n    or aggregated information that we will not re-identify.\nretention:\n- scope: Financial records\n  period: 5–7 years\n  text: Financial records are generally maintained for 5–7 years as required under BSA/AML and state MTL laws.\n- scope: Diagnostic\
  \ and device data\n  period: 12–24 months\n  text: Diagnostic and device data collected through the App is typically retained for 12–24 months.\n- scope: Third-party biometric verification data\n  period: 3 years\n  text: Unless required by law, the provider will retain your biometric data for no more than 3 years.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where Bolt transfers data outside the EEA, Switzerland, and UK, we rely on Standard Contractual Clauses,\n    adequacy decisions, or equivalent safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Once retention periods expire, Bolt securely deletes or anonymizes the data.\nrights:\n- right: access, correct, delete\n  text: access, correct, or delete that information\n- right: portability\n  text: request portability\n- right: object to processing\n  text: object to processing\n- right: withdraw consent\n  text: or withdraw consent\n\
  sale_or_sharing:\n  stance: unstated\n  text: Bolt does not sell Personal Information.\n"
source_yaml_url: https://artifacts.apis.io/bolt-financial/privacy/bolt-financial-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from Bolt Financial's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Checkout
- E-Commerce
- Fintech
- Subscription
- Tokenization
- Fraud Prevention
- Identity
- Webhook
---
