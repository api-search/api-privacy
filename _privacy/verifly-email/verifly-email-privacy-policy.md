---
api_specs:
- filename: verifly-email-account-api-openapi.yml
  format: yaml
  label: verifly-email Account API
  slug: verifly-email-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-account-api-openapi.yml
- filename: verifly-email-billing-api-openapi.yml
  format: yaml
  label: verifly-email Billing API
  slug: verifly-email-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-billing-api-openapi.yml
- filename: verifly-email-clean-api-openapi.yml
  format: yaml
  label: verifly-email Clean API
  slug: verifly-email-clean-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-clean-api-openapi.yml
- filename: verifly-email-extract-api-openapi.yml
  format: yaml
  label: verifly-email Extract API
  slug: verifly-email-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-extract-api-openapi.yml
- filename: verifly-email-files-api-openapi.yml
  format: yaml
  label: verifly-email Files API
  slug: verifly-email-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-files-api-openapi.yml
- filename: verifly-email-jobs-api-openapi.yml
  format: yaml
  label: verifly-email Jobs API
  slug: verifly-email-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-jobs-api-openapi.yml
- filename: verifly-email-list-cleaning-api-openapi.yml
  format: yaml
  label: verifly-email List Cleaning API
  slug: verifly-email-list-cleaning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-list-cleaning-api-openapi.yml
- filename: verifly-email-onboarding-api-openapi.yml
  format: yaml
  label: verifly-email Onboarding API
  slug: verifly-email-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-onboarding-api-openapi.yml
- filename: verifly-email-tools-api-openapi.yml
  format: yaml
  label: verifly-email Tools API
  slug: verifly-email-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-tools-api-openapi.yml
- filename: verifly-email-verification-api-openapi.yml
  format: yaml
  label: verifly-email Verification API
  slug: verifly-email-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-verification-api-openapi.yml
- filename: verifly-email-verify-api-openapi.yml
  format: yaml
  label: verifly-email Verify API
  slug: verifly-email-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/verifly-email/openapi/verifly-email-verify-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (for account creation and login)
  - category: contact
    text: Name (optional)
  - category: financial
    text: Payment information (processed by Stripe, not stored by us)
  - category: behavioral
    text: API request logs (endpoint, timestamp, response code)
  - category: device
    text: Browser type and version
  - category: device
    text: Device information
  - category: location
    text: IP address
  deletion:
    route: Contact support or privacy request email
    text: To exercise these rights, contact us at support@verifly.email (or privacy@verifly.email) or through the dashboard.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the email verification service
    text: Provide and maintain the email verification service
  - purpose: Process payments and manage account
    text: Process payments and manage your account
  - purpose: Prevent fraud and abuse
    text: Prevent fraud and abuse
  - purpose: Improve service and develop new features
    text: Improve our service and develop new features
  - purpose: Comply with legal obligations
    text: Comply with legal obligations
  retention:
  - period: 24 hours
    scope: Email verification results
    text: Cached for 24 hours, then deleted
  - period: 30 days
    scope: Bulk job data
    text: Retained for 30 days, then automatically deleted
  - period: null
    scope: Account data
    text: Retained while your account is active
  - period: 90 days
    scope: API logs
    text: Retained for 90 days for debugging and security
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Rectification: Correct inaccurate data'
  - right: Erasure
    text: 'Erasure: Request deletion of your data'
  - right: Portability
    text: 'Portability: Receive your data in a portable format'
  - right: Objection
    text: 'Objection: Object to certain processing'
  - right: Restriction
    text: 'Restriction: Limit how we use your data'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell your data.
  subprocessors:
    text: 'Email verification infrastructure (Million Verifier): Receives the email addresses you submit so their deliverability can be checked.'
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place, including standard contractual clauses where required.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: verifly-email
provenance_date: '2026-11-10'
provider_name: verifly-email
provider_slug: verifly-email
slug: verifly-email-privacy-policy
source_date: '2026-11-10'
source_filename: verifly-email-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://verifly.email/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: verifly-email\naid: verifly-email\nurl: https://verifly.email/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (for account creation and login)\n- category: contact\n  text: Name (optional)\n- category: financial\n  text: Payment information (processed by Stripe, not stored by us)\n- category: behavioral\n  text: API request logs (endpoint, timestamp, response code)\n- category: device\n  text: Browser type and version\n- category: device\n  text: Device information\n- category: location\n  text: IP address\npurposes:\n\
  - purpose: Provide and maintain the email verification service\n  text: Provide and maintain the email verification service\n- purpose: Process payments and manage account\n  text: Process payments and manage your account\n- purpose: Prevent fraud and abuse\n  text: Prevent fraud and abuse\n- purpose: Improve service and develop new features\n  text: Improve our service and develop new features\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations\nretention:\n- scope: Email verification results\n  period: 24 hours\n  text: Cached for 24 hours, then deleted\n- scope: Bulk job data\n  period: 30 days\n  text: Retained for 30 days, then automatically deleted\n- scope: Account data\n  period: null\n  text: Retained while your account is active\n- scope: API logs\n  period: 90 days\n  text: Retained for 90 days for debugging and security\nresidency: []\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place, including standard contractual\
  \ clauses where required.\nsubprocessors:\n  url: null\n  text: 'Email verification infrastructure (Million Verifier): Receives the email addresses you submit so their\n    deliverability can be checked.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support or privacy request email\n  text: To exercise these rights, contact us at support@verifly.email (or privacy@verifly.email) or through the\n    dashboard.\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Rectification: Correct inaccurate data'\n- right: Erasure\n  text: 'Erasure: Request deletion of your data'\n- right: Portability\n  text: 'Portability: Receive your data in a portable format'\n- right: Objection\n  text: 'Objection: Object to certain processing'\n- right: Restriction\n  text: 'Restriction: Limit how we use your data'\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell your data.\n"
source_yaml_url: https://artifacts.apis.io/verifly-email/privacy/verifly-email-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from verifly-email's own page on 2026-11-10.
synthetic: false
tags:
- Email Verification
- MCP
- Developer Tools
- Verification
- Company
---
