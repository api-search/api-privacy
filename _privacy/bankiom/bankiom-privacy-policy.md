---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: financial
    text: 'Transaction history: To identify missed cashback, uncredited rewards, and billing gaps.'
  - category: identifying
    text: Email address — for account authentication and transactional communications
  - category: identifying
    text: First name — to personalise the app experience and invite messages
  - category: device
    text: Device token (iOS) — to deliver push notifications about Fix-It actions and earnings updates
  - category: contact
    text: Phone number — only if you choose to receive SMS invite confirmations; governed by TCPA
  - category: behavioral
    text: In-app events (e.g. audit revealed, Fix-It opened, widget installed) — via Amplitude
  - category: device
    text: App crashes and performance metrics — via Apple's native crash reporting
  deletion:
    route: Email puravida@bankiom.com or delete account in app
    text: When an account is deleted, we execute a structured deletion process within 30 days.
  dpa:
    available: null
    text: Every provider is bound by a data processing agreement.
    url: null
  purposes:
  - purpose: Deliver the audit
    text: Analyse 90 days of transactions against card reward rules to identify gaps and compute your found amount.
  - purpose: Fix-It actions
    text: Generate and track dispute packages on your behalf.
  - purpose: Subscription billing
    text: Calculate your monthly fee (20% of confirmed recovered amounts, capped at $20).
  - purpose: Invite system
    text: Send personalised SMS invites to contacts you select.
  - purpose: Product improvement
    text: Understand how features are used. Identify performance issues. Improve audit accuracy over time.
  - purpose: Legal compliance
    text: Retain records as required by applicable law (tax, TCPA, GDPR/CCPA deletion logs).
  residency:
  - region: United States
    text: All Bankiom data is hosted on AWS (US East region).
  retention:
  - period: 90 days from pull date
    scope: Raw bank transactions
    text: Raw bank transactions 90 days from pull date
  - period: Duration of account
    scope: Plaid access tokens
    text: Plaid access tokens Duration of account (revoked immediately on deletion)
  - period: 24 months
    scope: Audit findings
    text: Audit findings 24 months
  - period: 7 years
    scope: Earnings ledger
    text: Earnings ledger 7 years (financial record-keeping)
  - period: 7 years
    scope: Stripe billing records
    text: Stripe billing records 7 years (tax and financial compliance)
  - period: 24 months
    scope: Analytics events
    text: Analytics events 24 months (anonymized)
  rights:
  - right: Access
    text: 'Access: Request a copy of all personal data we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of any inaccurate or incomplete data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your account and all associated personal data.'
  - right: Portability
    text: 'Portability: Request your data in a structured, machine-readable format.'
  - right: Object (GDPR)
    text: 'GDPR (EU/EEA residents): You have rights under GDPR including the right to object to processing and to lodge a complaint with a supervisory authority.'
  role:
    text: When this policy says "Bankiom", "we", "us", or "our", it means PuraVida Inc.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data. We do not share financial data with advertisers.
  subprocessors:
    text: 'Amazon Web Services: Cloud infrastructure. All Bankiom data is hosted on AWS (US East region).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bankiom
provenance_date: '2026-11-09'
provider_name: Bankiom
provider_slug: bankiom
slug: bankiom-privacy-policy
source_date: '2026-11-09'
source_filename: bankiom-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bankiom.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bankiom\naid: bankiom\nurl: https://bankiom.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: When this policy says \"Bankiom\", \"we\", \"us\", or \"our\", it means PuraVida Inc.\ndata_categories:\n- category: financial\n  text: 'Transaction history: To identify missed cashback, uncredited rewards, and billing gaps.'\n- category: identifying\n  text: Email address — for account authentication and transactional communications\n- category: identifying\n  text: First name — to personalise the app experience and invite messages\n- category: device\n  text: Device token (iOS) — to deliver\
  \ push notifications about Fix-It actions and earnings updates\n- category: contact\n  text: Phone number — only if you choose to receive SMS invite confirmations; governed by TCPA\n- category: behavioral\n  text: In-app events (e.g. audit revealed, Fix-It opened, widget installed) — via Amplitude\n- category: device\n  text: App crashes and performance metrics — via Apple's native crash reporting\npurposes:\n- purpose: Deliver the audit\n  text: Analyse 90 days of transactions against card reward rules to identify gaps and compute your found amount.\n- purpose: Fix-It actions\n  text: Generate and track dispute packages on your behalf.\n- purpose: Subscription billing\n  text: Calculate your monthly fee (20% of confirmed recovered amounts, capped at $20).\n- purpose: Invite system\n  text: Send personalised SMS invites to contacts you select.\n- purpose: Product improvement\n  text: Understand how features are used. Identify performance issues. Improve audit accuracy over time.\n- purpose:\
  \ Legal compliance\n  text: Retain records as required by applicable law (tax, TCPA, GDPR/CCPA deletion logs).\nretention:\n- scope: Raw bank transactions\n  period: 90 days from pull date\n  text: Raw bank transactions 90 days from pull date\n- scope: Plaid access tokens\n  period: Duration of account\n  text: Plaid access tokens Duration of account (revoked immediately on deletion)\n- scope: Audit findings\n  period: 24 months\n  text: Audit findings 24 months\n- scope: Earnings ledger\n  period: 7 years\n  text: Earnings ledger 7 years (financial record-keeping)\n- scope: Stripe billing records\n  period: 7 years\n  text: Stripe billing records 7 years (tax and financial compliance)\n- scope: Analytics events\n  period: 24 months\n  text: Analytics events 24 months (anonymized)\nresidency:\n- region: United States\n  text: All Bankiom data is hosted on AWS (US East region).\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Amazon Web Services: Cloud infrastructure. All Bankiom data\
  \ is hosted on AWS (US East region).'\ndpa:\n  available: null\n  url: null\n  text: Every provider is bound by a data processing agreement.\ndeletion:\n  route: Email puravida@bankiom.com or delete account in app\n  text: When an account is deleted, we execute a structured deletion process within 30 days.\nrights:\n- right: Access\n  text: 'Access: Request a copy of all personal data we hold about you.'\n- right: Correction\n  text: 'Correction: Request correction of any inaccurate or incomplete data.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your account and all associated personal data.'\n- right: Portability\n  text: 'Portability: Request your data in a structured, machine-readable format.'\n- right: Object (GDPR)\n  text: 'GDPR (EU/EEA residents): You have rights under GDPR including the right to object to processing and to\n    lodge a complaint with a supervisory authority.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data. We do not share financial\
  \ data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/bankiom/privacy/bankiom-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from Bankiom's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Neobank
- Personal Finance
- AI Agents
- Payments
- United Arab Emirates
- GCC
---
