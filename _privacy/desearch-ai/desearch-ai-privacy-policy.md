---
api_specs:
- filename: desearch-ai-ai-search-api-openapi.yml
  format: yaml
  label: desearch-ai AI Search API
  slug: desearch-ai-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-ai-search-api-openapi.yml
- filename: desearch-ai-company-search-api-openapi.yml
  format: yaml
  label: desearch-ai Company Search API
  slug: desearch-ai-company-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-company-search-api-openapi.yml
- filename: desearch-ai-facebook-search-api-openapi.yml
  format: yaml
  label: desearch-ai Facebook Search API
  slug: desearch-ai-facebook-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-facebook-search-api-openapi.yml
- filename: desearch-ai-instagram-search-api-openapi.yml
  format: yaml
  label: desearch-ai Instagram Search API
  slug: desearch-ai-instagram-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-instagram-search-api-openapi.yml
- filename: desearch-ai-network-stats-api-openapi.yml
  format: yaml
  label: desearch-ai Network Stats API
  slug: desearch-ai-network-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-network-stats-api-openapi.yml
- filename: desearch-ai-people-search-api-openapi.yml
  format: yaml
  label: desearch-ai People Search API
  slug: desearch-ai-people-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-people-search-api-openapi.yml
- filename: desearch-ai-search-api-openapi.yml
  format: yaml
  label: desearch-ai Search API
  slug: desearch-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-search-api-openapi.yml
- filename: desearch-ai-tiktok-search-api-openapi.yml
  format: yaml
  label: desearch-ai TikTok Search API
  slug: desearch-ai-tiktok-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-tiktok-search-api-openapi.yml
- filename: desearch-ai-web-search-api-openapi.yml
  format: yaml
  label: desearch-ai Web Search API
  slug: desearch-ai-web-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-web-search-api-openapi.yml
- filename: desearch-ai-x-search-api-openapi.yml
  format: yaml
  label: desearch-ai X Search API
  slug: desearch-ai-x-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/desearch-ai/openapi/desearch-ai-x-search-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email address, name, and password when you create an account'
  - category: device
    text: 'Technical Data: IP address, browser type, device information'
  - category: financial
    text: 'Payment Information: Billing details processed through our payment providers'
  - category: behavioral
    text: 'Usage Data: API calls, queries, and usage patterns'
  deletion:
    route: Email privacy@desearch.ai
    text: You can ask us to delete your personal information earlier by writing to privacy@desearch.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain services
    text: Provide and maintain our Services
  - purpose: Process transactions
    text: Process transactions and send billing information
  - purpose: Improve services
    text: Improve and optimize our Services
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud or abuse
  residency:
  - region: United States
    text: 'Where it is stored: on servers in the United States.'
  retention:
  - period: null
    scope: Account information
    text: while your account is open, and for 30 days after you close it.
  - period: 12 months
    scope: Usage data
    text: 'Usage data (API calls, queries and usage records): 12 months, then deleted or aggregated so it no longer identifies you.'
  - period: 90 days
    scope: Technical data
    text: 'Technical data (such as IP addresses in logs): 90 days.'
  - period: 30 days
    scope: People Search results
    text: Results stay available to you for 30 days after a search ends.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Objection
    text: Object to processing of your data
  - right: Portability
    text: Data portability
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
name: desearch-ai
provenance_date: '2026-11-09'
provider_name: desearch-ai
provider_slug: desearch-ai
slug: desearch-ai-privacy-policy
source_date: '2026-11-09'
source_filename: desearch-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.desearch.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: desearch-ai\naid: desearch-ai\nurl: https://www.desearch.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email address, name, and password when you create an account'\n- category: device\n  text: 'Technical Data: IP address, browser type, device information'\n- category: financial\n  text: 'Payment Information: Billing details processed through our payment providers'\n- category: behavioral\n  text: 'Usage Data: API calls, queries, and usage patterns'\npurposes:\n- purpose: Provide and maintain services\n\
  \  text: Provide and maintain our Services\n- purpose: Process transactions\n  text: Process transactions and send billing information\n- purpose: Improve services\n  text: Improve and optimize our Services\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud or abuse\nretention:\n- scope: Account information\n  period: null\n  text: while your account is open, and for 30 days after you close it.\n- scope: Usage data\n  period: 12 months\n  text: 'Usage data (API calls, queries and usage records): 12 months, then deleted or aggregated so it no longer\n    identifies you.'\n- scope: Technical data\n  period: 90 days\n  text: 'Technical data (such as IP addresses in logs): 90 days.'\n- scope: People Search results\n  period: 30 days\n  text: Results stay available to you for 30 days after a search ends.\nresidency:\n- region: United States\n  text: 'Where it is stored: on servers in the United States.'\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@desearch.ai\n  text: You can ask us to delete your personal information earlier by writing to privacy@desearch.ai .\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correction\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Objection\n  text: Object to processing of your data\n- right: Portability\n  text: Data portability\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/desearch-ai/privacy/desearch-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 19 quoted statements, read from desearch-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Search
- Web
- Bittensor
- Company
---
