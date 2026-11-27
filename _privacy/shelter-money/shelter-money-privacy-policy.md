---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: financial
    text: Account balances and available balances Transaction history, including up to 24 months from Plaid where available (amounts, dates, merchant names, categories)
  - category: identifying
    text: we collect your email address and authentication credentials through Clerk, our identity provider
  - category: device
    text: Device type, operating system version, and app version Push notification token (to send you alerts) IP address and approximate location (country/region, derived from IP)
  - category: behavioral
    text: Features you use and how you interact with the app (buttons tapped, screens viewed)
  - category: communication
    text: In-app messages and support communications
  deletion:
    route: Settings → Account → Delete Account within the app, or email privacy@shelter.money
    text: Account deletion can also be initiated directly from Settings → Account → Delete Account within the app.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: cash flow predictions and alerts
    text: Generate 30-day cash flow predictions and “safe to spend” calculations
  - purpose: account security
    text: Authenticate your identity and maintain account security
  - purpose: payments
    text: Process subscription payments and manage your account
  - purpose: model improvement
    text: Improve the accuracy of our prediction models using aggregated, anonymized patterns
  residency:
  - region: United States
    text: Shelter is operated from the United States.
  retention:
  - period: null
    scope: account and financial data
    text: Retained while your account is active. Upon account deletion, your data is permanently deleted immediately across all systems
  - period: 7 years
    scope: billing records
    text: 'Billing records: Retained for 7 years to comply with tax and financial record-keeping laws.'
  - period: null
    scope: anonymized usage data
    text: 'Anonymized usage data: May be retained indefinitely in aggregated form that cannot be linked to you.'
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: Ask us to correct inaccurate personal data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your account and associated personal data.'
  - right: Portability
    text: 'Portability: Request an export of your data in a machine-readable format.'
  - right: Limit use of sensitive personal information
    text: 'Right to Limit Use of Sensitive Personal Information: Financial account data is sensitive personal information.'
  - right: Non-discrimination
    text: 'Right to Non-Discrimination: We will not discriminate against you for exercising your CCPA rights.'
  role:
    text: Aura Labs, Inc. (“Shelter,” “we,” “us,” or “our”) operates the Shelter mobile application and website at shelter.money
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as contracts, data processing terms, and standard contractual clauses or equivalent transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Shelter
provenance_date: '2026-11-10'
provider_name: Shelter
provider_slug: shelter-money
slug: shelter-money-privacy-policy
source_date: '2026-11-10'
source_filename: shelter-money-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shelter.money/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Shelter\naid: shelter-money\nurl: https://shelter.money/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Aura Labs, Inc. (“Shelter,” “we,” “us,” or “our”) operates the Shelter mobile application and website at\n    shelter.money\ndata_categories:\n- category: financial\n  text: Account balances and available balances Transaction history, including up to 24 months from Plaid where\n    available (amounts, dates, merchant names, categories)\n- category: identifying\n  text: we collect your email address and authentication credentials through Clerk, our identity provider\n- category: device\n\
  \  text: Device type, operating system version, and app version Push notification token (to send you alerts) IP address\n    and approximate location (country/region, derived from IP)\n- category: behavioral\n  text: Features you use and how you interact with the app (buttons tapped, screens viewed)\n- category: communication\n  text: In-app messages and support communications\npurposes:\n- purpose: cash flow predictions and alerts\n  text: Generate 30-day cash flow predictions and “safe to spend” calculations\n- purpose: account security\n  text: Authenticate your identity and maintain account security\n- purpose: payments\n  text: Process subscription payments and manage your account\n- purpose: model improvement\n  text: Improve the accuracy of our prediction models using aggregated, anonymized patterns\nretention:\n- scope: account and financial data\n  period: null\n  text: Retained while your account is active. Upon account deletion, your data is permanently deleted immediately\n\
  \    across all systems\n- scope: billing records\n  period: 7 years\n  text: 'Billing records: Retained for 7 years to comply with tax and financial record-keeping laws.'\n- scope: anonymized usage data\n  period: null\n  text: 'Anonymized usage data: May be retained indefinitely in aggregated form that cannot be linked to you.'\nresidency:\n- region: United States\n  text: Shelter is operated from the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as contracts, data processing terms, and standard\n    contractual clauses or equivalent transfer mechanisms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Account → Delete Account within the app, or email privacy@shelter.money\n  text: Account deletion can also be initiated directly from Settings → Account → Delete Account within the app.\nrights:\n- right: Access\n  text: 'Access: Request a copy of\
  \ the personal data we hold about you.'\n- right: Correction\n  text: 'Correction: Ask us to correct inaccurate personal data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your account and associated personal data.'\n- right: Portability\n  text: 'Portability: Request an export of your data in a machine-readable format.'\n- right: Limit use of sensitive personal information\n  text: 'Right to Limit Use of Sensitive Personal Information: Financial account data is sensitive personal information.'\n- right: Non-discrimination\n  text: 'Right to Non-Discrimination: We will not discriminate against you for exercising your CCPA rights.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/shelter-money/privacy/shelter-money-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Shelter's own page on 2026-11-10.
synthetic: false
tags:
- Personal Finance
- Budgeting
- Fintech
- MCP
- AI Agents
- Cash Flow Forecasting
---
