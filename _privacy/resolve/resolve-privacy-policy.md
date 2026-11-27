---
api_specs:
- filename: resolve-access-keys-api-openapi.yml
  format: yaml
  label: Resolve Access Keys API
  slug: resolve-access-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-access-keys-api-openapi.yml
- filename: resolve-charges-api-openapi.yml
  format: yaml
  label: Resolve Charges API
  slug: resolve-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-charges-api-openapi.yml
- filename: resolve-credit-notes-api-openapi.yml
  format: yaml
  label: Resolve Credit Notes API
  slug: resolve-credit-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-credit-notes-api-openapi.yml
- filename: resolve-customers-api-openapi.yml
  format: yaml
  label: Resolve Customers API
  slug: resolve-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-customers-api-openapi.yml
- filename: resolve-invoices-api-openapi.yml
  format: yaml
  label: Resolve Invoices API
  slug: resolve-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-invoices-api-openapi.yml
- filename: resolve-merchants-api-openapi.yml
  format: yaml
  label: Resolve Merchants API
  slug: resolve-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-merchants-api-openapi.yml
- filename: resolve-orders-api-openapi.yml
  format: yaml
  label: Resolve Orders API
  slug: resolve-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-orders-api-openapi.yml
- filename: resolve-payments-api-openapi.yml
  format: yaml
  label: Resolve Payments API
  slug: resolve-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-payments-api-openapi.yml
- filename: resolve-payout-transactions-api-openapi.yml
  format: yaml
  label: Resolve Payout Transactions API
  slug: resolve-payout-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-payout-transactions-api-openapi.yml
- filename: resolve-payouts-api-openapi.yml
  format: yaml
  label: Resolve Payouts API
  slug: resolve-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-payouts-api-openapi.yml
- filename: resolve-shipments-api-openapi.yml
  format: yaml
  label: Resolve Shipments API
  slug: resolve-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-shipments-api-openapi.yml
- filename: resolve-webhooks-api-openapi.yml
  format: yaml
  label: Resolve Webhooks API
  slug: resolve-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/resolve/openapi/resolve-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, Social Security number, address, phone, email, third-party application IDs, and other similar information.
  - category: financial
    text: bank account numbers and/or credit card numbers that you link to your Resolve account or give us when you use the Services.
  - category: location
    text: location, mobile network information and standard web log information
  - category: device
    text: This information may include your IP address, device information including but not limited to identifier, name and type, operating system
  - category: behavioral
    text: details of your purchases, content you viewed, event information, click stream information, and cookies that may uniquely identify your browser or your account.
  deletion:
    route: Request account closure by contacting help@resolvepay.com
    text: You can also request to close your account by contacting us at help@resolvepay.com . If you close your Resolve account, we will mark your account in our database as "Closed," but will keep your account information in our database to comply with our legal obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Perform and improve services
    text: Resolve uses information to perform and improve our services, contact you, conduct research, and provide anonymous reporting for clients.
  - purpose: Targeted marketing
    text: We may use information to deliver targeted marketing, service update notices, and promotional offers based on your communication preferences.
  retention:
  - period: null
    scope: Closed accounts
    text: If you close your Resolve account, we will mark your account in our database as "Closed," but will keep your account information in our database to comply with our legal obligations.
  rights:
  - right: Review and edit personal information
    text: You can review and edit your personal information at any time by logging in to your account on the Website
  - right: Opt out of notifications
    text: If you no longer wish to receive notifications about our Services, you may change your notification preferences by emailing help@resolvepay.com .
  - right: Opt out of SMS messages
    text: You can opt out of receiving SMS messages by emailing help@resolvepay.com .
  - right: Revoke consent to merchant sharing
    text: You're able to revoke your consent at any time by following the steps below.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or rent your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Resolve
provenance_date: '2026-11-10'
provider_name: Resolve
provider_slug: resolve
slug: resolve-privacy-policy
source_date: '2026-11-10'
source_filename: resolve-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://resolvepay.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Resolve\naid: resolve\nurl: https://resolvepay.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, Social Security number, address, phone, email, third-party application IDs, and other similar\n    information.\n- category: financial\n  text: bank account numbers and/or credit card numbers that you link to your Resolve account or give us when you\n    use the Services.\n- category: location\n  text: location, mobile network information and standard web log information\n- category: device\n  text: This information may\
  \ include your IP address, device information including but not limited to identifier,\n    name and type, operating system\n- category: behavioral\n  text: details of your purchases, content you viewed, event information, click stream information, and cookies\n    that may uniquely identify your browser or your account.\npurposes:\n- purpose: Perform and improve services\n  text: Resolve uses information to perform and improve our services, contact you, conduct research, and provide\n    anonymous reporting for clients.\n- purpose: Targeted marketing\n  text: We may use information to deliver targeted marketing, service update notices, and promotional offers based\n    on your communication preferences.\nretention:\n- scope: Closed accounts\n  period: null\n  text: If you close your Resolve account, we will mark your account in our database as \"Closed,\" but will keep\n    your account information in our database to comply with our legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account closure by contacting help@resolvepay.com\n  text: You can also request to close your account by contacting us at help@resolvepay.com . If you close your Resolve\n    account, we will mark your account in our database as \"Closed,\" but will keep your account information in our\n    database to comply with our legal obligations.\nrights:\n- right: Review and edit personal information\n  text: You can review and edit your personal information at any time by logging in to your account on the Website\n- right: Opt out of notifications\n  text: If you no longer wish to receive notifications about our Services, you may change your notification preferences\n    by emailing help@resolvepay.com .\n- right: Opt out of SMS messages\n  text: You can opt out of receiving SMS messages by emailing help@resolvepay.com .\n- right: Revoke consent to merchant sharing\n  text: You're able to\
  \ revoke your consent at any time by following the steps below.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/resolve/privacy/resolve-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Resolve's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- B2B
- Net Terms
- Credit
- Invoicing
- Financing
- Embedded Finance
---
