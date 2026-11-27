---
api_specs:
- filename: endzoneapi-com-basic-lookup-api-openapi.yml
  format: yaml
  label: endzoneapi-com Basic lookup API
  slug: endzoneapi-com-basic-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-basic-lookup-api-openapi.yml
- filename: endzoneapi-com-multi-table-api-openapi.yml
  format: yaml
  label: endzoneapi-com Multi Table API
  slug: endzoneapi-com-multi-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-multi-table-api-openapi.yml
- filename: endzoneapi-com-static-reference-api-openapi.yml
  format: yaml
  label: endzoneapi-com Static reference API
  slug: endzoneapi-com-static-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-static-reference-api-openapi.yml
- filename: endzoneapi-com-stats-aggregation-api-openapi.yml
  format: yaml
  label: endzoneapi-com Stats + aggregation API
  slug: endzoneapi-com-stats-aggregation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-stats-aggregation-api-openapi.yml
- filename: endzoneapi-com-time-series-api-openapi.yml
  format: yaml
  label: endzoneapi-com Time Series API
  slug: endzoneapi-com-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endzoneapi-com/openapi/endzoneapi-com-time-series-api-openapi.yml
claim_count: 21
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
  deletion:
    route: Request account deletion
    text: When you ask us to delete your account, we delete or anonymize your account data within 30 days, except billing records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account and authenticate
    text: Run your account, issue keys, authenticate you and your apps
  - purpose: Billing and credits
    text: Count and bill credits, take payments, send receipts, refunds
  - purpose: Stopping abuse
    text: Stopping abuse, fraud, key sharing and attacks
  - purpose: Measuring website use
    text: Measuring website use Google Analytics Legitimate interests, outside the EU, EEA, UK and Switzerland only
  residency:
  - region: United States
    text: We are in the United States, and so are our providers' main systems.
  retention:
  - period: 90 days
    scope: IP address and user agent
    text: IP address and user agent (calls, sessions, failed attempts) 90 days, then deleted
  - period: While your account is open, plus 30 days
    scope: Account data and attribution record
    text: Account data and attribution record While your account is open, plus 30 days
  - period: 7 years
    scope: Billing and tax records
    text: Billing and tax records 7 years
  - period: 90 days
    scope: First-touch cookie
    text: First-touch cookie 90 days in your browser
  rights:
  - right: Access and copy
    text: You can ask us, free of charge, to give you a copy of your data, fix it, delete it, limit its use, object to uses based on legitimate interests, or send it to you in a machine-readable format.
  - right: Complain to authority
    text: In the EU or EEA you can complain to your data protection authority, in the UK to the Information Commissioner's Office, and in the U.S. to your state attorney general.
  role:
    text: OWSH Unlimited LLC, a New York limited liability company based in Buffalo, New York, USA, controls your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or share it for cross-context behavioral advertising, and have not in the past 12 months.
  subprocessors:
    text: null
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
name: endzoneapi-com
provenance_date: '2026-11-09'
provider_name: endzoneapi-com
provider_slug: endzoneapi-com
slug: endzoneapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: endzoneapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://endzoneapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: endzoneapi-com\naid: endzoneapi-com\nurl: https://endzoneapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: OWSH Unlimited LLC, a New York limited liability company based in Buffalo, New York, USA, controls your\n    personal data.\ndata_categories:\n- category: identifying\n  text: 'Account data: email, name, a hashed password, whether you verified your email, when you accepted our terms\n    and which version, and your Stripe customer ID.'\n- category: device\n  text: 'API and tool calls: the tool and the arguments you sent, time, credits charged, result status and row count,\n\
  \    league, request ID, IP address and user agent.'\n- category: financial\n  text: 'Payments: Stripe collects your card details. We receive your customer ID, plan, amount, date, card brand\n    and last four digits, and status.'\n- category: behavioral\n  text: 'Website analytics: Google Analytics 4 counts pages, device and browser, approximate location and referrer.'\n- category: communication\n  text: 'Emails: a record of emails we send you and anything you send to support.'\npurposes:\n- purpose: Run account and authenticate\n  text: Run your account, issue keys, authenticate you and your apps\n- purpose: Billing and credits\n  text: Count and bill credits, take payments, send receipts, refunds\n- purpose: Stopping abuse\n  text: Stopping abuse, fraud, key sharing and attacks\n- purpose: Measuring website use\n  text: Measuring website use Google Analytics Legitimate interests, outside the EU, EEA, UK and Switzerland only\nretention:\n- scope: IP address and user agent\n  period:\
  \ 90 days\n  text: IP address and user agent (calls, sessions, failed attempts) 90 days, then deleted\n- scope: Account data and attribution record\n  period: While your account is open, plus 30 days\n  text: Account data and attribution record While your account is open, plus 30 days\n- scope: Billing and tax records\n  period: 7 years\n  text: Billing and tax records 7 years\n- scope: First-touch cookie\n  period: 90 days\n  text: First-touch cookie 90 days in your browser\nresidency:\n- region: United States\n  text: We are in the United States, and so are our providers' main systems.\ntransfers:\n- mechanism: DPF\n  text: your data goes to the U.S. under the EU-U.S. Data Privacy Framework for providers certified under it\n- mechanism: SCC\n  text: otherwise under the European Commission's Standard Contractual Clauses and the UK addendum in our providers'\n    terms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request\
  \ account deletion\n  text: When you ask us to delete your account, we delete or anonymize your account data within 30 days, except\n    billing records.\nrights:\n- right: Access and copy\n  text: You can ask us, free of charge, to give you a copy of your data, fix it, delete it, limit its use, object\n    to uses based on legitimate interests, or send it to you in a machine-readable format.\n- right: Complain to authority\n  text: In the EU or EEA you can complain to your data protection authority, in the UK to the Information Commissioner's\n    Office, and in the U.S. to your state attorney general.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or share it for cross-context behavioral advertising, and have\n    not in the past 12 months.\n"
source_yaml_url: https://artifacts.apis.io/endzoneapi-com/privacy/endzoneapi-com-privacy-policy.yml
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
summary_line: 21 quoted statements, read from endzoneapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Football
- NFL
- Data API
- Odds
- MCP
---
