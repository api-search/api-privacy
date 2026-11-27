---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information Handled entirely by Auth0 (our identity provider).
  - category: financial
    text: Billing information Handled entirely by Polar.sh (our Merchant of Record and payment provider).
  - category: behavioral
    text: API usage data Request counts, timestamps, endpoint paths, response codes, and response times — are tied to your account ID for billing and rate limiting purposes.
  - category: device
    text: We do not log IP addresses, user agents, query parameters, request bodies, or response payloads.
  deletion:
    route: null
    text: 'Account data : Deleted within 30 days of account closure'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing and rate limiting
    text: API usage data Request counts, timestamps, endpoint paths, response codes, and response times — are tied to your account ID for billing and rate limiting purposes.
  - purpose: payments, tax compliance and billing disputes
    text: Polar.sh (our Merchant of Record and payment provider) handles payments, tax compliance, and billing disputes.
  residency:
  - region: EU
    text: Fly.io (our hosting provider) runs our infrastructure in the EU region.
  retention:
  - period: 30 days
    scope: account data
    text: 'Account data : Deleted within 30 days of account closure'
  - period: null
    scope: billing records
    text: 'Billing records : Retained by Polar.sh per their policies'
  - period: null
    scope: usage logs
    text: 'Usage logs : Retained by Polar.sh per their policies'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: World Data API
provenance_date: '2026-11-10'
provider_name: World Data API
provider_slug: worlddataapi
slug: worlddataapi-privacy-policy
source_date: '2026-11-10'
source_filename: worlddataapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://worlddataapi.com/about/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: World Data API\naid: worlddataapi\nurl: https://worlddataapi.com/about/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information Handled entirely by Auth0 (our identity provider).\n- category: financial\n  text: Billing information Handled entirely by Polar.sh (our Merchant of Record and payment provider).\n- category: behavioral\n  text: API usage data Request counts, timestamps, endpoint paths, response codes, and response times — are tied\n    to your account ID for billing and rate limiting purposes.\n- category:\
  \ device\n  text: We do not log IP addresses, user agents, query parameters, request bodies, or response payloads.\npurposes:\n- purpose: billing and rate limiting\n  text: API usage data Request counts, timestamps, endpoint paths, response codes, and response times — are tied\n    to your account ID for billing and rate limiting purposes.\n- purpose: payments, tax compliance and billing disputes\n  text: Polar.sh (our Merchant of Record and payment provider) handles payments, tax compliance, and billing disputes.\nretention:\n- scope: account data\n  period: 30 days\n  text: 'Account data : Deleted within 30 days of account closure'\n- scope: billing records\n  period: null\n  text: 'Billing records : Retained by Polar.sh per their policies'\n- scope: usage logs\n  period: null\n  text: 'Usage logs : Retained by Polar.sh per their policies'\nresidency:\n- region: EU\n  text: Fly.io (our hosting provider) runs our infrastructure in the EU region.\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: 'Account data : Deleted within 30 days of account closure'\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/worlddataapi/privacy/worlddataapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
summary_line: 11 quoted statements, read from World Data API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Geography
- Travel
---
