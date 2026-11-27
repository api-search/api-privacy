---
api_specs:
- filename: crawlgraph-backlinks-api-openapi.yml
  format: yaml
  label: CrawlGraph Backlinks API
  slug: crawlgraph-backlinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlgraph/openapi/crawlgraph-backlinks-api-openapi.yml
- filename: crawlgraph-changes-api-openapi.yml
  format: yaml
  label: CrawlGraph Changes API
  slug: crawlgraph-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlgraph/openapi/crawlgraph-changes-api-openapi.yml
- filename: crawlgraph-free-key-api-openapi.yml
  format: yaml
  label: CrawlGraph Free Key API
  slug: crawlgraph-free-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlgraph/openapi/crawlgraph-free-key-api-openapi.yml
- filename: crawlgraph-gap-analysis-api-openapi.yml
  format: yaml
  label: CrawlGraph Gap Analysis API
  slug: crawlgraph-gap-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlgraph/openapi/crawlgraph-gap-analysis-api-openapi.yml
- filename: crawlgraph-releases-api-openapi.yml
  format: yaml
  label: CrawlGraph Releases API
  slug: crawlgraph-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crawlgraph/openapi/crawlgraph-releases-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address - when you purchase a lifetime licence.
  - category: financial
    text: We receive the Stripe customer id, the amount paid, and the currency.
  - category: device
    text: standard request logs (IP, user-agent, timestamp) are kept for 30 days
  - category: behavioral
    text: we use Google Analytics 4 to record anonymous usage (pages viewed, buttons clicked, country)
  - category: other
    text: domains you look up are cached on our servers to speed up repeated lookups
  deletion:
    route: email privacy contact
    text: Email [email protected] and we will respond within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account login and receipts
    text: Used to send magic-link login emails and purchase receipts.
  - purpose: analytics
    text: we use Google Analytics 4 to record anonymous usage (pages viewed, buttons clicked, country)
  - purpose: ad measurement and audiences
    text: We also use Meta Pixel to measure launch ad performance and build advertising audiences after consent.
  - purpose: security and abuse prevention
    text: for security and abuse prevention
  retention:
  - period: 30 days
    scope: server logs
    text: standard request logs (IP, user-agent, timestamp) are kept for 30 days for security and abuse prevention.
  - period: as long as your licence is active plus two years
    scope: account data
    text: We keep account data for as long as your licence is active plus two years for tax and accounting obligations.
  - period: 30-day expiry
    scope: shared backlink cache
    text: Shared backlink cache entries have a 30-day expiry.
  - period: 7-day retention window
    scope: research jobs
    text: Research jobs have a 7-day retention window.
  - period: 30-day lifetime
    scope: refresh tokens
    text: Refresh tokens have a 30-day lifetime, bounded by the grant's absolute 90-day lifetime.
  rights:
  - right: access, correction, export, deletion, objection
    text: you have the right to access, correct, export, or delete the personal data we hold about you, and to object to processing
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with your local data protection authority.
  role:
    text: Data controller Search Engine Wizards (Hakukonevelhot Oy), a Finnish limited liability company
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data to anyone, ever.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CrawlGraph
provenance_date: '2026-11-09'
provider_name: CrawlGraph
provider_slug: crawlgraph
slug: crawlgraph-privacy-policy
source_date: '2026-11-09'
source_filename: crawlgraph-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crawlgraph.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CrawlGraph\naid: crawlgraph\nurl: https://crawlgraph.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller Search Engine Wizards (Hakukonevelhot Oy), a Finnish limited liability company\ndata_categories:\n- category: contact\n  text: Email address - when you purchase a lifetime licence.\n- category: financial\n  text: We receive the Stripe customer id, the amount paid, and the currency.\n- category: device\n  text: standard request logs (IP, user-agent, timestamp) are kept for 30 days\n- category: behavioral\n  text: we use Google Analytics 4 to record anonymous usage\
  \ (pages viewed, buttons clicked, country)\n- category: other\n  text: domains you look up are cached on our servers to speed up repeated lookups\npurposes:\n- purpose: account login and receipts\n  text: Used to send magic-link login emails and purchase receipts.\n- purpose: analytics\n  text: we use Google Analytics 4 to record anonymous usage (pages viewed, buttons clicked, country)\n- purpose: ad measurement and audiences\n  text: We also use Meta Pixel to measure launch ad performance and build advertising audiences after consent.\n- purpose: security and abuse prevention\n  text: for security and abuse prevention\nretention:\n- scope: server logs\n  period: 30 days\n  text: standard request logs (IP, user-agent, timestamp) are kept for 30 days for security and abuse prevention.\n- scope: account data\n  period: as long as your licence is active plus two years\n  text: We keep account data for as long as your licence is active plus two years for tax and accounting obligations.\n-\
  \ scope: shared backlink cache\n  period: 30-day expiry\n  text: Shared backlink cache entries have a 30-day expiry.\n- scope: research jobs\n  period: 7-day retention window\n  text: Research jobs have a 7-day retention window.\n- scope: refresh tokens\n  period: 30-day lifetime\n  text: Refresh tokens have a 30-day lifetime, bounded by the grant's absolute 90-day lifetime.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy contact\n  text: Email [email protected] and we will respond within 30 days.\nrights:\n- right: access, correction, export, deletion, objection\n  text: you have the right to access, correct, export, or delete the personal data we hold about you, and to object\n    to processing\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell data to anyone, ever.\n"
source_yaml_url: https://artifacts.apis.io/crawlgraph/privacy/crawlgraph-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from CrawlGraph's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- backlink-intelligence
- MarTech
- Competitive Intelligence
- Web Data
- Common-Crawl
- Link Building
- Developer Tools
- MCP
---
