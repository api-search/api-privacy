---
api_specs:
- filename: fastballapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: fastballapi-com Basic lookup API
  slug: fastballapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-basic-lookup-api-openapi.yml
- filename: fastballapi-com-multi-table-api-openapi.yml
  format: yaml
  label: fastballapi-com Multi Table API
  slug: fastballapi-com-multi-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-multi-table-api-openapi.yml
- filename: fastballapi-com-static-reference-api-openapi.yml
  format: yaml
  label: fastballapi-com Static reference API
  slug: fastballapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-static-reference-api-openapi.yml
- filename: fastballapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: fastballapi-com Stats + aggregation API
  slug: fastballapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-stats-aggregation-api-openapi.yml
- filename: fastballapi-com-time-series-api-openapi.yml
  format: yaml
  label: fastballapi-com Time Series API
  slug: fastballapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastballapi-com/openapi/fastballapi-com-time-series-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email, name, a hashed password, whether you verified your email, when you accepted our terms and which version, and your Stripe customer ID.'
  - category: device
    text: 'API and tool calls: the tool and the arguments you sent, time, credits charged, result status and row count, league, request ID, IP address and user agent.'
  - category: financial
    text: 'Payments: Stripe collects your card details. We receive your customer ID, plan, amount, date, card brand and last four digits, and status.'
  - category: behavioral
    text: 'Website analytics: Google Analytics 4 counts pages, device and browser, approximate location and referrer.'
  - category: communication
    text: 'Emails: a record of emails we send you and anything you send to support.'
  - category: health
    text: We do not collect health data, precise location, government IDs or data about children.
  deletion:
    route: Email support@fastballapi.com or delete account in dashboard
    text: When you ask us to delete your account, we delete or anonymize your account data within 30 days, except billing records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run your account, issue keys, authenticate you and your apps
    text: Run your account, issue keys, authenticate you and your apps
  - purpose: Count and bill credits, take payments
    text: Count and bill credits, take payments, send receipts, refunds
  - purpose: Stopping abuse, fraud, key sharing and attacks
    text: Stopping abuse, fraud, key sharing and attacks
  - purpose: Measuring website use
    text: Measuring website use
  residency:
  - region: United States
    text: We are in the United States, and so are our providers' main systems.
  retention:
  - period: 90 days
    scope: IP address and user agent (calls, sessions, failed attempts)
    text: IP address and user agent (calls, sessions, failed attempts) 90 days, then deleted
  - period: 7 years
    scope: Billing and tax records
    text: Billing and tax records 7 years
  - period: While your account is open, plus 30 days
    scope: Account data and attribution record
    text: Account data and attribution record While your account is open, plus 30 days
  - period: 90 days
    scope: First-touch cookie
    text: First-touch cookie 90 days in your browser
  rights:
  - right: access
    text: You can ask us, free of charge, to give you a copy of your data
  - right: rectification
    text: fix it
  - right: erasure
    text: delete it
  - right: restriction
    text: limit its use
  - right: objection
    text: object to uses based on legitimate interests
  - right: portability
    text: send it to you in a machine-readable format
  role:
    text: OWSH Unlimited LLC, a New York limited liability company based in Buffalo, New York, USA, controls your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or share it for cross-context behavioral advertising, and have not in the past 12 months.
  subprocessors:
    text: 'We share it only with these service providers, who act on our instructions: Provider What they do Data Stripe Payments, invoices, fraud checks Payment and billing data, name, email'
    url: null
  transfers:
  - mechanism: DPF
    text: your data goes to the U.S. under the EU-U.S. Data Privacy Framework for providers certified under it
  - mechanism: SCC
    text: otherwise under the European Commission's Standard Contractual Clauses and the UK addendum in our providers' terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fastballapi-com
provenance_date: '2026-11-09'
provider_name: fastballapi-com
provider_slug: fastballapi-com
slug: fastballapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: fastballapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fastballapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fastballapi-com\naid: fastballapi-com\nurl: https://fastballapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: OWSH Unlimited LLC, a New York limited liability company based in Buffalo, New York, USA, controls your\n    personal data.\ndata_categories:\n- category: identifying\n  text: 'Account data: email, name, a hashed password, whether you verified your email, when you accepted our terms\n    and which version, and your Stripe customer ID.'\n- category: device\n  text: 'API and tool calls: the tool and the arguments you sent, time, credits charged, result status and row count,\n\
  \    league, request ID, IP address and user agent.'\n- category: financial\n  text: 'Payments: Stripe collects your card details. We receive your customer ID, plan, amount, date, card brand\n    and last four digits, and status.'\n- category: behavioral\n  text: 'Website analytics: Google Analytics 4 counts pages, device and browser, approximate location and referrer.'\n- category: communication\n  text: 'Emails: a record of emails we send you and anything you send to support.'\n- category: health\n  text: We do not collect health data, precise location, government IDs or data about children.\npurposes:\n- purpose: Run your account, issue keys, authenticate you and your apps\n  text: Run your account, issue keys, authenticate you and your apps\n- purpose: Count and bill credits, take payments\n  text: Count and bill credits, take payments, send receipts, refunds\n- purpose: Stopping abuse, fraud, key sharing and attacks\n  text: Stopping abuse, fraud, key sharing and attacks\n- purpose:\
  \ Measuring website use\n  text: Measuring website use\nretention:\n- scope: IP address and user agent (calls, sessions, failed attempts)\n  period: 90 days\n  text: IP address and user agent (calls, sessions, failed attempts) 90 days, then deleted\n- scope: Billing and tax records\n  period: 7 years\n  text: Billing and tax records 7 years\n- scope: Account data and attribution record\n  period: While your account is open, plus 30 days\n  text: Account data and attribution record While your account is open, plus 30 days\n- scope: First-touch cookie\n  period: 90 days\n  text: First-touch cookie 90 days in your browser\nresidency:\n- region: United States\n  text: We are in the United States, and so are our providers' main systems.\ntransfers:\n- mechanism: DPF\n  text: your data goes to the U.S. under the EU-U.S. Data Privacy Framework for providers certified under it\n- mechanism: SCC\n  text: otherwise under the European Commission's Standard Contractual Clauses and the UK addendum\
  \ in our providers'\n    terms.\nsubprocessors:\n  url: null\n  text: 'We share it only with these service providers, who act on our instructions: Provider What they do Data\n    Stripe Payments, invoices, fraud checks Payment and billing data, name, email'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@fastballapi.com or delete account in dashboard\n  text: When you ask us to delete your account, we delete or anonymize your account data within 30 days, except\n    billing records.\nrights:\n- right: access\n  text: You can ask us, free of charge, to give you a copy of your data\n- right: rectification\n  text: fix it\n- right: erasure\n  text: delete it\n- right: restriction\n  text: limit its use\n- right: objection\n  text: object to uses based on legitimate interests\n- right: portability\n  text: send it to you in a machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or share it for\
  \ cross-context behavioral advertising, and have\n    not in the past 12 months.\n"
source_yaml_url: https://artifacts.apis.io/fastballapi-com/privacy/fastballapi-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from fastballapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Baseball
- Sports
- Data
- MLB
---
