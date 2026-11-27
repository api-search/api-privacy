---
api_specs:
- filename: caper-network-agent-api-openapi.yml
  format: yaml
  label: Caper Agent API
  slug: caper-network-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-agent-api-openapi.yml
- filename: caper-network-blog-api-openapi.yml
  format: yaml
  label: Caper Blog API
  slug: caper-network-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-blog-api-openapi.yml
- filename: caper-network-blog-xml-api-openapi.yml
  format: yaml
  label: Caper Blog.xml API
  slug: caper-network-blog-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-blog-xml-api-openapi.yml
- filename: caper-network-capers-api-openapi.yml
  format: yaml
  label: Caper Capers API
  slug: caper-network-capers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-capers-api-openapi.yml
- filename: caper-network-llms-txt-api-openapi.yml
  format: yaml
  label: Caper Llms.txt API
  slug: caper-network-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-llms-txt-api-openapi.yml
- filename: caper-network-mcp-api-openapi.yml
  format: yaml
  label: Caper MCP API
  slug: caper-network-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-mcp-api-openapi.yml
- filename: caper-network-sitemap-xml-api-openapi.yml
  format: yaml
  label: Caper Sitemap.xml API
  slug: caper-network-sitemap-xml-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-sitemap-xml-api-openapi.yml
- filename: caper-network-well-known-api-openapi.yml
  format: yaml
  label: Caper .well Known API
  slug: caper-network-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-well-known-api-openapi.yml
- filename: caper-network-wiki-api-openapi.yml
  format: yaml
  label: Caper Wiki API
  slug: caper-network-wiki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caper-network/openapi/caper-network-wiki-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store the address.
  - category: other
    text: A profile picture, if you set one.
  - category: other
    text: Wiki pages, every revision of them, and comments – each recorded against your wallet address.
  - category: location
    text: your country
  - category: device
    text: whether you are on a phone, tablet or computer
  - category: behavioral
    text: It also records searches typed into its search boxes, clicks on links to other sites, and calls to its MCP server.
  deletion:
    route: contact the provider
    text: To ask about, correct, or delete what we hold, get in touch
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: keep you signed in
    text: It exists only to keep you signed in, and Disconnect deletes it on the spot.
  - purpose: site traffic analytics
    text: The site counts its own traffic, in its own database
  residency:
  - region: Ireland (eu-west-1)
    text: Database – Supabase (PostgreSQL), hosted on AWS in eu-west-1, Ireland.
  retention:
  - period: 90 days
    scope: session cookie
    text: The session cookie expires 90 days after your last visit, sooner if you press Disconnect.
  - period: 400 days
    scope: analytics counts
    text: Analytics counts are deleted after 400 days.
  - period: for as long as the site runs
    scope: wallet address and published content
    text: Your wallet address and what you have published are kept for as long as the site runs
  - period: replaced every day
    scope: analytics visitor salt
    text: The salt is replaced every day and the old one deleted
  rights:
  - right: access, correction, deletion
    text: To ask about, correct, or delete what we hold, get in touch
  - right: stop using the service
    text: You can stop at any time by disconnecting your wallet and not returning.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or rent anything about you to anyone
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Caper
provenance_date: '2026-11-09'
provider_name: Caper
provider_slug: caper-network
slug: caper-network-privacy-policy
source_date: '2026-11-09'
source_filename: caper-network-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://caper.network/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Caper\naid: caper-network\nurl: https://caper.network/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store the address.\n- category: other\n  text: A profile picture, if you set one.\n- category: other\n  text: Wiki pages, every revision of them, and comments – each recorded against your wallet address.\n- category: location\n  text: your country\n- category: device\n  text: whether you are on a phone, tablet or computer\n- category: behavioral\n  text: It also records searches typed into its search boxes, clicks on links to\
  \ other sites, and calls to its MCP\n    server.\npurposes:\n- purpose: keep you signed in\n  text: It exists only to keep you signed in, and Disconnect deletes it on the spot.\n- purpose: site traffic analytics\n  text: The site counts its own traffic, in its own database\nretention:\n- scope: session cookie\n  period: 90 days\n  text: The session cookie expires 90 days after your last visit, sooner if you press Disconnect.\n- scope: analytics counts\n  period: 400 days\n  text: Analytics counts are deleted after 400 days.\n- scope: wallet address and published content\n  period: for as long as the site runs\n  text: Your wallet address and what you have published are kept for as long as the site runs\n- scope: analytics visitor salt\n  period: replaced every day\n  text: The salt is replaced every day and the old one deleted\nresidency:\n- region: Ireland (eu-west-1)\n  text: Database – Supabase (PostgreSQL), hosted on AWS in eu-west-1, Ireland.\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the provider\n  text: To ask about, correct, or delete what we hold, get in touch\nrights:\n- right: access, correction, deletion\n  text: To ask about, correct, or delete what we hold, get in touch\n- right: stop using the service\n  text: You can stop at any time by disconnecting your wallet and not returning.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or rent anything about you to anyone\n"
source_yaml_url: https://artifacts.apis.io/caper-network/privacy/caper-network-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Caper's own page on 2026-11-09.
synthetic: false
tags:
- DAO
- Blockchain
- Fundraising
- Radix
- Decentralized
---
