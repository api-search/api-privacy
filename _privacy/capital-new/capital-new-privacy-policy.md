---
api_specs:
- filename: capital-new-openapi-generated.yml
  format: yaml
  label: capital.new API
  slug: capital-new-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capital-new/openapi/_ae-authored/capital-new-openapi-generated.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: The forms on /investors and /funders collect your name, email address, firm or fund (optional) and message
  - category: device
    text: we record the time, your browser’s user agent and the country Cloudflare reports for the request
  - category: identifying
    text: To limit how many messages one network can send, they keep a hashed value of the address with a message count, and both expire an hour after the last message.
  deletion:
    route: Ask through any of these forms, or by mail to the address above.
    text: Ask through any of these forms, or by mail to the address above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: reply to contact form messages
    text: used only to reply to you
  - purpose: rate limiting
    text: To limit how many messages one network can send
  - purpose: deliver site requests
    text: Cloudflare serves the site and processes each request, including your IP address, to deliver it.
  retention:
  - period: null
    scope: contact form data
    text: They are stored in Cloudflare KV, used only to reply to you, and kept until you ask us to delete them.
  - period: an hour after the last message
    scope: hashed IP and message count
    text: both expire an hour after the last message
  - period: null
    scope: MCP request counts
    text: the counts disappear when that server stops
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
name: capital.new
provenance_date: '2026-11-09'
provider_name: capital.new
provider_slug: capital-new
slug: capital-new-privacy-policy
source_date: '2026-11-09'
source_filename: capital-new-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://capital.new/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: capital.new\naid: capital-new\nurl: https://capital.new/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: The forms on /investors and /funders collect your name, email address, firm or fund (optional) and message\n- category: device\n  text: we record the time, your browser’s user agent and the country Cloudflare reports for the request\n- category: identifying\n  text: To limit how many messages one network can send, they keep a hashed value of the address with a message\n    count, and both expire an hour after the last message.\npurposes:\n\
  - purpose: reply to contact form messages\n  text: used only to reply to you\n- purpose: rate limiting\n  text: To limit how many messages one network can send\n- purpose: deliver site requests\n  text: Cloudflare serves the site and processes each request, including your IP address, to deliver it.\nretention:\n- scope: contact form data\n  period: null\n  text: They are stored in Cloudflare KV, used only to reply to you, and kept until you ask us to delete them.\n- scope: hashed IP and message count\n  period: an hour after the last message\n  text: both expire an hour after the last message\n- scope: MCP request counts\n  period: null\n  text: the counts disappear when that server stops\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask through any of these forms, or by mail to the address above.\n  text: Ask through any of these forms, or by mail to the address above.\nrights: []\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capital-new/privacy/capital-new-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 10 quoted statements, read from capital.new's own page on 2026-11-09.
synthetic: false
tags:
- Funding
- Artificial Intelligence
- Agents
- Pre-Seed
- MCP
---
