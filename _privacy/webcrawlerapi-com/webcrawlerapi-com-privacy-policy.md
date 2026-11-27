---
api_specs:
- filename: webcrawlerapi-com-agent-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Agent API
  slug: webcrawlerapi-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-agent-api-openapi.yml
- filename: webcrawlerapi-com-feeds-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Feeds API
  slug: webcrawlerapi-com-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-feeds-api-openapi.yml
- filename: webcrawlerapi-com-jobs-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Jobs API
  slug: webcrawlerapi-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-jobs-api-openapi.yml
- filename: webcrawlerapi-com-organization-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Organization API
  slug: webcrawlerapi-com-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-organization-api-openapi.yml
- filename: webcrawlerapi-com-status-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI Status API
  slug: webcrawlerapi-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-status-api-openapi.yml
- filename: webcrawlerapi-com-v2-scraping-api-openapi.yml
  format: yaml
  label: WebCrawlerAPI V2 Scraping API
  slug: webcrawlerapi-com-v2-scraping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/webcrawlerapi-com/openapi/webcrawlerapi-com-v2-scraping-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: device
    source: https://webcrawlerapi.com/privacy
    text: we may collect information related to your device, your location, and the way you interact with our services
  - category: identifying
    source: https://webcrawlerapi.com/privacy
    text: This might include your IP address, browser type, access times, and referring website addresses.
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: as defined in our Data Processing Agreement (DPA)
    url: null
  purposes:
  - purpose: cloud hosting, data storage, analytics, content delivery, email delivery
    text: Sub-processors are engaged to perform specific services such as cloud hosting, data storage, analytics, content delivery, and email delivery.
  - purpose: provide and improve services
    source: https://webcrawlerapi.com/privacy
    text: We use this information to provide and improve our services, understand how you use our services, develop new products or services, and communicate with you, our users.
  residency:
  - region: EU
    text: Hetzner EU Scaleway EU Google Cloud Run Global Cloudflare Workers Global Cloudflare Global Brightdata Global PostHog (EU) EU Resend US
  rights:
  - right: object to new sub-processor
    text: If you object to the use of a new sub-processor on reasonable grounds, please notify us within the 30-day period.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    source: https://webcrawlerapi.com/privacy
    stance: conditional
    text: We do not sell or share your personal information to third parties for marketing purposes without your explicit consent.
  subprocessors:
    text: Current Sub-Processors Sub-Processor Data Location Hetzner EU Scaleway EU Google Cloud Run Global Cloudflare Workers Global Cloudflare Global Brightdata Global PostHog (EU) EU Resend US
    url: https://webcrawlerapi.com/legal/subprocessor-list
  transfers:
  - mechanism: SCC
    text: Data transfers outside the EU/EEA are protected using Standard Contractual Clauses (SCCs) or participation in the EU-U.S. Data Privacy Framework.
  - mechanism: DPF
    text: Data transfers outside the EU/EEA are protected using Standard Contractual Clauses (SCCs) or participation in the EU-U.S. Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WebCrawlerAPI
provenance_date: '2026-11-10'
provider_name: WebCrawlerAPI
provider_slug: webcrawlerapi-com
slug: webcrawlerapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: webcrawlerapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://webcrawlerapi.com/legal/subprocessor-list
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WebCrawlerAPI\naid: webcrawlerapi-com\nurl: https://webcrawlerapi.com/legal/subprocessor-list\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://webcrawlerapi.com/legal/subprocessor-list\n  - https://webcrawlerapi.com/privacy\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: we may collect information related to your device, your location, and the way you interact with our services\n  source: https://webcrawlerapi.com/privacy\n- category: identifying\n  text: This might include your IP address, browser type, access times, and referring website addresses.\n  source: https://webcrawlerapi.com/privacy\n\
  purposes:\n- purpose: cloud hosting, data storage, analytics, content delivery, email delivery\n  text: Sub-processors are engaged to perform specific services such as cloud hosting, data storage, analytics,\n    content delivery, and email delivery.\n- purpose: provide and improve services\n  text: We use this information to provide and improve our services, understand how you use our services, develop\n    new products or services, and communicate with you, our users.\n  source: https://webcrawlerapi.com/privacy\nretention: []\nresidency:\n- region: EU\n  text: Hetzner EU Scaleway EU Google Cloud Run Global Cloudflare Workers Global Cloudflare Global Brightdata Global\n    PostHog (EU) EU Resend US\ntransfers:\n- mechanism: SCC\n  text: Data transfers outside the EU/EEA are protected using Standard Contractual Clauses (SCCs) or participation\n    in the EU-U.S. Data Privacy Framework.\n- mechanism: DPF\n  text: Data transfers outside the EU/EEA are protected using Standard Contractual\
  \ Clauses (SCCs) or participation\n    in the EU-U.S. Data Privacy Framework.\nsubprocessors:\n  url: https://webcrawlerapi.com/legal/subprocessor-list\n  text: Current Sub-Processors Sub-Processor Data Location Hetzner EU Scaleway EU Google Cloud Run Global Cloudflare\n    Workers Global Cloudflare Global Brightdata Global PostHog (EU) EU Resend US\ndpa:\n  available: true\n  url: null\n  text: as defined in our Data Processing Agreement (DPA)\ndeletion:\n  route: null\n  text: null\nrights:\n- right: object to new sub-processor\n  text: If you object to the use of a new sub-processor on reasonable grounds, please notify us within the 30-day\n    period.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell or share your personal information to third parties for marketing purposes without your explicit\n    consent.\n  source: https://webcrawlerapi.com/privacy\n"
source_yaml_url: https://artifacts.apis.io/webcrawlerapi-com/privacy/webcrawlerapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- transfers
- subprocessors
- dpa
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from WebCrawlerAPI's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Web Crawling
- Data Extraction
- Markdown
- AI Agents
- LLM
- RAG
- Web Feeds
- Change Detection
- Structured Data
- MCP
- A2A
- Agent-Native
---
