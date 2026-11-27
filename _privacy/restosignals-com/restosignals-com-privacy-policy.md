---
api_specs:
- filename: restosignals-com-account-api-openapi.yml
  format: yaml
  label: restosignals-com Account API
  slug: restosignals-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-account-api-openapi.yml
- filename: restosignals-com-auth-api-openapi.yml
  format: yaml
  label: restosignals-com Auth API
  slug: restosignals-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-auth-api-openapi.yml
- filename: restosignals-com-billing-api-openapi.yml
  format: yaml
  label: restosignals-com Billing API
  slug: restosignals-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-billing-api-openapi.yml
- filename: restosignals-com-config-api-openapi.yml
  format: yaml
  label: restosignals-com Config API
  slug: restosignals-com-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-config-api-openapi.yml
- filename: restosignals-com-export-api-openapi.yml
  format: yaml
  label: restosignals-com Export API
  slug: restosignals-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-export-api-openapi.yml
- filename: restosignals-com-health-api-openapi.yml
  format: yaml
  label: restosignals-com Health API
  slug: restosignals-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-health-api-openapi.yml
- filename: restosignals-com-keys-api-openapi.yml
  format: yaml
  label: restosignals-com Keys API
  slug: restosignals-com-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-keys-api-openapi.yml
- filename: restosignals-com-mcp-api-openapi.yml
  format: yaml
  label: restosignals-com MCP API
  slug: restosignals-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-mcp-api-openapi.yml
- filename: restosignals-com-me-api-openapi.yml
  format: yaml
  label: restosignals-com Me API
  slug: restosignals-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-me-api-openapi.yml
- filename: restosignals-com-openings-api-openapi.yml
  format: yaml
  label: restosignals-com Openings API
  slug: restosignals-com-openings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-openings-api-openapi.yml
- filename: restosignals-com-register-api-openapi.yml
  format: yaml
  label: restosignals-com Register API
  slug: restosignals-com-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-register-api-openapi.yml
- filename: restosignals-com-signals-api-openapi.yml
  format: yaml
  label: restosignals-com Signals API
  slug: restosignals-com-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-signals-api-openapi.yml
- filename: restosignals-com-usage-api-openapi.yml
  format: yaml
  label: restosignals-com Usage API
  slug: restosignals-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-usage-api-openapi.yml
- filename: restosignals-com-webhooks-api-openapi.yml
  format: yaml
  label: restosignals-com Webhooks API
  slug: restosignals-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/restosignals-com/openapi/restosignals-com-webhooks-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — your email address and a hashed password (we never store passwords in plain text).
  - category: behavioral
    text: Usage data — API calls, endpoints, credits consumed, timestamps and coarse request metadata
  - category: financial
    text: Payment data — handled by our payment provider (Razorpay). We do not see or store your full card details
  - category: communication
    text: Support messages — anything you email us at support@restosignals.com.
  deletion:
    route: request by email
    text: You can ask us to delete your account and associated personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and meter service
    text: To operate and meter the Service, authenticate you, process payments, provide support, maintain security, comply with law, and send transactional email
  - purpose: essential cookies
    text: We use a small number of essential cookies to keep you signed in; we do not use non-essential tracking cookies.
  retention:
  - period: null
    scope: account and usage data
    text: We keep account and usage data while your account is active and as needed for legal, accounting and security purposes.
  rights:
  - right: access
    text: You can access or delete your account
  - right: deletion
    text: request a copy or deletion of your personal data by emailing support@restosignals.com
  - right: unsubscribe from alerts
    text: unsubscribe from any optional alerts
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not build advertising profiles.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: restosignals-com
provenance_date: '2026-11-10'
provider_name: restosignals-com
provider_slug: restosignals-com
slug: restosignals-com-privacy-policy
source_date: '2026-11-10'
source_filename: restosignals-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://restosignals.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: restosignals-com\naid: restosignals-com\nurl: https://restosignals.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — your email address and a hashed password (we never store passwords in plain text).\n- category: behavioral\n  text: Usage data — API calls, endpoints, credits consumed, timestamps and coarse request metadata\n- category: financial\n  text: Payment data — handled by our payment provider (Razorpay). We do not see or store your full card details\n- category: communication\n  text: Support messages —\
  \ anything you email us at support@restosignals.com.\npurposes:\n- purpose: operate and meter service\n  text: To operate and meter the Service, authenticate you, process payments, provide support, maintain security,\n    comply with law, and send transactional email\n- purpose: essential cookies\n  text: We use a small number of essential cookies to keep you signed in; we do not use non-essential tracking cookies.\nretention:\n- scope: account and usage data\n  period: null\n  text: We keep account and usage data while your account is active and as needed for legal, accounting and security\n    purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request by email\n  text: You can ask us to delete your account and associated personal data.\nrights:\n- right: access\n  text: You can access or delete your account\n- right: deletion\n  text: request a copy or deletion of your personal data\
  \ by emailing support@restosignals.com\n- right: unsubscribe from alerts\n  text: unsubscribe from any optional alerts\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not build advertising profiles.\n"
source_yaml_url: https://artifacts.apis.io/restosignals-com/privacy/restosignals-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from restosignals-com's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Data
- MCP
- Lead Generation
---
