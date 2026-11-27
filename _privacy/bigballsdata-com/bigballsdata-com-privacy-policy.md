---
api_specs:
- filename: bigballsdata-com-api-openapi.json
  format: json
  label: Big Ball Sports API API
  slug: big-ball-sports-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bigballsdata-com/openapi/_original/bigballsdata-com-api-openapi.json
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account we store your email address, a hashed password (or an OAuth identifier from a third-party login provider), and the API keys you generate.
  - category: behavioral
    text: When you make API requests we log the endpoint path, the sport the request was for, response status, response time, how the request reached us (direct API or an integration), the timestamp, and the originating API key
  deletion:
    route: Email request to the provider
    text: Self-serve export and deletion from the developer dashboard are not available yet.
  dpa:
    available: true
    text: A full sub-processor list is in our Data Processing Addendum .
    url: null
  purposes:
  - purpose: Authentication and rate limiting
    text: Account data lets us authenticate you and enforce per-key rate limits.
  - purpose: Billing and abuse detection
    text: Request logs let us bill paid plans accurately and detect abuse patterns.
  - purpose: Product decisions
    text: Aggregate, de-identified usage data informs product decisions.
  retention:
  - period: null
    scope: Account data
    text: Account data is kept while your account is open.
  - period: null
    scope: Request metadata
    text: The request metadata described above is retained for analytics, billing accuracy, and abuse detection.
  - period: null
    scope: Billing records
    text: Billing records are kept for the period required by tax law in our operating jurisdiction.
  rights:
  - right: Access
    text: You can request access to your account data, a copy of your API request logs, or deletion of your account.
  - right: Deletion
    text: You can request access to your account data, a copy of your API request logs, or deletion of your account.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your data with advertisers.
  subprocessors:
    text: A full sub-processor list is in our Data Processing Addendum .
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bigballsdata-com
provenance_date: '2026-11-09'
provider_name: bigballsdata-com
provider_slug: bigballsdata-com
slug: bigballsdata-com-privacy-policy
source_date: '2026-11-09'
source_filename: bigballsdata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bigballsdata.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bigballsdata-com\naid: bigballsdata-com\nurl: https://bigballsdata.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account we store your email address, a hashed password (or an OAuth identifier from a\n    third-party login provider), and the API keys you generate.\n- category: behavioral\n  text: When you make API requests we log the endpoint path, the sport the request was for, response status, response\n    time, how the request reached us (direct API or an integration), the timestamp, and the originating\
  \ API key\npurposes:\n- purpose: Authentication and rate limiting\n  text: Account data lets us authenticate you and enforce per-key rate limits.\n- purpose: Billing and abuse detection\n  text: Request logs let us bill paid plans accurately and detect abuse patterns.\n- purpose: Product decisions\n  text: Aggregate, de-identified usage data informs product decisions.\nretention:\n- scope: Account data\n  period: null\n  text: Account data is kept while your account is open.\n- scope: Request metadata\n  period: null\n  text: The request metadata described above is retained for analytics, billing accuracy, and abuse detection.\n- scope: Billing records\n  period: null\n  text: Billing records are kept for the period required by tax law in our operating jurisdiction.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: A full sub-processor list is in our Data Processing Addendum .\ndpa:\n  available: true\n  url: null\n  text: A full sub-processor list is in our Data Processing\
  \ Addendum .\ndeletion:\n  route: Email request to the provider\n  text: Self-serve export and deletion from the developer dashboard are not available yet.\nrights:\n- right: Access\n  text: You can request access to your account data, a copy of your API request logs, or deletion of your account.\n- right: Deletion\n  text: You can request access to your account data, a copy of your API request logs, or deletion of your account.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/bigballsdata-com/privacy/bigballsdata-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from bigballsdata-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Data
- Analytics
- Betting
---
