---
api_specs:
- filename: rendex-dev-account-api-openapi.yml
  format: yaml
  label: rendex-dev Account API
  slug: rendex-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-account-api-openapi.yml
- filename: rendex-dev-batch-api-openapi.yml
  format: yaml
  label: rendex-dev Batch API
  slug: rendex-dev-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-batch-api-openapi.yml
- filename: rendex-dev-health-api-openapi.yml
  format: yaml
  label: rendex-dev Health API
  slug: rendex-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-health-api-openapi.yml
- filename: rendex-dev-jobs-api-openapi.yml
  format: yaml
  label: rendex-dev Jobs API
  slug: rendex-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-jobs-api-openapi.yml
- filename: rendex-dev-screenshot-api-openapi.yml
  format: yaml
  label: rendex-dev Screenshot API
  slug: rendex-dev-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-screenshot-api-openapi.yml
- filename: rendex-dev-watch-api-openapi.yml
  format: yaml
  label: rendex-dev Watch API
  slug: rendex-dev-watch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rendex-dev/openapi/rendex-dev-watch-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect your email address for account management and service notifications
  - category: identifying
    text: A one-way hash of your IP address, stored on your account
  - category: location
    text: Approximate country derived from your IP address
  - category: device
    text: User-Agent header and Referer header, if sent by your client
  - category: behavioral
    text: Target URL or hostname being captured
  - category: financial
    text: Payment processing is handled by Stripe. We do not store credit card numbers or bank account details on our servers.
  - category: communication
    text: Content you ask the AI client to render — a URL, HTML, or Markdown — is sent to our API
  deletion:
    route: Contact legal@rendex.dev to exercise deletion rights
    text: Deletion / Erasure — Request deletion of your personal data and account
  dpa:
    available: true
    text: If you are a business customer who requires a Data Processing Addendum (DPA) under the GDPR, UK GDPR, or similar laws, we will execute our standard DPA on request
    url: null
  purposes:
  - purpose: Service provision
    text: Service provision — Processing API requests and delivering screenshots
  - purpose: Billing
    text: Billing — Tracking API usage for accurate invoicing and plan-cap enforcement
  - purpose: Abuse prevention
    text: Abuse prevention — Detecting and preventing misuse of the Service
  - purpose: Service improvement
    text: Service improvement — Analyzing anonymized usage patterns to improve reliability and performance
  - purpose: Customer support
    text: Customer support — Responding to your requests and debugging issues
  - purpose: Legal compliance
    text: Legal compliance — Meeting legal obligations and responding to lawful requests
  retention:
  - period: 30 days
    scope: Account data
    text: While account is active, deleted within 30 days of closure
  - period: 90 days
    scope: API request metadata (detail fields)
    text: 90 days — target URL, user-agent, referer, country, and ASN are automatically scrubbed after the retention window
  - period: 90 days
    scope: Async job parameters
    text: Async job parameters 90 days — redacted capture params are nulled out after the retention window
  - period: 30 days
    scope: Hosted output in R2
    text: the stored object is automatically deleted by our storage lifecycle policy within 30 days of creation
  - period: 30 days
    scope: Signup throttle records
    text: These throttle records are automatically deleted after 30 days.
  rights:
  - right: Access / Know
    text: Access / Know — Request a copy of the personal data we hold about you and information about how it is processed
  - right: Correction / Rectification
    text: Correction / Rectification — Request correction of inaccurate or incomplete data
  - right: Deletion / Erasure
    text: Deletion / Erasure — Request deletion of your personal data and account
  - right: Portability
    text: Portability — Request your data in a machine-readable portable format
  - right: Object / Restrict
    text: Object / Restrict — Object to or restrict certain processing activities
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Our sub-processors (listed above) may also process data in various jurisdictions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: rendex-dev
provenance_date: '2026-11-10'
provider_name: rendex-dev
provider_slug: rendex-dev
slug: rendex-dev-privacy-policy
source_date: '2026-11-10'
source_filename: rendex-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rendex.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rendex-dev\naid: rendex-dev\nurl: https://rendex.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we collect your email address for account management and service notifications\n- category: identifying\n  text: A one-way hash of your IP address, stored on your account\n- category: location\n  text: Approximate country derived from your IP address\n- category: device\n  text: User-Agent header and Referer header, if sent by your client\n- category: behavioral\n  text: Target URL or hostname being captured\n- category: financial\n\
  \  text: Payment processing is handled by Stripe. We do not store credit card numbers or bank account details on\n    our servers.\n- category: communication\n  text: Content you ask the AI client to render — a URL, HTML, or Markdown — is sent to our API\npurposes:\n- purpose: Service provision\n  text: Service provision — Processing API requests and delivering screenshots\n- purpose: Billing\n  text: Billing — Tracking API usage for accurate invoicing and plan-cap enforcement\n- purpose: Abuse prevention\n  text: Abuse prevention — Detecting and preventing misuse of the Service\n- purpose: Service improvement\n  text: Service improvement — Analyzing anonymized usage patterns to improve reliability and performance\n- purpose: Customer support\n  text: Customer support — Responding to your requests and debugging issues\n- purpose: Legal compliance\n  text: Legal compliance — Meeting legal obligations and responding to lawful requests\nretention:\n- scope: Account data\n  period: 30 days\n\
  \  text: While account is active, deleted within 30 days of closure\n- scope: API request metadata (detail fields)\n  period: 90 days\n  text: 90 days — target URL, user-agent, referer, country, and ASN are automatically scrubbed after the retention\n    window\n- scope: Async job parameters\n  period: 90 days\n  text: Async job parameters 90 days — redacted capture params are nulled out after the retention window\n- scope: Hosted output in R2\n  period: 30 days\n  text: the stored object is automatically deleted by our storage lifecycle policy within 30 days of creation\n- scope: Signup throttle records\n  period: 30 days\n  text: These throttle records are automatically deleted after 30 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Our sub-processors (listed above) may also process data in various jurisdictions.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: If you are a business customer who requires a Data Processing Addendum\
  \ (DPA) under the GDPR, UK GDPR, or\n    similar laws, we will execute our standard DPA on request\ndeletion:\n  route: Contact legal@rendex.dev to exercise deletion rights\n  text: Deletion / Erasure — Request deletion of your personal data and account\nrights:\n- right: Access / Know\n  text: Access / Know — Request a copy of the personal data we hold about you and information about how it is processed\n- right: Correction / Rectification\n  text: Correction / Rectification — Request correction of inaccurate or incomplete data\n- right: Deletion / Erasure\n  text: Deletion / Erasure — Request deletion of your personal data and account\n- right: Portability\n  text: Portability — Request your data in a machine-readable portable format\n- right: Object / Restrict\n  text: Object / Restrict — Object to or restrict certain processing activities\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal information.\n"
source_yaml_url: https://artifacts.apis.io/rendex-dev/privacy/rendex-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from rendex-dev's own page on 2026-11-10.
synthetic: false
tags:
- Rendering
- Screenshots
- PDF
- Automation
---
