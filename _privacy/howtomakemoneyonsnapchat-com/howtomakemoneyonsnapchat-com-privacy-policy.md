---
api_specs:
- filename: howtomakemoneyonsnapchat-com-calculations-api-openapi.yml
  format: yaml
  label: howtomakemoneyonsnapchat-com Calculations API
  slug: howtomakemoneyonsnapchat-com-calculations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtomakemoneyonsnapchat-com/openapi/howtomakemoneyonsnapchat-com-calculations-api-openapi.yml
- filename: howtomakemoneyonsnapchat-com-facts-api-openapi.yml
  format: yaml
  label: howtomakemoneyonsnapchat-com Facts API
  slug: howtomakemoneyonsnapchat-com-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtomakemoneyonsnapchat-com/openapi/howtomakemoneyonsnapchat-com-facts-api-openapi.yml
- filename: howtomakemoneyonsnapchat-com-meta-api-openapi.yml
  format: yaml
  label: howtomakemoneyonsnapchat-com Meta API
  slug: howtomakemoneyonsnapchat-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/howtomakemoneyonsnapchat-com/openapi/howtomakemoneyonsnapchat-com-meta-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: 'What we store for an account: your email address;'
  - category: financial
    text: Records we already received (customer id, plan status, country, postal code, and possibly card brand and last four digits)
  - category: location
    text: a two-letter country code from our hosting provider
  deletion:
    route: email request from account address
    text: Email hello@howtomakemoneyonsnapchat.com from the account's address and ask us to delete the account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run Eligibility Watch
    text: 'Only to run your Watch: trends, projected dates, the threshold holding you back, and rule-change alerts.'
  - purpose: rate limits and abuse prevention
    text: We use it for rate limits, abuse prevention, improving the service, and billing (for example, counting calls against a credit pack).
  - purpose: site update emails
    text: We use the address only to send those updates.
  - purpose: page analytics
    text: We use them to see which pages are read and how fast they load.
  residency:
  - region: Cloudflare hosting database
    text: In our database at Cloudflare.
  retention:
  - period: 90 days
    scope: usage log
    text: Raw usage records are deleted after 90 days and only daily totals are kept.
  - period: 24 months
    scope: Watch saved numbers
    text: 'Saved numbers: while your plan is active, up to 24 months back.'
  - period: 12 months
    scope: Watch alerts
    text: 'Alerts: 12 months.'
  - period: 7 years
    scope: billing records
    text: We keep those records for 7 years and then delete them.
  - period: 30 days
    scope: Watch webhook delivery logs
    text: 'Webhook delivery logs: 30 days.'
  - period: about 12 hours
    scope: cached public profile
    text: The cache lifetime is configurable, normally about 12 hours.
  rights:
  - right: export Watch data
    text: You can export your Watch data (JSON or CSV),
  - right: delete Watch data
    text: delete one check-in, one profile, or all of your Watch data
  - right: deletion requests
    text: We will honor deletion requests.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell them or use them for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: howtomakemoneyonsnapchat-com
provenance_date: '2026-11-09'
provider_name: howtomakemoneyonsnapchat-com
provider_slug: howtomakemoneyonsnapchat-com
slug: howtomakemoneyonsnapchat-com-privacy-policy
source_date: '2026-11-09'
source_filename: howtomakemoneyonsnapchat-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://howtomakemoneyonsnapchat.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: howtomakemoneyonsnapchat-com\naid: howtomakemoneyonsnapchat-com\nurl: https://howtomakemoneyonsnapchat.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'What we store for an account: your email address;'\n- category: financial\n  text: Records we already received (customer id, plan status, country, postal code, and possibly card brand and\n    last four digits)\n- category: location\n  text: a two-letter country code from our hosting provider\npurposes:\n- purpose: run Eligibility Watch\n  text: 'Only to run your Watch: trends, projected\
  \ dates, the threshold holding you back, and rule-change alerts.'\n- purpose: rate limits and abuse prevention\n  text: We use it for rate limits, abuse prevention, improving the service, and billing (for example, counting calls\n    against a credit pack).\n- purpose: site update emails\n  text: We use the address only to send those updates.\n- purpose: page analytics\n  text: We use them to see which pages are read and how fast they load.\nretention:\n- scope: usage log\n  period: 90 days\n  text: Raw usage records are deleted after 90 days and only daily totals are kept.\n- scope: Watch saved numbers\n  period: 24 months\n  text: 'Saved numbers: while your plan is active, up to 24 months back.'\n- scope: Watch alerts\n  period: 12 months\n  text: 'Alerts: 12 months.'\n- scope: billing records\n  period: 7 years\n  text: We keep those records for 7 years and then delete them.\n- scope: Watch webhook delivery logs\n  period: 30 days\n  text: 'Webhook delivery logs: 30 days.'\n- scope:\
  \ cached public profile\n  period: about 12 hours\n  text: The cache lifetime is configurable, normally about 12 hours.\nresidency:\n- region: Cloudflare hosting database\n  text: In our database at Cloudflare.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request from account address\n  text: Email hello@howtomakemoneyonsnapchat.com from the account's address and ask us to delete the account.\nrights:\n- right: export Watch data\n  text: You can export your Watch data (JSON or CSV),\n- right: delete Watch data\n  text: delete one check-in, one profile, or all of your Watch data\n- right: deletion requests\n  text: We will honor deletion requests.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell them or use them for advertising.\n"
source_yaml_url: https://artifacts.apis.io/howtomakemoneyonsnapchat-com/privacy/howtomakemoneyonsnapchat-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from howtomakemoneyonsnapchat-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Snapchat
- Monetization
- Calculator
- Rules
---
