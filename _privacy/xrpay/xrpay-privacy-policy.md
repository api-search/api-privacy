---
api_specs:
- filename: xrpay-connected-account-api-openapi.yml
  format: yaml
  label: XRPay Connected account API
  slug: xrpay-connected-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-connected-account-api-openapi.yml
- filename: xrpay-payment-intents-api-openapi.yml
  format: yaml
  label: XRPay Payment intents API
  slug: xrpay-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-payment-intents-api-openapi.yml
- filename: xrpay-payouts-api-openapi.yml
  format: yaml
  label: XRPay Payouts API
  slug: xrpay-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-payouts-api-openapi.yml
- filename: xrpay-payroll-api-openapi.yml
  format: yaml
  label: XRPay Payroll API
  slug: xrpay-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-payroll-api-openapi.yml
- filename: xrpay-refunds-api-openapi.yml
  format: yaml
  label: XRPay Refunds API
  slug: xrpay-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-refunds-api-openapi.yml
- filename: xrpay-sandbox-api-openapi.yml
  format: yaml
  label: XRPay Sandbox API
  slug: xrpay-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-sandbox-api-openapi.yml
- filename: xrpay-webhooks-api-openapi.yml
  format: yaml
  label: XRPay Webhooks API
  slug: xrpay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-webhooks-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full legal name, date of birth, residential address, Social Security Number (SSN), and government-issued ID
  - category: financial
    text: 'Bank account data: Bank name, routing number, and account number (US ACH), IBAN and BIC/SWIFT (international), or wire transfer details'
  - category: contact
    text: Merchant email address (provided by BigCommerce during install)
  - category: contact
    text: 'Optional contact profile: display name and verified phone number when you choose to let contacts find you'
  - category: location
    text: country, Mobile Money phone number and network
  - category: behavioral
    text: 'Product usage data: app interactions, transaction-flow events, anonymous installation and session identifiers, country code, and error or outcome information'
  - category: device
    text: 'Device and notification data: push notification token, platform, app version, and related delivery status'
  - category: financial
    text: 'Transaction history: order IDs, amounts, payment statuses, XRPL transaction hashes'
  deletion:
    route: Email support@xbitinnovations.com
    text: Merchants and off-ramp users may request deletion of non-regulated data at any time by emailing support@xbitinnovations.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide sales channel and catalog services
    text: To connect the sales channels you authorize and keep your selected product catalog up to date
  - purpose: Operate off-ramp
    text: 'To operate the xApp off-ramp: verify identity via Bridge.xyz, link bank accounts via Plaid, initiate ACH withdrawals, and record transaction history'
  - purpose: Fraud prevention
    text: To detect and prevent fraudulent or unauthorized activity
  - purpose: Legal compliance
    text: To comply with US financial regulations (BSA/FinCEN) applicable to fiat off-ramp services
  - purpose: Product analytics
    text: To measure product usage, diagnose failures, and improve reliability using first-party analytics
  residency:
  - region: EU/US
    text: All data is stored in a PostgreSQL database hosted on Railway (EU/US region).
  retention:
  - period: 5 years
    scope: xApp off-ramp KYC records
    text: xApp off-ramp KYC records are retained for a minimum of 5 years as required by US Bank Secrecy Act (BSA) and FinCEN regulations.
  - period: 7 years
    scope: Off-ramp transaction records
    text: Off-ramp transaction records (amounts, timestamps, XRPL hashes, ACH transfer IDs) are retained for 7 years to comply with financial recordkeeping requirements
  - period: 12 months
    scope: Waitlist email addresses
    text: Waitlist email addresses are deleted upon request or within 12 months if no launch notification is sent
  - period: seven days
    scope: Temporary import snapshots
    text: Temporary import snapshots expire after seven days and are removed by an hourly cleanup process
  - period: while the App is installed
    scope: Merchant and transaction data
    text: Merchant and transaction data is retained while the App is installed
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you
  - right: Rectification
    text: Rectification — correct inaccurate or incomplete data
  - right: Erasure
    text: Erasure — request deletion of your personal data ("right to be forgotten")
  - right: Restriction
    text: Restriction — request that we restrict processing of your data
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format
  - right: Objection
    text: Objection — object to processing based on legitimate interests
  role:
    text: Xbit Innovations LLC ("we," "us," "our") operates XRPay
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade personal data to advertisers or data brokers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: XRPay
provenance_date: '2026-11-10'
provider_name: XRPay
provider_slug: xrpay
slug: xrpay-privacy-policy
source_date: '2026-11-10'
source_filename: xrpay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.xrpay.it/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: XRPay\naid: xrpay\nurl: https://www.xrpay.it/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Xbit Innovations LLC (\"we,\" \"us,\" \"our\") operates XRPay\ndata_categories:\n- category: identifying\n  text: Full legal name, date of birth, residential address, Social Security Number (SSN), and government-issued\n    ID\n- category: financial\n  text: 'Bank account data: Bank name, routing number, and account number (US ACH), IBAN and BIC/SWIFT (international),\n    or wire transfer details'\n- category: contact\n  text: Merchant email address (provided by BigCommerce during install)\n\
  - category: contact\n  text: 'Optional contact profile: display name and verified phone number when you choose to let contacts find you'\n- category: location\n  text: country, Mobile Money phone number and network\n- category: behavioral\n  text: 'Product usage data: app interactions, transaction-flow events, anonymous installation and session identifiers,\n    country code, and error or outcome information'\n- category: device\n  text: 'Device and notification data: push notification token, platform, app version, and related delivery status'\n- category: financial\n  text: 'Transaction history: order IDs, amounts, payment statuses, XRPL transaction hashes'\npurposes:\n- purpose: Provide sales channel and catalog services\n  text: To connect the sales channels you authorize and keep your selected product catalog up to date\n- purpose: Operate off-ramp\n  text: 'To operate the xApp off-ramp: verify identity via Bridge.xyz, link bank accounts via Plaid, initiate ACH\n    withdrawals, and\
  \ record transaction history'\n- purpose: Fraud prevention\n  text: To detect and prevent fraudulent or unauthorized activity\n- purpose: Legal compliance\n  text: To comply with US financial regulations (BSA/FinCEN) applicable to fiat off-ramp services\n- purpose: Product analytics\n  text: To measure product usage, diagnose failures, and improve reliability using first-party analytics\nretention:\n- scope: xApp off-ramp KYC records\n  period: 5 years\n  text: xApp off-ramp KYC records are retained for a minimum of 5 years as required by US Bank Secrecy Act (BSA)\n    and FinCEN regulations.\n- scope: Off-ramp transaction records\n  period: 7 years\n  text: Off-ramp transaction records (amounts, timestamps, XRPL hashes, ACH transfer IDs) are retained for 7 years\n    to comply with financial recordkeeping requirements\n- scope: Waitlist email addresses\n  period: 12 months\n  text: Waitlist email addresses are deleted upon request or within 12 months if no launch notification is sent\n\
  - scope: Temporary import snapshots\n  period: seven days\n  text: Temporary import snapshots expire after seven days and are removed by an hourly cleanup process\n- scope: Merchant and transaction data\n  period: while the App is installed\n  text: Merchant and transaction data is retained while the App is installed\nresidency:\n- region: EU/US\n  text: All data is stored in a PostgreSQL database hosted on Railway (EU/US region).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@xbitinnovations.com\n  text: Merchants and off-ramp users may request deletion of non-regulated data at any time by emailing support@xbitinnovations.com\nrights:\n- right: Access\n  text: Access — request a copy of the personal data we hold about you\n- right: Rectification\n  text: Rectification — correct inaccurate or incomplete data\n- right: Erasure\n  text: Erasure — request deletion of your personal data (\"right\
  \ to be forgotten\")\n- right: Restriction\n  text: Restriction — request that we restrict processing of your data\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format\n- right: Objection\n  text: Objection — object to processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade personal data to advertisers or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/xrpay/privacy/xrpay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from XRPay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Merchant Payments
- Refunds
- Webhook
- Fintech
---
