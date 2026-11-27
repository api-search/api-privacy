---
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: the URL or hostname you entered
  - category: identifying
    text: a short-lived counter of requests per IP address (100 per hour) that expires automatically
  deletion:
    route: revoke connection from AI client
    text: you can revoke a connection from your client at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: perform network lookups for the user
    text: That function receives the URL or hostname you entered, performs the lookup, and returns metadata.
  - purpose: abuse prevention
    text: To prevent abuse it keeps a short-lived counter of requests per IP address (100 per hour) that expires automatically.
  - purpose: keep MCP connection working
    text: We store the token and grant record needed to keep that connection working (in Cloudflare Workers KV) and nothing else
  - purpose: display advertising
    text: We display advertisements served by Google AdSense.
  retention:
  - period: null
    scope: network tool URLs and results
    text: It does not persist URLs or results.
  - period: null
    scope: MCP OAuth tokens and grant records
    text: Tokens expire automatically and you can revoke a connection from your client at any time.
  - period: null
    scope: MCP tool call inputs
    text: tool calls are not logged with their inputs
  rights:
  - right: opt out of personalised advertising
    text: You can opt out of personalised advertising at Google's ad settings page.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or share personal data
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: httpstatus-com
provenance_date: '2026-11-09'
provider_name: httpstatus-com
provider_slug: httpstatus-com
slug: httpstatus-com-privacy-policy
source_date: '2026-11-09'
source_filename: httpstatus-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://httpstatus.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: httpstatus-com\naid: httpstatus-com\nurl: https://httpstatus.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the URL or hostname you entered\n- category: identifying\n  text: a short-lived counter of requests per IP address (100 per hour) that expires automatically\npurposes:\n- purpose: perform network lookups for the user\n  text: That function receives the URL or hostname you entered, performs the lookup, and returns metadata.\n- purpose: abuse prevention\n  text: To prevent abuse it keeps a short-lived counter of requests\
  \ per IP address (100 per hour) that expires automatically.\n- purpose: keep MCP connection working\n  text: We store the token and grant record needed to keep that connection working (in Cloudflare Workers KV) and\n    nothing else\n- purpose: display advertising\n  text: We display advertisements served by Google AdSense.\nretention:\n- scope: network tool URLs and results\n  period: null\n  text: It does not persist URLs or results.\n- scope: MCP OAuth tokens and grant records\n  period: null\n  text: Tokens expire automatically and you can revoke a connection from your client at any time.\n- scope: MCP tool call inputs\n  period: null\n  text: tool calls are not logged with their inputs\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: revoke connection from AI client\n  text: you can revoke a connection from your client at any time\nrights:\n- right: opt out of personalised advertising\n\
  \  text: You can opt out of personalised advertising at Google's ad settings page.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or share personal data\n"
source_yaml_url: https://artifacts.apis.io/httpstatus-com/privacy/httpstatus-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from httpstatus-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- HTTP
- Status-Codes
- Developer Tools
- Open Source
---
