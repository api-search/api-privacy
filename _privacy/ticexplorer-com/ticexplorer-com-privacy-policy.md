---
api_specs:
- filename: ticexplorer-com-admin-api-openapi.yml
  format: yaml
  label: ticexplorer-com Admin API
  slug: ticexplorer-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-admin-api-openapi.yml
- filename: ticexplorer-com-analytics-api-openapi.yml
  format: yaml
  label: ticexplorer-com Analytics API
  slug: ticexplorer-com-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-analytics-api-openapi.yml
- filename: ticexplorer-com-claims-api-openapi.yml
  format: yaml
  label: ticexplorer-com Claims API
  slug: ticexplorer-com-claims-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-claims-api-openapi.yml
- filename: ticexplorer-com-codes-api-openapi.yml
  format: yaml
  label: ticexplorer-com Codes API
  slug: ticexplorer-com-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-codes-api-openapi.yml
- filename: ticexplorer-com-guide-api-openapi.yml
  format: yaml
  label: ticexplorer-com Guide API
  slug: ticexplorer-com-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-guide-api-openapi.yml
- filename: ticexplorer-com-plans-api-openapi.yml
  format: yaml
  label: ticexplorer-com Plans API
  slug: ticexplorer-com-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-plans-api-openapi.yml
- filename: ticexplorer-com-providers-api-openapi.yml
  format: yaml
  label: ticexplorer-com Providers API
  slug: ticexplorer-com-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-providers-api-openapi.yml
- filename: ticexplorer-com-rates-api-openapi.yml
  format: yaml
  label: ticexplorer-com Rates API
  slug: ticexplorer-com-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ticexplorer-com/openapi/ticexplorer-com-rates-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We receive your Clerk user ID and email address, and Clerk stores your name and sign-in details.
  - category: contact
    text: We receive your Clerk user ID and email address, and Clerk stores your name and sign-in details.
  - category: financial
    text: We keep your Stripe customer ID, card brand, last four digits and expiry, your plan, and your invoices.
  - category: device
    text: Our servers and Google Cloud’s load balancer log requests, including the full URL (with any query parameters you send), your IP address and user agent.
  - category: behavioral
    text: 'For each request: the time, the operation (for example, a rate lookup), the result status, the key or connection used, and the price.'
  - category: communication
    text: 'Questions: privacy@ticexplorer.com .'
  deletion:
    route: Email privacy@ticexplorer.com to delete your data or close your account
    text: To see, correct or delete your data, or to close your account, email privacy@ticexplorer.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service, sign in, meter and bill usage
    text: To run the service, sign you in, meter and bill usage, prevent abuse, fix problems, and contact you about your account or billing.
  - purpose: Answer searches via outside services
    text: 'To answer some searches we send the search text, without your account details, to outside services: a language-model API for billing-code searches and the US Census Bureau geocoder for addresses.'
  residency:
  - region: United States
    text: Google Cloud, which hosts the service, its logs and backups in the United States.
  retention:
  - period: while your account is open, and afterwards as long as tax and accounting rules require
    scope: Account, key and billing records
    text: 'Account, key and billing records: while your account is open, and afterwards as long as tax and accounting rules require.'
  - period: for the life of your account
    scope: Usage records
    text: 'Usage records: for the life of your account.'
  - period: 30 days
    scope: Access logs
    text: 'Access logs: 30 days.'
  - period: up to 180 days
    scope: Database backups
    text: 'Database backups: daily, kept up to 180 days.'
  - period: 30 days without use
    scope: MCP refresh tokens
    text: Access tokens expire after one hour and refresh tokens after 30 days without use.
  rights:
  - right: Access, correction and deletion
    text: To see, correct or delete your data, or to close your account, email privacy@ticexplorer.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell or rent your data, and we don’t use it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ticexplorer-com
provenance_date: '2026-11-10'
provider_name: ticexplorer-com
provider_slug: ticexplorer-com
slug: ticexplorer-com-privacy-policy
source_date: '2026-11-10'
source_filename: ticexplorer-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ticexplorer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ticexplorer-com\naid: ticexplorer-com\nurl: https://ticexplorer.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We receive your Clerk user ID and email address, and Clerk stores your name and sign-in details.\n- category: contact\n  text: We receive your Clerk user ID and email address, and Clerk stores your name and sign-in details.\n- category: financial\n  text: We keep your Stripe customer ID, card brand, last four digits and expiry, your plan, and your invoices.\n- category: device\n  text: Our servers and Google Cloud’s\
  \ load balancer log requests, including the full URL (with any query parameters\n    you send), your IP address and user agent.\n- category: behavioral\n  text: 'For each request: the time, the operation (for example, a rate lookup), the result status, the key or connection\n    used, and the price.'\n- category: communication\n  text: 'Questions: privacy@ticexplorer.com .'\npurposes:\n- purpose: Run the service, sign in, meter and bill usage\n  text: To run the service, sign you in, meter and bill usage, prevent abuse, fix problems, and contact you about\n    your account or billing.\n- purpose: Answer searches via outside services\n  text: 'To answer some searches we send the search text, without your account details, to outside services: a language-model\n    API for billing-code searches and the US Census Bureau geocoder for addresses.'\nretention:\n- scope: Account, key and billing records\n  period: while your account is open, and afterwards as long as tax and accounting rules require\n\
  \  text: 'Account, key and billing records: while your account is open, and afterwards as long as tax and accounting\n    rules require.'\n- scope: Usage records\n  period: for the life of your account\n  text: 'Usage records: for the life of your account.'\n- scope: Access logs\n  period: 30 days\n  text: 'Access logs: 30 days.'\n- scope: Database backups\n  period: up to 180 days\n  text: 'Database backups: daily, kept up to 180 days.'\n- scope: MCP refresh tokens\n  period: 30 days without use\n  text: Access tokens expire after one hour and refresh tokens after 30 days without use.\nresidency:\n- region: United States\n  text: Google Cloud, which hosts the service, its logs and backups in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@ticexplorer.com to delete your data or close your account\n  text: To see, correct or delete your data, or to close your account, email\
  \ privacy@ticexplorer.com .\nrights:\n- right: Access, correction and deletion\n  text: To see, correct or delete your data, or to close your account, email privacy@ticexplorer.com .\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell or rent your data, and we don’t use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/ticexplorer-com/privacy/ticexplorer-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from ticexplorer-com's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Finance
- Transparency
- Healthcare
---
