---
api_specs:
- filename: defoorreport-com-news-api-openapi.yml
  format: yaml
  label: DeFoor Report News API
  slug: defoorreport-com-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/defoorreport-com/openapi/defoorreport-com-news-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: If you sign up, we keep your email address to send the email and, for saved articles, your list of saved stories.
  - category: device
    text: For each page view it keeps the page, the time, the site that sent you, your device type, browser language and time zone
  - category: behavioral
    text: the stories you read (dropped after about seven weeks)
  - category: communication
    text: If you write to us, we keep what you send so we can answer it.
  - category: identifying
    text: the servers that run the Report keep standard request logs, which include the network address a request came from
  deletion:
    route: Contact us request
    text: 'Ask us to remove your email, your key or anything you sent, and we will: contact us'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Send weekly email
    text: we keep your email address to send the email
  - purpose: Apply plan daily limit
    text: (to apply your plan's daily limit)
  - purpose: Security and troubleshooting
    text: for security and troubleshooting
  - purpose: Improve the Report
    text: We count visits to improve the Report.
  retention:
  - period: 30 days
    scope: Standard server request logs
    text: Google Cloud keeps them for 30 days.
  - period: a day
    scope: Sign-up request hashes
    text: we also keep a scrambled (hashed) form of the network address and email with the times of recent sign-up requests, for a day.
  - period: about seven weeks
    scope: Stories read in reader memory
    text: the stories you read (dropped after about seven weeks)
  - period: a few weeks
    scope: Interest words in reader memory
    text: (they fade over a few weeks)
  - period: six hours
    scope: Recently shown stories
    text: which stories an app showed you in the last six hours
  rights:
  - right: Reset or start fresh on learned interests
    text: on My saved articles you can turn interests up or down, reset what was learned or start fresh
  - right: Download memory file
    text: on Just for you you can download your memory file, clear your reading history, and disconnect every AI app at once
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
name: DeFoor Report
provenance_date: '2026-11-09'
provider_name: DeFoor Report
provider_slug: defoorreport-com
slug: defoorreport-com-privacy-policy
source_date: '2026-11-09'
source_filename: defoorreport-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://defoorreport.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DeFoor Report\naid: defoorreport-com\nurl: https://defoorreport.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: If you sign up, we keep your email address to send the email and, for saved articles, your list of saved\n    stories.\n- category: device\n  text: For each page view it keeps the page, the time, the site that sent you, your device type, browser language\n    and time zone\n- category: behavioral\n  text: the stories you read (dropped after about seven weeks)\n- category: communication\n  text: If you write to us, we keep\
  \ what you send so we can answer it.\n- category: identifying\n  text: the servers that run the Report keep standard request logs, which include the network address a request\n    came from\npurposes:\n- purpose: Send weekly email\n  text: we keep your email address to send the email\n- purpose: Apply plan daily limit\n  text: (to apply your plan's daily limit)\n- purpose: Security and troubleshooting\n  text: for security and troubleshooting\n- purpose: Improve the Report\n  text: We count visits to improve the Report.\nretention:\n- scope: Standard server request logs\n  period: 30 days\n  text: Google Cloud keeps them for 30 days.\n- scope: Sign-up request hashes\n  period: a day\n  text: we also keep a scrambled (hashed) form of the network address and email with the times of recent sign-up\n    requests, for a day.\n- scope: Stories read in reader memory\n  period: about seven weeks\n  text: the stories you read (dropped after about seven weeks)\n- scope: Interest words in reader\
  \ memory\n  period: a few weeks\n  text: (they fade over a few weeks)\n- scope: Recently shown stories\n  period: six hours\n  text: which stories an app showed you in the last six hours\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us request\n  text: 'Ask us to remove your email, your key or anything you sent, and we will: contact us'\nrights:\n- right: Reset or start fresh on learned interests\n  text: on My saved articles you can turn interests up or down, reset what was learned or start fresh\n- right: Download memory file\n  text: on Just for you you can download your memory file, clear your reading history, and disconnect every AI app\n    at once\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/defoorreport-com/privacy/defoorreport-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from DeFoor Report's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Artificial Intelligence
- Media
- News Aggregation
- MCP
- LLM
---
