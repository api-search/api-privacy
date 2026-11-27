---
api_specs:
- filename: logo-dev-account-api-openapi.yml
  format: yaml
  label: Logo.dev Account API
  slug: logo-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-account-api-openapi.yml
- filename: logo-dev-brands-api-openapi.yml
  format: yaml
  label: Logo.dev Brands API
  slug: logo-dev-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-brands-api-openapi.yml
- filename: logo-dev-flags-api-openapi.yml
  format: yaml
  label: Logo.dev Flags API
  slug: logo-dev-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-flags-api-openapi.yml
- filename: logo-dev-logo-cdn-api-openapi.yml
  format: yaml
  label: Logo.dev Logo CDN API
  slug: logo-dev-logo-cdn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-logo-cdn-api-openapi.yml
- filename: logo-dev-logos-api-openapi.yml
  format: yaml
  label: Logo.dev Logos API
  slug: logo-dev-logos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-logos-api-openapi.yml
- filename: logo-dev-search-api-openapi.yml
  format: yaml
  label: Logo.dev Search API
  slug: logo-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-search-api-openapi.yml
- filename: logo-dev-subscriptions-api-openapi.yml
  format: yaml
  label: Logo.dev Subscriptions API
  slug: logo-dev-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-subscriptions-api-openapi.yml
- filename: logo-dev-transaction-enrichment-api-api-openapi.yml
  format: yaml
  label: Logo.dev Transaction Enrichment API
  slug: logo-dev-transaction-enrichment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-transaction-enrichment-api-api-openapi.yml
- filename: logo-dev-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Logo.dev Webhook endpoints API
  slug: logo-dev-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logo-dev/openapi/logo-dev-webhook-endpoints-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your name, email address, and organization details.
  - category: device
    text: we collect IP addresses (a technical necessity of HTTPS), the domain or URL queried, request timestamps, and the account, organization, and plan that made the request.
  - category: behavioral
    text: We use PostHog to understand how our website and product are used.
  - category: communication
    text: Service emails cover account, security, billing, usage-limit, and other operational matters.
  deletion:
    route: email support@logo.dev
    text: To exercise any of these rights, email support@logo.dev .
  dpa:
    available: true
    text: For customers subject to the GDPR or applicable data protection law, our Data Processing Agreement forms part of our Terms of Service .
    url: null
  purposes:
  - purpose: service delivery and product improvement
    text: This data is used for service delivery, usage metering, security monitoring, and product improvement.
  - purpose: payments and billing
    text: To process payments and manage billing
  - purpose: security
    text: To monitor and ensure the security of the Services
  - purpose: legal compliance
    text: To comply with legal obligations
  residency:
  - region: United States
    text: your personal data is transferred to the United States.
  retention:
  - period: 120 days
    scope: API request logs
    text: 'API request logs (IP addresses, API request data): deleted within 120 days.'
  - period: 400 days
    scope: Security and audit logs
    text: 'Security and audit logs , which can include IP addresses: deleted within 400 days.'
  - period: 35 days
    scope: Database backups
    text: Copies in database backups expire within 35 days.
  - period: null
    scope: Account data
    text: retained for the duration of your account and deleted when you delete it.
  rights:
  - right: Access
    text: Request a copy of the personal data we hold about you.
  - right: Rectification
    text: Request correction of inaccurate personal data.
  - right: Erasure
    text: Request deletion of your personal data.
  - right: Portability
    text: Request your personal data in a structured, machine-readable format.
  - right: Objection
    text: Object to the processing of your personal data based on legitimate interests.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Our current sub-processor notice is available on our Sub-processors page.
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are protected by the EU Standard Contractual Clauses (SCCs), as described in our Data Processing Agreement .
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Logo.dev
provenance_date: '2026-11-09'
provider_name: Logo.dev
provider_slug: logo-dev
slug: logo-dev-privacy-policy
source_date: '2026-11-09'
source_filename: logo-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.logo.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Logo.dev\naid: logo-dev\nurl: https://www.logo.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your name, email address, and organization details.\n- category: device\n  text: we collect IP addresses (a technical necessity of HTTPS), the domain or URL queried, request timestamps,\n    and the account, organization, and plan that made the request.\n- category: behavioral\n  text: We use PostHog to understand how our website and product are used.\n- category: communication\n  text:\
  \ Service emails cover account, security, billing, usage-limit, and other operational matters.\npurposes:\n- purpose: service delivery and product improvement\n  text: This data is used for service delivery, usage metering, security monitoring, and product improvement.\n- purpose: payments and billing\n  text: To process payments and manage billing\n- purpose: security\n  text: To monitor and ensure the security of the Services\n- purpose: legal compliance\n  text: To comply with legal obligations\nretention:\n- scope: API request logs\n  period: 120 days\n  text: 'API request logs (IP addresses, API request data): deleted within 120 days.'\n- scope: Security and audit logs\n  period: 400 days\n  text: 'Security and audit logs , which can include IP addresses: deleted within 400 days.'\n- scope: Database backups\n  period: 35 days\n  text: Copies in database backups expire within 35 days.\n- scope: Account data\n  period: null\n  text: retained for the duration of your account and deleted\
  \ when you delete it.\nresidency:\n- region: United States\n  text: your personal data is transferred to the United States.\ntransfers:\n- mechanism: SCC\n  text: These transfers are protected by the EU Standard Contractual Clauses (SCCs), as described in our Data Processing\n    Agreement .\nsubprocessors:\n  url: null\n  text: Our current sub-processor notice is available on our Sub-processors page.\ndpa:\n  available: true\n  url: null\n  text: For customers subject to the GDPR or applicable data protection law, our Data Processing Agreement forms\n    part of our Terms of Service .\ndeletion:\n  route: email support@logo.dev\n  text: To exercise any of these rights, email support@logo.dev .\nrights:\n- right: Access\n  text: Request a copy of the personal data we hold about you.\n- right: Rectification\n  text: Request correction of inaccurate personal data.\n- right: Erasure\n  text: Request deletion of your personal data.\n- right: Portability\n  text: Request your personal data\
  \ in a structured, machine-readable format.\n- right: Objection\n  text: Object to the processing of your personal data based on legitimate interests.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/logo-dev/privacy/logo-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Logo.dev's own page on 2026-11-09.
synthetic: false
tags:
- Logo
- Branding
- CDN
- Free Tier
---
