---
api_specs:
- filename: aivideoatlas-com-plan-shots-api-openapi.yml
  format: yaml
  label: AI Video Atlas Plan Shots API
  slug: aivideoatlas-com-plan-shots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aivideoatlas-com/openapi/aivideoatlas-com-plan-shots-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: your email, whether it's an agent's or a person's address (recipientType)
  - category: communication
    text: the URLs and notes you enter, and your email if you give one
  - category: device
    text: the client's user-agent string (first 40 characters)
  - category: behavioral
    text: how many tool calls (by tool, MCP vs REST) and which client apps connected
  - category: other
    text: any UTM campaign tags (utm_source, utm_medium, utm_campaign) on the link you arrived from
  deletion:
    route: email hello@aivideoatlas.com
    text: Email hello@aivideoatlas.com to have your data deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: reply and send signed-up content
    text: We use your email only to send what you signed up for or to reply to you.
  - purpose: improve data
    text: to improve our data we log the tool name
  - purpose: rate limiting
    text: to keep the free API fair we limit requests per address
  retention:
  - period: briefly
    scope: rate limit counter
    text: only that hash's one-minute request counter is kept briefly
  - period: null
    scope: IP addresses
    text: IPs are never written to our logs or stats.
  rights:
  - right: deletion
    text: Email hello@aivideoatlas.com to have your data deleted.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or share data with advertisers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Video Atlas
provenance_date: '2026-11-09'
provider_name: AI Video Atlas
provider_slug: aivideoatlas-com
slug: aivideoatlas-com-privacy-policy
source_date: '2026-11-09'
source_filename: aivideoatlas-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aivideoatlas.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Video Atlas\naid: aivideoatlas-com\nurl: https://aivideoatlas.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email, whether it's an agent's or a person's address (recipientType)\n- category: communication\n  text: the URLs and notes you enter, and your email if you give one\n- category: device\n  text: the client's user-agent string (first 40 characters)\n- category: behavioral\n  text: how many tool calls (by tool, MCP vs REST) and which client apps connected\n- category: other\n  text: any UTM campaign tags (utm_source,\
  \ utm_medium, utm_campaign) on the link you arrived from\npurposes:\n- purpose: reply and send signed-up content\n  text: We use your email only to send what you signed up for or to reply to you.\n- purpose: improve data\n  text: to improve our data we log the tool name\n- purpose: rate limiting\n  text: to keep the free API fair we limit requests per address\nretention:\n- scope: rate limit counter\n  period: briefly\n  text: only that hash's one-minute request counter is kept briefly\n- scope: IP addresses\n  period: null\n  text: IPs are never written to our logs or stats.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@aivideoatlas.com\n  text: Email hello@aivideoatlas.com to have your data deleted.\nrights:\n- right: deletion\n  text: Email hello@aivideoatlas.com to have your data deleted.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or share data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/aivideoatlas-com/privacy/aivideoatlas-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from AI Video Atlas's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Comparison
- Pricing
- Tools
---
