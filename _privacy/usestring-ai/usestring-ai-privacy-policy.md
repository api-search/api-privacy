---
api_specs:
- filename: usestring-ai-browser-api-openapi.yml
  format: yaml
  label: usestring-ai Browser API
  slug: usestring-ai-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-browser-api-openapi.yml
- filename: usestring-ai-builds-api-openapi.yml
  format: yaml
  label: usestring-ai Builds API
  slug: usestring-ai-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-builds-api-openapi.yml
- filename: usestring-ai-contexts-api-openapi.yml
  format: yaml
  label: usestring-ai Contexts API
  slug: usestring-ai-contexts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-contexts-api-openapi.yml
- filename: usestring-ai-documentation-api-openapi.yml
  format: yaml
  label: usestring-ai Documentation API
  slug: usestring-ai-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-documentation-api-openapi.yml
- filename: usestring-ai-feeds-api-openapi.yml
  format: yaml
  label: usestring-ai Feeds API
  slug: usestring-ai-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-feeds-api-openapi.yml
- filename: usestring-ai-fetch-api-openapi.yml
  format: yaml
  label: usestring-ai Fetch API
  slug: usestring-ai-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-fetch-api-openapi.yml
- filename: usestring-ai-search-api-openapi.yml
  format: yaml
  label: usestring-ai Search API
  slug: usestring-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-search-api-openapi.yml
- filename: usestring-ai-sessions-api-openapi.yml
  format: yaml
  label: usestring-ai Sessions API
  slug: usestring-ai-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-sessions-api-openapi.yml
- filename: usestring-ai-sitemap-api-openapi.yml
  format: yaml
  label: usestring-ai Sitemap API
  slug: usestring-ai-sitemap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/usestring-ai/openapi/usestring-ai-sitemap-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information, which may include your name, email address, company name
  - category: financial
    text: we retain your billing contact, transaction history, and the last four digits and brand of your card
  - category: location
    text: geolocation inferred from IP
  - category: behavioral
    text: session replays and heatmaps of your interactions with our websites and the customer portal
  - category: communication
    text: support communications
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: our data processing agreement with PostHog incorporates the EU Standard Contractual Clauses
    url: null
  purposes:
  - purpose: provide and secure services
    text: To provide, operate, and secure the Services; authenticate you; process payments and prevent fraud
  - purpose: product improvement
    text: understand aggregate usage to improve the product
  - purpose: visitor identification sales follow-up
    text: where visitor identification is active, evaluate business interest and conduct human-reviewed sales follow-up
  residency:
  - region: United States
    text: We are based in the United States and our servers and service providers are primarily located there.
  retention:
  - period: 30 days
    scope: request captures kept for debugging
    text: request captures kept for debugging are deleted after 30 days
  - period: 90 days
    scope: monitoring artifacts
    text: monitoring artifacts after 90 days
  - period: 30 days
    scope: session replays
    text: Session replays are deleted 30 days after capture.
  - period: 12 months
    scope: product analytics events
    text: Product analytics events, including the interaction data behind heatmaps, are kept for no more than 12 months.
  - period: 180 days
    scope: visitor identification minimum record
    text: We retain the minimum record needed to measure accuracy, suppression, and outcomes for no more than 180 days
  rights:
  - right: access
    text: you may have the right to access, receive a portable copy of, correct, delete, restrict, or object to processing of your personal information
  - right: withdraw consent
    text: and to withdraw consent
  - right: opt out of direct marketing
    text: including direct marketing, which we honor for everyone
  - right: California access, deletion, correction
    text: California residents may request access (twice per 12 months), deletion, and correction
  role:
    text: String acts as a service provider processing those requests on the customer's behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information for money or use your information ourselves for third-party behavioral advertising.
  subprocessors:
    text: we maintain a current list of these sub-processors and update it as they change. The current list is available to customers on request via our sub-processors page
    url: null
  transfers:
  - mechanism: DPF
    text: PostHog is certified under the EU-U.S. Data Privacy Framework, the UK Extension to it, and the Swiss-U.S. Data Privacy Framework.
  - mechanism: SCC
    text: our data processing agreement with PostHog incorporates the EU Standard Contractual Clauses (controller-to-processor module)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: String
provenance_date: '2026-11-10'
provider_name: String
provider_slug: usestring-ai
slug: usestring-ai-privacy-policy
source_date: '2026-11-10'
source_filename: usestring-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://usestring.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: String\naid: usestring-ai\nurl: https://usestring.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: String acts as a service provider processing those requests on the customer's behalf.\ndata_categories:\n- category: identifying\n  text: Account information, which may include your name, email address, company name\n- category: financial\n  text: we retain your billing contact, transaction history, and the last four digits and brand of your card\n- category: location\n  text: geolocation inferred from IP\n- category: behavioral\n  text: session replays and heatmaps of your interactions with\
  \ our websites and the customer portal\n- category: communication\n  text: support communications\npurposes:\n- purpose: provide and secure services\n  text: To provide, operate, and secure the Services; authenticate you; process payments and prevent fraud\n- purpose: product improvement\n  text: understand aggregate usage to improve the product\n- purpose: visitor identification sales follow-up\n  text: where visitor identification is active, evaluate business interest and conduct human-reviewed sales follow-up\nretention:\n- scope: request captures kept for debugging\n  period: 30 days\n  text: request captures kept for debugging are deleted after 30 days\n- scope: monitoring artifacts\n  period: 90 days\n  text: monitoring artifacts after 90 days\n- scope: session replays\n  period: 30 days\n  text: Session replays are deleted 30 days after capture.\n- scope: product analytics events\n  period: 12 months\n  text: Product analytics events, including the interaction data behind heatmaps,\
  \ are kept for no more than 12 months.\n- scope: visitor identification minimum record\n  period: 180 days\n  text: We retain the minimum record needed to measure accuracy, suppression, and outcomes for no more than 180\n    days\nresidency:\n- region: United States\n  text: We are based in the United States and our servers and service providers are primarily located there.\ntransfers:\n- mechanism: DPF\n  text: PostHog is certified under the EU-U.S. Data Privacy Framework, the UK Extension to it, and the Swiss-U.S.\n    Data Privacy Framework.\n- mechanism: SCC\n  text: our data processing agreement with PostHog incorporates the EU Standard Contractual Clauses (controller-to-processor\n    module)\nsubprocessors:\n  url: null\n  text: we maintain a current list of these sub-processors and update it as they change. The current list is available\n    to customers on request via our sub-processors page\ndpa:\n  available: true\n  url: null\n  text: our data processing agreement with PostHog\
  \ incorporates the EU Standard Contractual Clauses\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: you may have the right to access, receive a portable copy of, correct, delete, restrict, or object to processing\n    of your personal information\n- right: withdraw consent\n  text: and to withdraw consent\n- right: opt out of direct marketing\n  text: including direct marketing, which we honor for everyone\n- right: California access, deletion, correction\n  text: California residents may request access (twice per 12 months), deletion, and correction\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information for money or use your information ourselves for third-party behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/usestring-ai/privacy/usestring-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from String's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Data Extraction
- Markdown
- JSON
---
