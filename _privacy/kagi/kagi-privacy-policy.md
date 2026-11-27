---
api_specs:
- filename: kagi-extract-api-openapi.yml
  format: yaml
  label: Kagi Extract API
  slug: kagi-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kagi/openapi/kagi-extract-api-openapi.yml
- filename: kagi-search-api-openapi.yml
  format: yaml
  label: Kagi Search API
  slug: kagi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kagi/openapi/kagi-search-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Creating an account with a pseudonymous email address
  - category: financial
    text: Paying for their plan using cryptocurrency
  - category: device
    text: kagi_session cookies Opaque Token Session identifier.
  - category: location
    text: kagi_precise_location cookies Base64 Encoded JSON Stored client location when using optional Geolocation or manual location setting in Maps
  - category: behavioral
    text: We may store web requests made by user browser temporarily, with strict retention periods, for debugging purposes, and in a manner that they are not linked to an account.
  deletion:
    route: Delete thread via Assistant UI or delete Kagi account
    text: Users can also choose to delete a thread immediately via the Assistant UI.
  dpa:
    available: null
    text: we're finishing a Data Processing Addendum that covers this in full, including standard contractual clauses for international transfers.
    url: null
  purposes:
  - purpose: billing and administrative
    text: These services may be loaded only when necessary for billing and administrative purposes.
  - purpose: usage metering for API billing
    text: We use the key to authenticate the request and to meter usage for billing.
  - purpose: debugging and abuse prevention
    text: Queries may be logged temporarily, in a non-account-linked manner, for debugging and abuse prevention
  retention:
  - period: 7 days
    scope: Load balancer logs
    text: Load Balancer Logs 7 days Identifies and protects against Denial of Service Attacks (DDoS prevention).
  - period: 7 days
    scope: Virtual machine logs
    text: Virtual Machine Logs 7 days Contains debug information used to ensure system reliability and availability.
  - period: 90 days
    scope: Sentry error data
    text: Sentry 90 days Contains information about server-side errors that occur within our production applications.
  - period: one day
    scope: Kagi Assistant conversation threads
    text: By default and unless otherwise stated, Kagi Assistant automatically deletes conversation threads after one day.
  - period: 30 days
    scope: Reported Assistant threads
    text: Reported threads are retained for 30 days and then automatically deleted.
  - period: not more than a day
    scope: Summaries of public web pages
    text: Summaries of public web pages may be cached for a short period of time, not more than a day.
  rights:
  - right: data protection rights under GDPR, CCPA and other privacy laws
    text: For information about your data protection rights under GDPR, CCPA, and other privacy laws, see our Privacy Rights Addendum.
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
name: Kagi
provenance_date: '2026-11-09'
provider_name: Kagi
provider_slug: kagi
slug: kagi-privacy-policy
source_date: '2026-11-09'
source_filename: kagi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kagi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Kagi\naid: kagi\nurl: https://kagi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Creating an account with a pseudonymous email address\n- category: financial\n  text: Paying for their plan using cryptocurrency\n- category: device\n  text: kagi_session cookies Opaque Token Session identifier.\n- category: location\n  text: kagi_precise_location cookies Base64 Encoded JSON Stored client location when using optional Geolocation\n    or manual location setting in Maps\n- category: behavioral\n  text: We may store web requests\
  \ made by user browser temporarily, with strict retention periods, for debugging\n    purposes, and in a manner that they are not linked to an account.\npurposes:\n- purpose: billing and administrative\n  text: These services may be loaded only when necessary for billing and administrative purposes.\n- purpose: usage metering for API billing\n  text: We use the key to authenticate the request and to meter usage for billing.\n- purpose: debugging and abuse prevention\n  text: Queries may be logged temporarily, in a non-account-linked manner, for debugging and abuse prevention\nretention:\n- scope: Load balancer logs\n  period: 7 days\n  text: Load Balancer Logs 7 days Identifies and protects against Denial of Service Attacks (DDoS prevention).\n- scope: Virtual machine logs\n  period: 7 days\n  text: Virtual Machine Logs 7 days Contains debug information used to ensure system reliability and availability.\n- scope: Sentry error data\n  period: 90 days\n  text: Sentry 90 days Contains information\
  \ about server-side errors that occur within our production applications.\n- scope: Kagi Assistant conversation threads\n  period: one day\n  text: By default and unless otherwise stated, Kagi Assistant automatically deletes conversation threads after\n    one day.\n- scope: Reported Assistant threads\n  period: 30 days\n  text: Reported threads are retained for 30 days and then automatically deleted.\n- scope: Summaries of public web pages\n  period: not more than a day\n  text: Summaries of public web pages may be cached for a short period of time, not more than a day.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: we're finishing a Data Processing Addendum that covers this in full, including standard contractual clauses\n    for international transfers.\ndeletion:\n  route: Delete thread via Assistant UI or delete Kagi account\n  text: Users can also choose to delete a thread immediately via the Assistant UI.\n\
  rights:\n- right: data protection rights under GDPR, CCPA and other privacy laws\n  text: For information about your data protection rights under GDPR, CCPA, and other privacy laws, see our Privacy\n    Rights Addendum.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kagi/privacy/kagi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
summary_line: 17 quoted statements, read from Kagi's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Premium Search
- AI Search
- Summarization
- FastGPT
- Data Enrichment
- OpenAPI
- Pay-per-use
- Privacy
- LLM
- Web Index
---
