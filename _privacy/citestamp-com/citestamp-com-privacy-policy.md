---
api_specs:
- filename: citestamp-com-openapi-generated.yml
  format: yaml
  label: CiteStamp API
  slug: citestamp-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citestamp-com/openapi/_ae-authored/citestamp-com-openapi-generated.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: We keep your Google account id, email address and name, your plan, and the API key issued to you.
  - category: identifying
    text: A claim you sign carries your public researcher identifier, and it is permanent on an append-only log.
  - category: location
    text: Cloudflare keeps a request log for about a week and traffic analytics for about a month. Both hold your IP address, a rough location (city and network), the time, your browser’s user agent and the URL
  deletion:
    route: email
    text: 'Questions, deletion requests, anything: info@citestamp.com'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: traffic counting and abuse prevention
    text: Our host’s request logs, also below, are read only to count traffic and to stop abuse.
  - purpose: billing and rate limits
    text: We keep the daily counts for billing while the agreement is active.
  retention:
  - period: about a week
    scope: extension DOI lookup in Cloudflare request log
    text: Cloudflare’s request log keeps that lookup, with your IP address, for about a week.
  - period: 13 months
    scope: lookup record without IP address
    text: We keep the lookup itself for 13 months, without your IP address.
  - period: about a year
    scope: MCP tool call counts
    text: Seven tool names, one integer each per UTC day, kept about a year.
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
name: CiteStamp
provenance_date: '2026-11-09'
provider_name: CiteStamp
provider_slug: citestamp-com
slug: citestamp-com-privacy-policy
source_date: '2026-11-09'
source_filename: citestamp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://citestamp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CiteStamp\naid: citestamp-com\nurl: https://citestamp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We keep your Google account id, email address and name, your plan, and the API key issued to you.\n- category: identifying\n  text: A claim you sign carries your public researcher identifier, and it is permanent on an append-only log.\n- category: location\n  text: Cloudflare keeps a request log for about a week and traffic analytics for about a month. Both hold your\n    IP address, a rough location (city and network), the\
  \ time, your browser’s user agent and the URL\npurposes:\n- purpose: traffic counting and abuse prevention\n  text: Our host’s request logs, also below, are read only to count traffic and to stop abuse.\n- purpose: billing and rate limits\n  text: We keep the daily counts for billing while the agreement is active.\nretention:\n- scope: extension DOI lookup in Cloudflare request log\n  period: about a week\n  text: Cloudflare’s request log keeps that lookup, with your IP address, for about a week.\n- scope: lookup record without IP address\n  period: 13 months\n  text: We keep the lookup itself for 13 months, without your IP address.\n- scope: MCP tool call counts\n  period: about a year\n  text: Seven tool names, one integer each per UTC day, kept about a year.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: 'Questions, deletion requests, anything: info@citestamp.com'\nrights:\
  \ []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/citestamp-com/privacy/citestamp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 9 quoted statements, read from CiteStamp's own page on 2026-11-09.
synthetic: false
tags:
- Citation Graph
- Scholarly Metadata
- Bibliography Checking
- AI Integration
- Publishers
---
