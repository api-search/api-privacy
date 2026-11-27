---
api_specs:
- filename: sourcepost-interest-api-openapi.yml
  format: yaml
  label: SourcePost Interest API
  slug: sourcepost-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepost/openapi/sourcepost-interest-api-openapi.yml
- filename: sourcepost-listings-api-openapi.yml
  format: yaml
  label: SourcePost Listings API
  slug: sourcepost-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepost/openapi/sourcepost-listings-api-openapi.yml
- filename: sourcepost-system-api-openapi.yml
  format: yaml
  label: SourcePost System API
  slug: sourcepost-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sourcepost/openapi/sourcepost-system-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: device
    text: user agent, response language and an estimated client type
  - category: identifying
    text: These logs may include IP addresses
  - category: communication
    text: SourcePost stores the type of message ( offer or missing ), the text, the optional contact_url and the date.
  deletion:
    route: automatic deletion
    text: Request records are kept for 90 days and then deleted automatically
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: measure usage and protect service
    text: To measure how SourcePost is used (which kinds of clients come, what they search, which searches find nothing) and to protect the service
  - purpose: server security
    text: They are used only to protect and maintain the server
  - purpose: prevent abuse
    text: To prevent abuse, each client can make 60 requests per minute
  residency:
  - region: European Union (the Netherlands)
    text: on a server in a data centre in the European Union (the Netherlands)
  retention:
  - period: 90 days
    scope: request records
    text: Request records are kept for 90 days and then deleted automatically
  - period: 30 days at most
    scope: security logs
    text: are kept for 30 days at most and are then deleted automatically
  - period: 365 days (12 months)
    scope: messages sent to POST /v1/interest
    text: These messages are kept for 365 days (12 months) and then deleted automatically
  - period: 7 more days
    scope: backups
    text: Backups keep the data up to 7 more days
  role:
    text: Data controller
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: SourcePost is hosted by DigitalOcean (DigitalOcean, LLC, a company based in the United States)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SourcePost
provenance_date: '2026-11-10'
provider_name: SourcePost
provider_slug: sourcepost
slug: sourcepost-privacy-policy
source_date: '2026-11-10'
source_filename: sourcepost-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sourcepost.dev/privacy?lang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SourcePost\naid: sourcepost\nurl: https://sourcepost.dev/privacy?lang=en\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller\ndata_categories:\n- category: device\n  text: user agent, response language and an estimated client type\n- category: identifying\n  text: These logs may include IP addresses\n- category: communication\n  text: SourcePost stores the type of message ( offer or missing ), the text, the optional contact_url and the date.\npurposes:\n- purpose: measure usage and protect service\n  text: To measure how SourcePost is used (which kinds of clients come, what they\
  \ search, which searches find nothing)\n    and to protect the service\n- purpose: server security\n  text: They are used only to protect and maintain the server\n- purpose: prevent abuse\n  text: To prevent abuse, each client can make 60 requests per minute\nretention:\n- scope: request records\n  period: 90 days\n  text: Request records are kept for 90 days and then deleted automatically\n- scope: security logs\n  period: 30 days at most\n  text: are kept for 30 days at most and are then deleted automatically\n- scope: messages sent to POST /v1/interest\n  period: 365 days (12 months)\n  text: These messages are kept for 365 days (12 months) and then deleted automatically\n- scope: backups\n  period: 7 more days\n  text: Backups keep the data up to 7 more days\nresidency:\n- region: European Union (the Netherlands)\n  text: on a server in a data centre in the European Union (the Netherlands)\ntransfers: []\nsubprocessors:\n  url: null\n  text: SourcePost is hosted by DigitalOcean (DigitalOcean,\
  \ LLC, a company based in the United States)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: automatic deletion\n  text: Request records are kept for 90 days and then deleted automatically\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sourcepost/privacy/sourcepost-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
summary_line: 14 quoted statements, read from SourcePost's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Directory
- Suppliers
- Data
- Agents
---
