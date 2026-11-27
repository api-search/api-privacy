---
api_specs:
- filename: duckduckgo-instant-answers-api-openapi.yml
  format: yaml
  label: DuckDuckGo Instant Answers API
  slug: duckduckgo-instant-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/duckduckgo/openapi/duckduckgo-instant-answers-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: your device sends some information about itself automatically, like its IP address, browser type, and language
  - category: behavioral
    text: we only save these anonymous search queries — completely disconnected from any unique identifiers like IP addresses — to improve our search indexes by analyzing anonymous search trends
  - category: contact
    text: we will ask for your email address and use it only to deliver that content
  - category: location
    text: we've further engineered a solution to shield your precise location from us and our content providers that sends us a random location nearish to you, which we also never log to disk
  deletion:
    route: Privacy Rights page
    text: For information about these rights, such as requesting deletion or a copy of your personal information, please review our Privacy Rights page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Improve search indexes
    text: we only save these anonymous search queries — completely disconnected from any unique identifiers like IP addresses — to improve our search indexes by analyzing anonymous search trends
  retention:
  - period: null
    scope: Device information
    text: we only use this information temporarily to deliver content to you
  - period: null
    scope: Direct communications
    text: we will limit its use by only keeping it for as long as necessary for the stated purpose
  rights:
  - right: Deletion or copy of personal information
    text: such as requesting deletion or a copy of your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: there are scenarios where we may transfer this limited personal information (for example, your email address) to countries other than the country in which it was received
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DuckDuckGo
provenance_date: '2026-11-09'
provider_name: DuckDuckGo
provider_slug: duckduckgo
slug: duckduckgo-privacy-policy
source_date: '2026-11-09'
source_filename: duckduckgo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://duckduckgo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DuckDuckGo\naid: duckduckgo\nurl: https://duckduckgo.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your device sends some information about itself automatically, like its IP address, browser type, and language\n- category: behavioral\n  text: we only save these anonymous search queries — completely disconnected from any unique identifiers like IP\n    addresses — to improve our search indexes by analyzing anonymous search trends\n- category: contact\n  text: we will ask for your email address and use it only to deliver that\
  \ content\n- category: location\n  text: we've further engineered a solution to shield your precise location from us and our content providers that\n    sends us a random location nearish to you, which we also never log to disk\npurposes:\n- purpose: Improve search indexes\n  text: we only save these anonymous search queries — completely disconnected from any unique identifiers like IP\n    addresses — to improve our search indexes by analyzing anonymous search trends\nretention:\n- scope: Device information\n  period: null\n  text: we only use this information temporarily to deliver content to you\n- scope: Direct communications\n  period: null\n  text: we will limit its use by only keeping it for as long as necessary for the stated purpose\nresidency: []\ntransfers:\n- mechanism: other\n  text: there are scenarios where we may transfer this limited personal information (for example, your email address)\n    to countries other than the country in which it was received\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy Rights page\n  text: For information about these rights, such as requesting deletion or a copy of your personal information,\n    please review our Privacy Rights page\nrights:\n- right: Deletion or copy of personal information\n  text: such as requesting deletion or a copy of your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/duckduckgo/privacy/duckduckgo-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from DuckDuckGo's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Privacy
- Browser
- AI Chat
- Email Protection
- VPN
- Trackers
- Identity
---
