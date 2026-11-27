---
api_specs:
- filename: bowmark-ai-library-api-openapi.yml
  format: yaml
  label: Bowmark AI Library API
  slug: bowmark-ai-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-library-api-openapi.yml
- filename: bowmark-ai-recipes-api-openapi.yml
  format: yaml
  label: Bowmark AI Recipes API
  slug: bowmark-ai-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-recipes-api-openapi.yml
- filename: bowmark-ai-run-api-openapi.yml
  format: yaml
  label: Bowmark AI Run API
  slug: bowmark-ai-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-run-api-openapi.yml
- filename: bowmark-ai-scripts-api-openapi.yml
  format: yaml
  label: Bowmark AI Scripts API
  slug: bowmark-ai-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-scripts-api-openapi.yml
- filename: bowmark-ai-sites-api-openapi.yml
  format: yaml
  label: Bowmark AI Sites API
  slug: bowmark-ai-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bowmark-ai/openapi/bowmark-ai-sites-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information (via our authentication provider, Clerk): your name, email address, and authentication identifiers when you sign up or sign in.'
  - category: financial
    text: We retain limited billing records — such as your Stripe customer and subscription identifiers, your plan and subscription status, the billing period, and the email associated with billing.
  - category: behavioral
    text: 'Usage and session information. We record how the Service is used, including: the requests you make to the Service, timestamps, error events, performance and diagnostic telemetry, and account/session identifiers.'
  - category: communication
    text: Communications. If you contact us, we keep the content of your messages and our responses.
  - category: device
    text: your browser's user-agent string
  - category: location
    text: Our public marketing website uses a third-party visitor-analytics tool that may collect site visitors' IP addresses
  deletion:
    route: email privacy@bowmark.ai
    text: When you ask us to delete your account or your information (contact privacy@bowmark.ai ), we delete or de-identify it within 90 days of your request, except records we are required to keep longer for legal, tax, or dispute-resolution purposes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, operate, secure, and improve the Service
    text: provide, operate, secure, and improve the Service
  - purpose: authenticate users and manage accounts
    text: authenticate users and manage accounts
  - purpose: process payments and manage subscriptions
    text: process payments and manage subscriptions
  - purpose: prevent fraud and abuse
    text: prevent fraud and abuse
  - purpose: communicate with you about the Service
    text: communicate with you about the Service
  residency:
  - region: Canada
    text: we and our providers may process personal information outside your province and outside Canada
  retention:
  - period: 90 days
    scope: Account information
    text: When you ask us to delete your account or your information (contact privacy@bowmark.ai ), we delete or de-identify it within 90 days of your request
  - period: up to 30 days
    scope: Diagnostic and performance telemetry
    text: Diagnostic and performance telemetry (traces and logs in our self-hosted SigNoz) — automatically deleted after up to 30 days .
  - period: up to 60 days
    scope: Database backups
    text: Backups — database backups are retained for up to 60 days
  - period: at least six (6) years
    scope: Billing records
    text: Billing records (such as invoices, transaction and subscription identifiers, and billing status held by us; full payment details are held by Stripe) — retained for at least six (6) years , as required by Canadian tax law.
  - period: up to 24 months
    scope: Support communications
    text: Support communications — retained for up to 24 months .
  - period: null
    scope: Run records
    text: We do not currently delete these on a fixed schedule
  rights:
  - right: access
    text: access the personal information we hold about you
  - right: correct
    text: correct inaccurate information
  - right: delete
    text: delete information
  - right: withdraw consent
    text: withdraw consent
  - right: port
    text: where applicable, port information
  role:
    text: Bowmark AI Inc. (" Bowmark ", " we ", " us ")
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your account information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where personal information is transferred across borders we take steps required by applicable law (such as appropriate contractual safeguards)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bowmark AI
provenance_date: '2026-11-09'
provider_name: Bowmark AI
provider_slug: bowmark-ai
slug: bowmark-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bowmark-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bowmark.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bowmark AI\naid: bowmark-ai\nurl: https://bowmark.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Bowmark AI Inc. (\" Bowmark \", \" we \", \" us \")\ndata_categories:\n- category: identifying\n  text: 'Account information (via our authentication provider, Clerk): your name, email address, and authentication\n    identifiers when you sign up or sign in.'\n- category: financial\n  text: We retain limited billing records — such as your Stripe customer and subscription identifiers, your plan\n    and subscription status, the billing period, and the email associated with billing.\n-\
  \ category: behavioral\n  text: 'Usage and session information. We record how the Service is used, including: the requests you make to the\n    Service, timestamps, error events, performance and diagnostic telemetry, and account/session identifiers.'\n- category: communication\n  text: Communications. If you contact us, we keep the content of your messages and our responses.\n- category: device\n  text: your browser's user-agent string\n- category: location\n  text: Our public marketing website uses a third-party visitor-analytics tool that may collect site visitors' IP\n    addresses\npurposes:\n- purpose: provide, operate, secure, and improve the Service\n  text: provide, operate, secure, and improve the Service\n- purpose: authenticate users and manage accounts\n  text: authenticate users and manage accounts\n- purpose: process payments and manage subscriptions\n  text: process payments and manage subscriptions\n- purpose: prevent fraud and abuse\n  text: prevent fraud and abuse\n-\
  \ purpose: communicate with you about the Service\n  text: communicate with you about the Service\nretention:\n- scope: Account information\n  period: 90 days\n  text: When you ask us to delete your account or your information (contact privacy@bowmark.ai ), we delete or de-identify\n    it within 90 days of your request\n- scope: Diagnostic and performance telemetry\n  period: up to 30 days\n  text: Diagnostic and performance telemetry (traces and logs in our self-hosted SigNoz) — automatically deleted\n    after up to 30 days .\n- scope: Database backups\n  period: up to 60 days\n  text: Backups — database backups are retained for up to 60 days\n- scope: Billing records\n  period: at least six (6) years\n  text: Billing records (such as invoices, transaction and subscription identifiers, and billing status held by\n    us; full payment details are held by Stripe) — retained for at least six (6) years , as required by Canadian\n    tax law.\n- scope: Support communications\n  period: up\
  \ to 24 months\n  text: Support communications — retained for up to 24 months .\n- scope: Run records\n  period: null\n  text: We do not currently delete these on a fixed schedule\nresidency:\n- region: Canada\n  text: we and our providers may process personal information outside your province and outside Canada\ntransfers:\n- mechanism: other\n  text: Where personal information is transferred across borders we take steps required by applicable law (such\n    as appropriate contractual safeguards)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@bowmark.ai\n  text: When you ask us to delete your account or your information (contact privacy@bowmark.ai ), we delete or de-identify\n    it within 90 days of your request, except records we are required to keep longer for legal, tax, or dispute-resolution\n    purposes.\nrights:\n- right: access\n  text: access the personal information we hold about you\n- right:\
  \ correct\n  text: correct inaccurate information\n- right: delete\n  text: delete information\n- right: withdraw consent\n  text: withdraw consent\n- right: port\n  text: where applicable, port information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your account information.\n"
source_yaml_url: https://artifacts.apis.io/bowmark-ai/privacy/bowmark-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Bowmark AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Web
- Data Extraction
- Platform
- Company
---
