---
api_specs:
- filename: datacircle-datacircle-api-openapi.yml
  format: yaml
  label: Datacircle Datacircle API
  slug: datacircle-datacircle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-datacircle-api-openapi.yml
- filename: datacircle-fetchin-api-openapi.yml
  format: yaml
  label: Datacircle Fetchin API
  slug: datacircle-fetchin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-fetchin-api-openapi.yml
- filename: datacircle-harvestapi-api-openapi.yml
  format: yaml
  label: Datacircle Harvest API
  slug: datacircle-harvestapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-harvestapi-api-openapi.yml
- filename: datacircle-up2data-api-openapi.yml
  format: yaml
  label: Datacircle Up2 Data API
  slug: datacircle-up2data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datacircle/openapi/datacircle-up2data-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: With this ID, we can tell one person's visits from another's.
  - category: contact
    text: We keep your work email and the times you signed up and signed in.
  - category: device
    text: We store the names and versions of your browser and operating system, and on some phones the model too.
  - category: behavioral
    text: The script notes whether you scrolled, clicked, tapped, typed or moved the pointer.
  - category: communication
    text: We keep the message and the email address you send to wayne@datacircle.dev .
  deletion:
    route: email to wayne@datacircle.dev
    text: We delete your data within 30 days of your email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: keep the site running
    text: We use your data to keep the site running and to fix what breaks.
  - purpose: learn pages read, answer and test APIs
    text: We use it to learn which pages you read, to answer you and to test the GTM APIs we list.
  retention:
  - period: 400 days
    scope: request logs
    text: We keep request logs for 400 days, then delete them.
  - period: 30 days
    scope: MCP server logs
    text: We keep the app's name and tool calls for 30 days, then delete them.
  - period: until you ask us to delete them
    scope: account data
    text: We keep your account and the data in your account until you ask us to delete them.
  - period: until you ask us to delete them
    scope: emails to us
    text: We keep your message and your email address until you ask us to delete them.
  rights:
  - right: access and deletion
    text: To ask what data we hold about you, or to have us delete it, write to wayne@datacircle.dev .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell it, and we don't use it for ads.
  subprocessors:
    text: Other companies host our server and our email.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Datacircle
provenance_date: '2026-11-09'
provider_name: Datacircle
provider_slug: datacircle
slug: datacircle-privacy-policy
source_date: '2026-11-09'
source_filename: datacircle-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://datacircle.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Datacircle\naid: datacircle\nurl: https://datacircle.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: With this ID, we can tell one person's visits from another's.\n- category: contact\n  text: We keep your work email and the times you signed up and signed in.\n- category: device\n  text: We store the names and versions of your browser and operating system, and on some phones the model too.\n- category: behavioral\n  text: The script notes whether you scrolled, clicked, tapped, typed or moved the pointer.\n- category: communication\n\
  \  text: We keep the message and the email address you send to wayne@datacircle.dev .\npurposes:\n- purpose: keep the site running\n  text: We use your data to keep the site running and to fix what breaks.\n- purpose: learn pages read, answer and test APIs\n  text: We use it to learn which pages you read, to answer you and to test the GTM APIs we list.\nretention:\n- scope: request logs\n  period: 400 days\n  text: We keep request logs for 400 days, then delete them.\n- scope: MCP server logs\n  period: 30 days\n  text: We keep the app's name and tool calls for 30 days, then delete them.\n- scope: account data\n  period: until you ask us to delete them\n  text: We keep your account and the data in your account until you ask us to delete them.\n- scope: emails to us\n  period: until you ask us to delete them\n  text: We keep your message and your email address until you ask us to delete them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Other companies host our server\
  \ and our email.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to wayne@datacircle.dev\n  text: We delete your data within 30 days of your email.\nrights:\n- right: access and deletion\n  text: To ask what data we hold about you, or to have us delete it, write to wayne@datacircle.dev .\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell it, and we don't use it for ads.\n"
source_yaml_url: https://artifacts.apis.io/datacircle/privacy/datacircle-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Datacircle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B Data
- MCP
- API Directory
- Benchmarks
- Open Data
---
