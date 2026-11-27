---
api_specs:
- filename: fastcrw-com-batch-api-openapi.yml
  format: yaml
  label: fastcrw-com Batch API
  slug: fastcrw-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-batch-api-openapi.yml
- filename: fastcrw-com-capabilities-api-openapi.yml
  format: yaml
  label: fastcrw-com Capabilities API
  slug: fastcrw-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-capabilities-api-openapi.yml
- filename: fastcrw-com-change-tracking-api-openapi.yml
  format: yaml
  label: fastcrw-com Change Tracking API
  slug: fastcrw-com-change-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-change-tracking-api-openapi.yml
- filename: fastcrw-com-crawl-api-openapi.yml
  format: yaml
  label: fastcrw-com Crawl API
  slug: fastcrw-com-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-crawl-api-openapi.yml
- filename: fastcrw-com-extract-api-openapi.yml
  format: yaml
  label: fastcrw-com Extract API
  slug: fastcrw-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-extract-api-openapi.yml
- filename: fastcrw-com-map-api-openapi.yml
  format: yaml
  label: fastcrw-com Map API
  slug: fastcrw-com-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-map-api-openapi.yml
- filename: fastcrw-com-scrape-api-openapi.yml
  format: yaml
  label: fastcrw-com Scrape API
  slug: fastcrw-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-scrape-api-openapi.yml
- filename: fastcrw-com-search-api-openapi.yml
  format: yaml
  label: fastcrw-com Search API
  slug: fastcrw-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fastcrw-com/openapi/fastcrw-com-search-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: Account email, optional profile metadata, hashed passwords for credentials users, hashed API key material, Stripe customer and subscription identifiers, and usage counters needed for plan enforcement and invoicing.
  - category: financial
    text: Stripe customer and subscription identifiers
  - category: device
    text: together with your IP address, approximate device and browser, and the page you arrived from
  - category: behavioral
    text: usage counters needed for plan enforcement and invoicing
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authentication, abuse prevention and billing
    text: Data is used to authenticate requests, prevent abuse, enforce limits, generate billing records, and provide dashboard visibility.
  - purpose: service announcements
    text: Product and service announcements, meaning feature launches, breaking changes and incident notices, are sent to registered users on the basis of our legitimate interest in keeping you informed about the service you signed up for
  - purpose: analytics and advertising measurement
    text: We also use Google Analytics 4 and Google Ads for usage analytics and to measure whether a visit followed one of our ads.
  retention:
  - period: null
    scope: access logs and usage telemetry
    text: Access logs and usage telemetry are retained only as long as needed for security, analytics, and billing operations.
  - period: null
    scope: request content with zero data retention enabled
    text: an account with zero data retention enabled has none of its request content written to our systems at all.
  rights:
  - right: object to product emails
    text: you can object at any time in your email settings
  - right: withdraw marketing consent
    text: you can withdraw it at any time
  - right: privacy requests
    text: Privacy requests and operational questions can be sent to hello@fastcrw.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not expose private account data publicly or sell customer data to third parties.
  subprocessors:
    text: infrastructure and search providers acting for fastCRW under contract
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fastcrw-com
provenance_date: '2026-11-09'
provider_name: fastcrw-com
provider_slug: fastcrw-com
slug: fastcrw-com-privacy-policy
source_date: '2026-11-09'
source_filename: fastcrw-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fastcrw.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fastcrw-com\naid: fastcrw-com\nurl: https://fastcrw.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Account email, optional profile metadata, hashed passwords for credentials users, hashed API key material,\n    Stripe customer and subscription identifiers, and usage counters needed for plan enforcement and invoicing.\n- category: financial\n  text: Stripe customer and subscription identifiers\n- category: device\n  text: together with your IP address, approximate device and browser, and the page you arrived from\n- category: behavioral\n\
  \  text: usage counters needed for plan enforcement and invoicing\npurposes:\n- purpose: authentication, abuse prevention and billing\n  text: Data is used to authenticate requests, prevent abuse, enforce limits, generate billing records, and provide\n    dashboard visibility.\n- purpose: service announcements\n  text: Product and service announcements, meaning feature launches, breaking changes and incident notices, are\n    sent to registered users on the basis of our legitimate interest in keeping you informed about the service you\n    signed up for\n- purpose: analytics and advertising measurement\n  text: We also use Google Analytics 4 and Google Ads for usage analytics and to measure whether a visit followed\n    one of our ads.\nretention:\n- scope: access logs and usage telemetry\n  period: null\n  text: Access logs and usage telemetry are retained only as long as needed for security, analytics, and billing\n    operations.\n- scope: request content with zero data retention enabled\n\
  \  period: null\n  text: an account with zero data retention enabled has none of its request content written to our systems at all.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: infrastructure and search providers acting for fastCRW under contract\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: object to product emails\n  text: you can object at any time in your email settings\n- right: withdraw marketing consent\n  text: you can withdraw it at any time\n- right: privacy requests\n  text: Privacy requests and operational questions can be sent to hello@fastcrw.com\nsale_or_sharing:\n  stance: prohibited\n  text: We do not expose private account data publicly or sell customer data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/fastcrw-com/privacy/fastcrw-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from fastcrw-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Scraping
- AI Agents
- Rust
- Open Source
- SERP
---
