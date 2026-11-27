---
api_specs:
- filename: tradedatahub-commerce-api-openapi.yml
  format: yaml
  label: TradeDataHub Public API Commerce API
  slug: tradedatahub-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradedatahub/openapi/tradedatahub-commerce-api-openapi.yml
- filename: tradedatahub-datasets-api-openapi.yml
  format: yaml
  label: TradeDataHub Public API Datasets API
  slug: tradedatahub-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradedatahub/openapi/tradedatahub-datasets-api-openapi.yml
- filename: tradedatahub-discovery-api-openapi.yml
  format: yaml
  label: TradeDataHub Public API Discovery API
  slug: tradedatahub-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradedatahub/openapi/tradedatahub-discovery-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: financial
    text: Payment information is collected and processed by Stripe .
  - category: contact
    text: Contact details (such as an email address) only when you provide them during checkout or when you email us for support.
  - category: device
    text: Operational logs maintained by our hosting provider (Netlify), such as IP address, user agent, and request time, used for security and abuse prevention.
  - category: behavioral
    text: Basic usage events (page views and outbound link clicks) used to operate and improve the site.
  deletion:
    route: email sales@tradedatahub.net
    text: To exercise a right, email sales@tradedatahub.net with enough order detail for us to verify the request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: security and abuse prevention
    text: used for security and abuse prevention
  - purpose: operate and improve the site
    text: used to operate and improve the site
  retention:
  - period: null
    scope: purchase and support records
    text: Purchase and support records are kept only as long as needed to deliver products, handle support and refunds, meet tax and fraud-prevention obligations, or as required by law.
  - period: null
    scope: operational logs
    text: Operational logs follow the retention settings of the relevant provider.
  rights:
  - right: access, correction, deletion
    text: you may have rights to access, correct, or delete personal information, or to opt out of certain processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell buyer identity information to anyone.
  subprocessors:
    text: Service providers Stripe — payment processing ( Stripe privacy policy ) Netlify — hosting, functions, and logs ( Netlify privacy policy )
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TradeDataHub Public API
provenance_date: '2026-11-10'
provider_name: TradeDataHub Public API
provider_slug: tradedatahub
slug: tradedatahub-privacy-policy
source_date: '2026-11-10'
source_filename: tradedatahub-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tradedatahub.net/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TradeDataHub Public API\naid: tradedatahub\nurl: https://www.tradedatahub.net/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: Payment information is collected and processed by Stripe .\n- category: contact\n  text: Contact details (such as an email address) only when you provide them during checkout or when you email\n    us for support.\n- category: device\n  text: Operational logs maintained by our hosting provider (Netlify), such as IP address, user agent, and request\n    time, used for security and abuse prevention.\n- category:\
  \ behavioral\n  text: Basic usage events (page views and outbound link clicks) used to operate and improve the site.\npurposes:\n- purpose: security and abuse prevention\n  text: used for security and abuse prevention\n- purpose: operate and improve the site\n  text: used to operate and improve the site\nretention:\n- scope: purchase and support records\n  period: null\n  text: Purchase and support records are kept only as long as needed to deliver products, handle support and refunds,\n    meet tax and fraud-prevention obligations, or as required by law.\n- scope: operational logs\n  period: null\n  text: Operational logs follow the retention settings of the relevant provider.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Service providers Stripe — payment processing ( Stripe privacy policy ) Netlify — hosting, functions, and\n    logs ( Netlify privacy policy )\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email sales@tradedatahub.net\n\
  \  text: To exercise a right, email sales@tradedatahub.net with enough order detail for us to verify the request.\nrights:\n- right: access, correction, deletion\n  text: you may have rights to access, correct, or delete personal information, or to opt out of certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell buyer identity information to anyone.\n"
source_yaml_url: https://artifacts.apis.io/tradedatahub/privacy/tradedatahub-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from TradeDataHub Public API's own page on 2026-11-10.
synthetic: false
tags:
- contractor data
- B2B Data
- Business Listings
- Datasets
- CSV
- Lead Generation
- Sales Intelligence
- x402
- Agent-Native
- Llms.txt
- OpenAPI
---
