---
api_specs:
- filename: send21-io-account-api-openapi.yml
  format: yaml
  label: send21-io Account API
  slug: send21-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-account-api-openapi.yml
- filename: send21-io-auth-api-openapi.yml
  format: yaml
  label: send21-io Auth API
  slug: send21-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-auth-api-openapi.yml
- filename: send21-io-checkout-api-openapi.yml
  format: yaml
  label: send21-io Checkout API
  slug: send21-io-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-checkout-api-openapi.yml
- filename: send21-io-demo-api-openapi.yml
  format: yaml
  label: send21-io Demo API
  slug: send21-io-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-demo-api-openapi.yml
- filename: send21-io-drafts-api-openapi.yml
  format: yaml
  label: send21-io Drafts API
  slug: send21-io-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-drafts-api-openapi.yml
- filename: send21-io-fees-api-openapi.yml
  format: yaml
  label: send21-io Fees API
  slug: send21-io-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-fees-api-openapi.yml
- filename: send21-io-rates-api-openapi.yml
  format: yaml
  label: send21-io Rates API
  slug: send21-io-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-rates-api-openapi.yml
- filename: send21-io-recurringtemplates-api-openapi.yml
  format: yaml
  label: send21-io Recurring Templates API
  slug: send21-io-recurringtemplates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-recurringtemplates-api-openapi.yml
- filename: send21-io-suggestions-api-openapi.yml
  format: yaml
  label: send21-io Suggestions API
  slug: send21-io-suggestions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-suggestions-api-openapi.yml
- filename: send21-io-webhooks-api-openapi.yml
  format: yaml
  label: send21-io Webhooks API
  slug: send21-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-webhooks-api-openapi.yml
- filename: send21-io-address-book-api-openapi.yml
  format: yaml
  label: send21-io Address Book API
  slug: send21-io-address-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-address-book-api-openapi.yml
- filename: send21-io-api-keys-api-openapi.yml
  format: yaml
  label: send21-io API Keys API
  slug: send21-io-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-api-keys-api-openapi.yml
- filename: send21-io-payment-requests-api-openapi.yml
  format: yaml
  label: send21-io Payment Requests API
  slug: send21-io-payment-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/send21-io/openapi/send21-io-payment-requests-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address for account identity, sign-in codes, and payment notifications.
  - category: identifying
    text: Display name (optional) for UI personalization.
  - category: financial
    text: 'Payment metadata : addresses, amounts, memos, and order ids you create.'
  - category: device
    text: IP addresses in the security audit log and rotating server logs, for abuse prevention (legitimate interest).
  deletion:
    route: Account deletion or email to privacy@send21.io
    text: Deleting your account removes your credentials, API keys, address book, webhooks, and drafts.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account identity and sign-in
    text: Email address for account identity, sign-in codes, and payment notifications.
  - purpose: Abuse prevention
    text: IP addresses in the security audit log and rotating server logs, for abuse prevention (legitimate interest).
  - purpose: UI personalization
    text: Display name (optional) for UI personalization.
  retention:
  - period: for the life of the account
    scope: Account data
    text: 'Account data: for the life of the account.'
  - period: 7 years after the fiscal year
    scope: Confirmed payment records
    text: 'Confirmed payment records (incl. fee and valuation data): 7 years after the fiscal year, as required by Swedish accounting law (Bokföringslagen).'
  - period: up to 12 months
    scope: Audit log entries incl. IPs
    text: 'Audit log entries incl. IPs: up to 12 months.'
  - period: 30 days
    scope: Server log files
    text: 'Server log files: 30 days.'
  rights:
  - right: Access and export
    text: You can access and export everything you own through the API (JSON), and edit your email, display name, and address book in the app.
  - right: Erasure, objection or other GDPR request
    text: For erasure, objection, or any other GDPR request, email privacy@send21.io .
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
name: send21-io
provenance_date: '2026-11-10'
provider_name: send21-io
provider_slug: send21-io
slug: send21-io-privacy-policy
source_date: '2026-11-10'
source_filename: send21-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://send21.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: send21-io\naid: send21-io\nurl: https://send21.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address for account identity, sign-in codes, and payment notifications.\n- category: identifying\n  text: Display name (optional) for UI personalization.\n- category: financial\n  text: 'Payment metadata : addresses, amounts, memos, and order ids you create.'\n- category: device\n  text: IP addresses in the security audit log and rotating server logs, for abuse prevention (legitimate interest).\npurposes:\n- purpose: Account identity\
  \ and sign-in\n  text: Email address for account identity, sign-in codes, and payment notifications.\n- purpose: Abuse prevention\n  text: IP addresses in the security audit log and rotating server logs, for abuse prevention (legitimate interest).\n- purpose: UI personalization\n  text: Display name (optional) for UI personalization.\nretention:\n- scope: Account data\n  period: for the life of the account\n  text: 'Account data: for the life of the account.'\n- scope: Confirmed payment records\n  period: 7 years after the fiscal year\n  text: 'Confirmed payment records (incl. fee and valuation data): 7 years after the fiscal year, as required by\n    Swedish accounting law (Bokföringslagen).'\n- scope: Audit log entries incl. IPs\n  period: up to 12 months\n  text: 'Audit log entries incl. IPs: up to 12 months.'\n- scope: Server log files\n  period: 30 days\n  text: 'Server log files: 30 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or email to privacy@send21.io\n  text: Deleting your account removes your credentials, API keys, address book, webhooks, and drafts.\nrights:\n- right: Access and export\n  text: You can access and export everything you own through the API (JSON), and edit your email, display name,\n    and address book in the app.\n- right: Erasure, objection or other GDPR request\n  text: For erasure, objection, or any other GDPR request, email privacy@send21.io .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/send21-io/privacy/send21-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from send21-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cryptocurrency
- Non-Custodial
- Artificial Intelligence
---
