---
api_specs:
- filename: groundmail-dev-automations-api-openapi.yml
  format: yaml
  label: groundmail-dev Automations API
  slug: groundmail-dev-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-automations-api-openapi.yml
- filename: groundmail-dev-deliverability-api-openapi.yml
  format: yaml
  label: groundmail-dev Deliverability API
  slug: groundmail-dev-deliverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-deliverability-api-openapi.yml
- filename: groundmail-dev-dmarc-api-openapi.yml
  format: yaml
  label: groundmail-dev Dmarc API
  slug: groundmail-dev-dmarc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-dmarc-api-openapi.yml
- filename: groundmail-dev-domains-api-openapi.yml
  format: yaml
  label: groundmail-dev Domains API
  slug: groundmail-dev-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-domains-api-openapi.yml
- filename: groundmail-dev-emails-api-openapi.yml
  format: yaml
  label: groundmail-dev Emails API
  slug: groundmail-dev-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-emails-api-openapi.yml
- filename: groundmail-dev-events-api-openapi.yml
  format: yaml
  label: groundmail-dev Events API
  slug: groundmail-dev-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-events-api-openapi.yml
- filename: groundmail-dev-inbound-api-openapi.yml
  format: yaml
  label: groundmail-dev Inbound API
  slug: groundmail-dev-inbound-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-inbound-api-openapi.yml
- filename: groundmail-dev-integrations-api-openapi.yml
  format: yaml
  label: groundmail-dev Integrations API
  slug: groundmail-dev-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-integrations-api-openapi.yml
- filename: groundmail-dev-migrations-api-openapi.yml
  format: yaml
  label: groundmail-dev Migrations API
  slug: groundmail-dev-migrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-migrations-api-openapi.yml
- filename: groundmail-dev-oauth-api-openapi.yml
  format: yaml
  label: groundmail-dev OAuth API
  slug: groundmail-dev-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-oauth-api-openapi.yml
- filename: groundmail-dev-smtpcredentials-api-openapi.yml
  format: yaml
  label: groundmail-dev Smtp Credentials API
  slug: groundmail-dev-smtpcredentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-smtpcredentials-api-openapi.yml
- filename: groundmail-dev-suppressions-api-openapi.yml
  format: yaml
  label: groundmail-dev Suppressions API
  slug: groundmail-dev-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-suppressions-api-openapi.yml
- filename: groundmail-dev-templates-api-openapi.yml
  format: yaml
  label: groundmail-dev Templates API
  slug: groundmail-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-templates-api-openapi.yml
- filename: groundmail-dev-tenants-api-openapi.yml
  format: yaml
  label: groundmail-dev Tenants API
  slug: groundmail-dev-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-tenants-api-openapi.yml
- filename: groundmail-dev-test-inbox-api-openapi.yml
  format: yaml
  label: groundmail-dev Test inbox API
  slug: groundmail-dev-test-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-test-inbox-api-openapi.yml
- filename: groundmail-dev-validation-api-openapi.yml
  format: yaml
  label: groundmail-dev Validation API
  slug: groundmail-dev-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-validation-api-openapi.yml
- filename: groundmail-dev-webhooks-api-openapi.yml
  format: yaml
  label: groundmail-dev Webhooks API
  slug: groundmail-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-webhooks-api-openapi.yml
- filename: groundmail-dev-api-keys-api-openapi.yml
  format: yaml
  label: groundmail-dev API Keys API
  slug: groundmail-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/groundmail-dev/openapi/groundmail-dev-api-keys-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : name, email address, company name, login credentials (stored hashed), and session tokens.'
  - category: financial
    text: 'Billing data : subscription status, invoices, and payment metadata processed by Stripe (we do not store full card numbers).'
  - category: device
    text: 'Technical data : IP address, browser type, device information, activity logs, and product analytics events (for example signups, billing actions, and feature usage).'
  - category: communication
    text: 'Message data : email content, recipients, delivery events, suppressions, and inbound messages you route through the Service.'
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Our Data Processing Agreement ( groundmail.dev/legal/dpa/ ) applies when you use the Service, with nothing to sign.
    url: groundmail.dev/legal/dpa/
  purposes:
  - purpose: Operate accounts and billing
    text: Operate accounts, domains, API keys, templates, webhooks, and billing.
  - purpose: Abuse monitoring
    text: Monitor abuse, enforce limits, and protect shared infrastructure reputation.
  - purpose: Product analytics
    text: Measure product usage and improve onboarding, reliability, and feature development through analytics.
  residency:
  - region: United States and other provider regions
    text: Customer data is processed in the United States and in other regions where our providers operate.
  retention:
  - period: null
    scope: Active accounts
    text: 'Active accounts : retained while your account is active and as needed to provide the Service.'
  - period: null
    scope: Deleted accounts
    text: 'Deleted accounts : account data is deleted or anonymized within a reasonable period after deletion request, subject to legal retention requirements.'
  - period: 30 days
    scope: BurrowGuard data
    text: We keep the IP address, browser details, email domain and a one-way hash of the email for 30 days.
  - period: two years
    scope: gm_did cookie
    text: a strictly necessary security cookie ( gm_did ) keeps a random identifier for your browser for up to two years.
  - period: 180 days
    scope: Sign-up and sign-in security records
    text: We store it, your IP address and your browser type with each sign-up and sign-in for 180 days
  rights:
  - right: access, correct, delete, restrict, object, port
    text: Depending on your location, you may have rights to access, correct, delete, restrict, object to, or port your personal data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The providers that process your customer data, what each does and where, are listed at groundmail.dev/legal/subprocessors/ .
    url: groundmail.dev/legal/subprocessors/
  transfers:
  - mechanism: SCC
    text: our Data Processing Agreement includes the EU Standard Contractual Clauses, the UK International Data Transfer Addendum and the Swiss amendments.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: groundmail-dev
provenance_date: '2026-11-09'
provider_name: groundmail-dev
provider_slug: groundmail-dev
slug: groundmail-dev-privacy-policy
source_date: '2026-11-09'
source_filename: groundmail-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://groundmail.dev/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: groundmail-dev\naid: groundmail-dev\nurl: https://groundmail.dev/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data : name, email address, company name, login credentials (stored hashed), and session tokens.'\n- category: financial\n  text: 'Billing data : subscription status, invoices, and payment metadata processed by Stripe (we do not store\n    full card numbers).'\n- category: device\n  text: 'Technical data : IP address, browser type, device information, activity logs, and product analytics events\n    (for\
  \ example signups, billing actions, and feature usage).'\n- category: communication\n  text: 'Message data : email content, recipients, delivery events, suppressions, and inbound messages you route\n    through the Service.'\npurposes:\n- purpose: Operate accounts and billing\n  text: Operate accounts, domains, API keys, templates, webhooks, and billing.\n- purpose: Abuse monitoring\n  text: Monitor abuse, enforce limits, and protect shared infrastructure reputation.\n- purpose: Product analytics\n  text: Measure product usage and improve onboarding, reliability, and feature development through analytics.\nretention:\n- scope: Active accounts\n  period: null\n  text: 'Active accounts : retained while your account is active and as needed to provide the Service.'\n- scope: Deleted accounts\n  period: null\n  text: 'Deleted accounts : account data is deleted or anonymized within a reasonable period after deletion request,\n    subject to legal retention requirements.'\n- scope: BurrowGuard\
  \ data\n  period: 30 days\n  text: We keep the IP address, browser details, email domain and a one-way hash of the email for 30 days.\n- scope: gm_did cookie\n  period: two years\n  text: a strictly necessary security cookie ( gm_did ) keeps a random identifier for your browser for up to two\n    years.\n- scope: Sign-up and sign-in security records\n  period: 180 days\n  text: We store it, your IP address and your browser type with each sign-up and sign-in for 180 days\nresidency:\n- region: United States and other provider regions\n  text: Customer data is processed in the United States and in other regions where our providers operate.\ntransfers:\n- mechanism: SCC\n  text: our Data Processing Agreement includes the EU Standard Contractual Clauses, the UK International Data Transfer\n    Addendum and the Swiss amendments.\nsubprocessors:\n  url: groundmail.dev/legal/subprocessors/\n  text: The providers that process your customer data, what each does and where, are listed at groundmail.dev/legal/subprocessors/\n\
  \    .\ndpa:\n  available: true\n  url: groundmail.dev/legal/dpa/\n  text: Our Data Processing Agreement ( groundmail.dev/legal/dpa/ ) applies when you use the Service, with nothing\n    to sign.\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correct, delete, restrict, object, port\n  text: Depending on your location, you may have rights to access, correct, delete, restrict, object to, or port\n    your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/groundmail-dev/privacy/groundmail-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- rights
summary_line: 17 quoted statements, read from groundmail-dev's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Transactional
- SMTP
- Developers
---
