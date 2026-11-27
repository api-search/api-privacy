---
api_specs:
- filename: auxen-ai-billing-api-openapi.yml
  format: yaml
  label: Auxen Billing API
  slug: auxen-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-billing-api-openapi.yml
- filename: auxen-ai-deployments-api-openapi.yml
  format: yaml
  label: Auxen Deployments API
  slug: auxen-ai-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-deployments-api-openapi.yml
- filename: auxen-ai-deprecated-api-openapi.yml
  format: yaml
  label: Auxen Deprecated API
  slug: auxen-ai-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-deprecated-api-openapi.yml
- filename: auxen-ai-inference-api-openapi.yml
  format: yaml
  label: Auxen Inference API
  slug: auxen-ai-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-inference-api-openapi.yml
- filename: auxen-ai-models-api-openapi.yml
  format: yaml
  label: Auxen Models API
  slug: auxen-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-models-api-openapi.yml
- filename: auxen-ai-pay-with-usdc-api-openapi.yml
  format: yaml
  label: Auxen Pay with USDC API
  slug: auxen-ai-pay-with-usdc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-pay-with-usdc-api-openapi.yml
- filename: auxen-ai-scheduling-api-openapi.yml
  format: yaml
  label: Auxen Scheduling API
  slug: auxen-ai-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-scheduling-api-openapi.yml
- filename: auxen-ai-webhooks-api-openapi.yml
  format: yaml
  label: Auxen Webhooks API
  slug: auxen-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-webhooks-api-openapi.yml
- filename: auxen-ai-workers-api-openapi.yml
  format: yaml
  label: Auxen Workers API
  slug: auxen-ai-workers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auxen-ai/openapi/auxen-ai-workers-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (used for sign-in via one-time code).
  - category: contact
    text: Email address (used for sign-in via one-time code).
  - category: financial
    text: Prepaid USD credit balance, top-up history, and saved payment method, processed by Stripe
  - category: communication
    text: Chat messages sent to your private endpoint.
  - category: behavioral
    text: Minimal analytics on the marketing site (page views, referrer).
  - category: other
    text: Server logs (timestamps, request paths, deployment IDs, redacted error messages)
  deletion:
    route: Dashboard for documents and conversations; email for full account deletion
    text: Delete your account and all associated data — email [email protected] and we will action it within [ RETENTION RESPONSE WINDOW, e.g. 7 business days ]
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: To provide and operate the Auxen service.
  - purpose: Billing
    text: To bill you and honor your plan.
  - purpose: Customer support
    text: To provide customer support when you ask.
  - purpose: Security
    text: To secure the service (detect abuse, prevent fraud, investigate incidents).
  residency:
  - region: United States
    text: Auxen operates from the United States.
  retention:
  - period: while your account is active
    scope: Account data
    text: Account data is retained while your account is active.
  - period: '[ ERASE WINDOW, e.g. 30 days ]'
    scope: Account data after deletion
    text: On deletion, we erase account data and associated uploaded content within [ ERASE WINDOW, e.g. 30 days ] .
  - period: '[ RETENTION DAYS, e.g. 30 ] days'
    scope: Operational logs
    text: Operational logs are retained for [ RETENTION DAYS, e.g. 30 ] days then purged.
  - period: '[ TAX RETENTION YEARS, e.g. 7 ] years'
    scope: Billing records
    text: Billing records are retained for [ TAX RETENTION YEARS, e.g. 7 ] years for tax/audit compliance.
  rights:
  - right: Access
    text: Access the data we hold about you (Settings).
  - right: Delete uploaded documents
    text: Delete your uploaded documents (Knowledge Base → remove).
  - right: EU/UK rights under GDPR
    text: Residents of the EU/UK have additional rights under GDPR
  - right: California rights under CCPA/CPRA
    text: residents of California have additional rights under the CCPA/CPRA.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your data with advertisers.
  subprocessors:
    text: Stripe — payment processing.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Auxen
provenance_date: '2026-11-09'
provider_name: Auxen
provider_slug: auxen-ai
slug: auxen-ai-privacy-policy
source_date: '2026-11-09'
source_filename: auxen-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://auxen.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Auxen\naid: auxen-ai\nurl: https://auxen.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (used for sign-in via one-time code).\n- category: contact\n  text: Email address (used for sign-in via one-time code).\n- category: financial\n  text: Prepaid USD credit balance, top-up history, and saved payment method, processed by Stripe\n- category: communication\n  text: Chat messages sent to your private endpoint.\n- category: behavioral\n  text: Minimal analytics on the marketing site (page views, referrer).\n- category:\
  \ other\n  text: Server logs (timestamps, request paths, deployment IDs, redacted error messages)\npurposes:\n- purpose: Provide and operate the service\n  text: To provide and operate the Auxen service.\n- purpose: Billing\n  text: To bill you and honor your plan.\n- purpose: Customer support\n  text: To provide customer support when you ask.\n- purpose: Security\n  text: To secure the service (detect abuse, prevent fraud, investigate incidents).\nretention:\n- scope: Account data\n  period: while your account is active\n  text: Account data is retained while your account is active.\n- scope: Account data after deletion\n  period: '[ ERASE WINDOW, e.g. 30 days ]'\n  text: On deletion, we erase account data and associated uploaded content within [ ERASE WINDOW, e.g. 30 days ]\n    .\n- scope: Operational logs\n  period: '[ RETENTION DAYS, e.g. 30 ] days'\n  text: Operational logs are retained for [ RETENTION DAYS, e.g. 30 ] days then purged.\n- scope: Billing records\n  period: '[ TAX\
  \ RETENTION YEARS, e.g. 7 ] years'\n  text: Billing records are retained for [ TAX RETENTION YEARS, e.g. 7 ] years for tax/audit compliance.\nresidency:\n- region: United States\n  text: Auxen operates from the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe — payment processing.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement\ndeletion:\n  route: Dashboard for documents and conversations; email for full account deletion\n  text: Delete your account and all associated data — email [email protected] and we will action it within [ RETENTION\n    RESPONSE WINDOW, e.g. 7 business days ]\nrights:\n- right: Access\n  text: Access the data we hold about you (Settings).\n- right: Delete uploaded documents\n  text: Delete your uploaded documents (Knowledge Base → remove).\n- right: EU/UK rights under GDPR\n  text: Residents of the EU/UK have additional rights under GDPR\n- right: California rights under CCPA/CPRA\n  text: residents of California\
  \ have additional rights under the CCPA/CPRA.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/auxen-ai/privacy/auxen-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Auxen's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Platform
- Workers
- Productivity
---
