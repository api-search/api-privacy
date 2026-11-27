---
api_specs:
- filename: bullion-api-bullion-api-api-api-openapi.yml
  format: yaml
  label: Bullion API Bullion API API
  slug: bullion-api-bullion-api-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-bullion-api-api-api-openapi.yml
- filename: bullion-api-central-bank-gold-api-openapi.yml
  format: yaml
  label: Bullion API Central Bank Gold API
  slug: bullion-api-central-bank-gold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-central-bank-gold-api-openapi.yml
- filename: bullion-api-central-bank-reserves-api-openapi.yml
  format: yaml
  label: Bullion API Central Bank Reserves API
  slug: bullion-api-central-bank-reserves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-central-bank-reserves-api-openapi.yml
- filename: bullion-api-countries-api-openapi.yml
  format: yaml
  label: Bullion API Countries API
  slug: bullion-api-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-countries-api-openapi.yml
- filename: bullion-api-gold-api-openapi.yml
  format: yaml
  label: Bullion API Gold API
  slug: bullion-api-gold-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-gold-api-openapi.yml
- filename: bullion-api-portfolio-api-openapi.yml
  format: yaml
  label: Bullion API Portfolio API
  slug: bullion-api-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-portfolio-api-openapi.yml
- filename: bullion-api-silver-api-openapi.yml
  format: yaml
  label: Bullion API Silver API
  slug: bullion-api-silver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bullion-api/openapi/bullion-api-silver-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your name and email address, plus a securely hashed password when you use email/password sign-in.'
  - category: financial
    text: 'Billing data: handled by Stripe. We receive your plan, the Stripe customer ID and the subscription status back from Stripe.'
  - category: financial
    text: 'Transaction records: the transaction date, quantity and weight unit, amount paid or received, delivery costs, fees, product description, and the tax treatment you declare.'
  - category: device
    text: Sign-in sessions can separately contain IP addresses and user agents
  - category: communication
    text: 'Support emails: anything you send us at hello@bullionapi.dev or our privacy, security and sales addresses, stored in Gmail.'
  - category: behavioral
    text: It records aggregate figures such as page views, referring pages, browser and device type, country, and page-load performance, and we see only those totals, not individual visitors.
  deletion:
    route: Dashboard Delete account button or email privacy@bullionapi.dev
    text: The dashboard has a Delete account button; deletion happens immediately and cannot be undone.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, authenticate and bill the service
    text: Provide, authenticate and bill the service.
  - purpose: Enforce quotas and detect abuse
    text: Enforce per-plan quotas and detect abusive usage.
  - purpose: Diagnose outages and support
    text: Diagnose outages and respond to support requests.
  - purpose: Legal compliance
    text: Comply with legal obligations and respond to lawful requests.
  - purpose: Portfolio features
    text: 'We use this information only to provide the portfolio features: showing what you hold, what it cost you, what it is worth now, and any gains or losses.'
  residency:
  - region: Global
    text: 'Processing location: Global network, including processing outside the UK/EEA; no UK/EEA-only residency is promised.'
  - region: United States
    text: 'Processing location: United States and other countries used by Stripe; no account-specific regional restriction is verified.'
  retention:
  - period: 30 days
    scope: Request logs
    text: 'Request logs: deleted once they are 30 days old, by a job that runs every day.'
  - period: null
    scope: Account data
    text: 'Account data: for as long as your account is active.'
  - period: 12 months
    scope: Support emails
    text: 'Support emails: our target is deletion within 12 months of the last exchange, unless a documented legal need requires longer retention.'
  - period: 24 hours
    scope: Revoked API keys
    text: Revoking a key stops it working immediately and the row is deleted within 24 hours.
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you.
  - right: Correction
    text: Correction — ask us to fix anything wrong.
  - right: Deletion
    text: Deletion — delete your account and the data we hold.
  - right: Export
    text: Export — while signed in, download your application data as JSON .
  - right: Object or restrict
    text: Object or restrict — object to certain processing or ask us to pause it.
  - right: Withdraw consent
    text: Withdraw consent — where our lawful basis is consent, you can withdraw it at any time without affecting prior processing.
  - right: Complain
    text: Complain — to your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use these service providers and recipients.
    url: null
  transfers:
  - mechanism: SCC
    text: Applicable transfer safeguards can include an adequacy decision, the European Commission's Standard Contractual Clauses and the UK addendum or International Data Transfer Agreement.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bullion API
provenance_date: '2026-11-09'
provider_name: Bullion API
provider_slug: bullion-api
slug: bullion-api-privacy-policy
source_date: '2026-11-09'
source_filename: bullion-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bullionapi.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bullion API\naid: bullion-api\nurl: https://bullionapi.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your name and email address, plus a securely hashed password when you use email/password\n    sign-in.'\n- category: financial\n  text: 'Billing data: handled by Stripe. We receive your plan, the Stripe customer ID and the subscription status\n    back from Stripe.'\n- category: financial\n  text: 'Transaction records: the transaction date, quantity and weight unit, amount paid or received, delivery\n    costs,\
  \ fees, product description, and the tax treatment you declare.'\n- category: device\n  text: Sign-in sessions can separately contain IP addresses and user agents\n- category: communication\n  text: 'Support emails: anything you send us at hello@bullionapi.dev or our privacy, security and sales addresses,\n    stored in Gmail.'\n- category: behavioral\n  text: It records aggregate figures such as page views, referring pages, browser and device type, country, and\n    page-load performance, and we see only those totals, not individual visitors.\npurposes:\n- purpose: Provide, authenticate and bill the service\n  text: Provide, authenticate and bill the service.\n- purpose: Enforce quotas and detect abuse\n  text: Enforce per-plan quotas and detect abusive usage.\n- purpose: Diagnose outages and support\n  text: Diagnose outages and respond to support requests.\n- purpose: Legal compliance\n  text: Comply with legal obligations and respond to lawful requests.\n- purpose: Portfolio features\n\
  \  text: 'We use this information only to provide the portfolio features: showing what you hold, what it cost you,\n    what it is worth now, and any gains or losses.'\nretention:\n- scope: Request logs\n  period: 30 days\n  text: 'Request logs: deleted once they are 30 days old, by a job that runs every day.'\n- scope: Account data\n  period: null\n  text: 'Account data: for as long as your account is active.'\n- scope: Support emails\n  period: 12 months\n  text: 'Support emails: our target is deletion within 12 months of the last exchange, unless a documented legal\n    need requires longer retention.'\n- scope: Revoked API keys\n  period: 24 hours\n  text: Revoking a key stops it working immediately and the row is deleted within 24 hours.\nresidency:\n- region: Global\n  text: 'Processing location: Global network, including processing outside the UK/EEA; no UK/EEA-only residency\n    is promised.'\n- region: United States\n  text: 'Processing location: United States and other countries\
  \ used by Stripe; no account-specific regional restriction\n    is verified.'\ntransfers:\n- mechanism: SCC\n  text: Applicable transfer safeguards can include an adequacy decision, the European Commission's Standard Contractual\n    Clauses and the UK addendum or International Data Transfer Agreement.\nsubprocessors:\n  url: null\n  text: We use these service providers and recipients.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard Delete account button or email privacy@bullionapi.dev\n  text: The dashboard has a Delete account button; deletion happens immediately and cannot be undone.\nrights:\n- right: Access\n  text: Access — request a copy of the personal data we hold about you.\n- right: Correction\n  text: Correction — ask us to fix anything wrong.\n- right: Deletion\n  text: Deletion — delete your account and the data we hold.\n- right: Export\n  text: Export — while signed in, download your application data as JSON .\n- right: Object or restrict\n\
  \  text: Object or restrict — object to certain processing or ask us to pause it.\n- right: Withdraw consent\n  text: Withdraw consent — where our lawful basis is consent, you can withdraw it at any time without affecting\n    prior processing.\n- right: Complain\n  text: Complain — to your local data protection authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bullion-api/privacy/bullion-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 27 quoted statements, read from Bullion API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gold
- Prices
- Finance
- Data
---
