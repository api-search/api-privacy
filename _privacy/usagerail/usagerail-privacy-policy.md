---
api_specs:
- filename: usagerail-openapi-generated.yml
  format: yaml
  label: UsageRail API
  slug: usagerail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usagerail/openapi/_ae-authored/usagerail-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: we store their email addresses
  - category: identifying
    text: Your email address.
  - category: financial
    text: Your card details go to Stripe, not to us; we keep your plan, its status and its billing dates.
  - category: device
    text: Our servers see the IP address of each request.
  deletion:
    route: email support@usagerail.com
    text: Email support@usagerail.com from your account's address to see what we hold, correct it or delete it.
  dpa:
    available: true
    text: If you need a data processing agreement for your customers' data, email support@usagerail.com .
    url: null
  purposes:
  - purpose: Run UsageRail
    text: 'To run UsageRail: signing you and your customers in, enforcing keys and limits, showing usage, and sending the emails the service needs, such as sign-in codes and quota alerts.'
  - purpose: Marketing
    text: we don't use your customers' data to market to them.
  residency:
  - region: United States
    text: Tencent Cloud runs our servers and database in Ashburn, Virginia, in the United States.
  retention:
  - period: while your account is open
    scope: Account data
    text: Account data stays while your account is open.
  - period: 45 days
    scope: Minute-level usage
    text: We keep minute-level usage for 45 days.
  - period: 7 days
    scope: Hourly usage on Free
    text: Hourly usage is kept for 7 days on Free, 30 on Starter, 90 on Growth and 365 on Scale.
  - period: 13 months
    scope: Billing-period usage totals and change log
    text: Usage totals for each billing period and the log of changes in your account are kept for 13 months.
  - period: 30 days
    scope: Webhook events and email records
    text: Webhook events, delivery records and records of the emails we send are kept for 30 days.
  rights:
  - right: Access
    text: see what we hold
  - right: Correction
    text: correct it
  - right: Deletion
    text: delete it
  - right: Complaint to authority
    text: you can also complain to your local data protection authority.
  role:
    text: For this data you decide what happens to it, and we process it on your behalf.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or rent any of this data, and we don't use your customers' data to market to them.
  subprocessors:
    text: Vercel hosts the website, the console and the portals, and runs Web Analytics.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UsageRail
provenance_date: '2026-11-10'
provider_name: UsageRail
provider_slug: usagerail
slug: usagerail-privacy-policy
source_date: '2026-11-10'
source_filename: usagerail-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://usagerail.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UsageRail\naid: usagerail\nurl: https://usagerail.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: For this data you decide what happens to it, and we process it on your behalf.\ndata_categories:\n- category: contact\n  text: we store their email addresses\n- category: identifying\n  text: Your email address.\n- category: financial\n  text: Your card details go to Stripe, not to us; we keep your plan, its status and its billing dates.\n- category: device\n  text: Our servers see the IP address of each request.\npurposes:\n- purpose: Run UsageRail\n  text: 'To run UsageRail: signing\
  \ you and your customers in, enforcing keys and limits, showing usage, and sending\n    the emails the service needs, such as sign-in codes and quota alerts.'\n- purpose: Marketing\n  text: we don't use your customers' data to market to them.\nretention:\n- scope: Account data\n  period: while your account is open\n  text: Account data stays while your account is open.\n- scope: Minute-level usage\n  period: 45 days\n  text: We keep minute-level usage for 45 days.\n- scope: Hourly usage on Free\n  period: 7 days\n  text: Hourly usage is kept for 7 days on Free, 30 on Starter, 90 on Growth and 365 on Scale.\n- scope: Billing-period usage totals and change log\n  period: 13 months\n  text: Usage totals for each billing period and the log of changes in your account are kept for 13 months.\n- scope: Webhook events and email records\n  period: 30 days\n  text: Webhook events, delivery records and records of the emails we send are kept for 30 days.\nresidency:\n- region: United States\n  text:\
  \ Tencent Cloud runs our servers and database in Ashburn, Virginia, in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Vercel hosts the website, the console and the portals, and runs Web Analytics.\ndpa:\n  available: true\n  url: null\n  text: If you need a data processing agreement for your customers' data, email support@usagerail.com .\ndeletion:\n  route: email support@usagerail.com\n  text: Email support@usagerail.com from your account's address to see what we hold, correct it or delete it.\nrights:\n- right: Access\n  text: see what we hold\n- right: Correction\n  text: correct it\n- right: Deletion\n  text: delete it\n- right: Complaint to authority\n  text: you can also complain to your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or rent any of this data, and we don't use your customers' data to market to them.\n"
source_yaml_url: https://artifacts.apis.io/usagerail/privacy/usagerail-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from UsageRail's own page on 2026-11-10.
synthetic: false
tags:
- Company
- API Monetization
- Software-as-a-Service
- Billing
- Rate Limiting
- Developer Tools
---
