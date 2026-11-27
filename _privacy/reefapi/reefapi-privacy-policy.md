---
api_specs:
- filename: reefapi-classifieds-second-hand-api-openapi.yml
  format: yaml
  label: ReefAPI Classifieds & Second-hand API
  slug: reefapi-classifieds-second-hand-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-classifieds-second-hand-api-openapi.yml
- filename: reefapi-developer-tools-api-openapi.yml
  format: yaml
  label: ReefAPI Developer Tools API
  slug: reefapi-developer-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-developer-tools-api-openapi.yml
- filename: reefapi-e-commerce-marketplaces-api-openapi.yml
  format: yaml
  label: ReefAPI E-commerce & Marketplaces API
  slug: reefapi-e-commerce-marketplaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-e-commerce-marketplaces-api-openapi.yml
- filename: reefapi-finance-data-api-openapi.yml
  format: yaml
  label: ReefAPI Finance & Data API
  slug: reefapi-finance-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-finance-data-api-openapi.yml
- filename: reefapi-government-tenders-api-openapi.yml
  format: yaml
  label: ReefAPI Government & Tenders API
  slug: reefapi-government-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-government-tenders-api-openapi.yml
- filename: reefapi-jobs-hiring-api-openapi.yml
  format: yaml
  label: ReefAPI Jobs & Hiring API
  slug: reefapi-jobs-hiring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-jobs-hiring-api-openapi.yml
- filename: reefapi-media-film-knowledge-api-openapi.yml
  format: yaml
  label: ReefAPI Media, Film & Knowledge API
  slug: reefapi-media-film-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-media-film-knowledge-api-openapi.yml
- filename: reefapi-other-api-openapi.yml
  format: yaml
  label: ReefAPI Other API
  slug: reefapi-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-other-api-openapi.yml
- filename: reefapi-real-estate-api-openapi.yml
  format: yaml
  label: ReefAPI Real Estate API
  slug: reefapi-real-estate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-real-estate-api-openapi.yml
- filename: reefapi-reputation-reviews-api-openapi.yml
  format: yaml
  label: ReefAPI Reputation & Reviews API
  slug: reefapi-reputation-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-reputation-reviews-api-openapi.yml
- filename: reefapi-search-seo-api-openapi.yml
  format: yaml
  label: ReefAPI Search & SEO API
  slug: reefapi-search-seo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-search-seo-api-openapi.yml
- filename: reefapi-social-media-api-openapi.yml
  format: yaml
  label: ReefAPI Social Media API
  slug: reefapi-social-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-social-media-api-openapi.yml
- filename: reefapi-travel-lodging-api-openapi.yml
  format: yaml
  label: ReefAPI Travel & Lodging API
  slug: reefapi-travel-lodging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-travel-lodging-api-openapi.yml
- filename: reefapi-utilities-ai-api-openapi.yml
  format: yaml
  label: ReefAPI Utilities & AI API
  slug: reefapi-utilities-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reefapi/openapi/reefapi-utilities-ai-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email and authentication details (passwords are hashed; we never store them in plaintext).'
  - category: financial
    text: 'Payment data: handled by our Merchant of Record, the payment provider that processes checkout on our behalf; we never see or store full card details.'
  - category: behavioral
    text: 'Usage data: per-request metadata — which API/endpoint, timestamp, latency, bytes, and credits — to meter billing and operate the Service.'
  - category: communication
    text: the messages you write and the assistant's replies
  - category: location
    text: your country as reported by our network provider, your browser language and user agent
  - category: device
    text: a one-way hash of your IP address, never the address itself
  deletion:
    route: Delete conversation from assistant menu or email privacy contact; account deletion removes account data
    text: You can delete a conversation from the assistant's menu
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and billing
    text: To authenticate you, provision and meter API keys, show your usage and billing, prevent abuse, and improve reliability.
  - purpose: Service improvement
    text: Conversations are recorded for that purpose and may be reviewed by our team, to learn which data people need, which APIs fail and where the assistant got something wrong.
  - purpose: Site measurement
    text: To understand how the site is used, we also set a few measurement cookies
  residency:
  - region: EEA/Azure
    text: the data is stored in Microsoft's Azure cloud
  retention:
  - period: null
    scope: Account data
    text: We keep account data while your account is active and usage records for as long as needed for billing, security, and legal obligations, then delete or anonymize them.
  - period: a few days to a few weeks
    scope: Request logs
    text: 'Request logs are kept on a rolling basis: the most recent 100,000 requests across the Service plus the latest 200 for each endpoint, which in practice is a few days to a few weeks'
  - period: a few hours
    scope: Failed request parameters
    text: the parameters of failed requests are kept for a few hours
  - period: 180 days
    scope: Visit records
    text: Visit records are deleted after 180 days.
  - period: 30 days
    scope: Playground requests
    text: Requests you run in the API playground are kept with their parameters, with personal data such as email addresses, phone numbers and keys removed, for 30 days
  - period: 30 days
    scope: Clarity recordings
    text: Recordings are available to us for 30 days; Microsoft keeps recordings we mark as favourites and a random sample for up to 9 months.
  rights:
  - right: access, correct, export, delete
    text: you can access, correct, export, or delete your account data, and object to or restrict certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, and we don't use your request payloads to build profiles of you.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ReefAPI
provenance_date: '2026-11-10'
provider_name: ReefAPI
provider_slug: reefapi
slug: reefapi-privacy-policy
source_date: '2026-11-10'
source_filename: reefapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://reefapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ReefAPI\naid: reefapi\nurl: https://reefapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your email and authentication details (passwords are hashed; we never store them in plaintext).'\n- category: financial\n  text: 'Payment data: handled by our Merchant of Record, the payment provider that processes checkout on our behalf;\n    we never see or store full card details.'\n- category: behavioral\n  text: 'Usage data: per-request metadata — which API/endpoint, timestamp, latency, bytes, and credits — to meter\n\
  \    billing and operate the Service.'\n- category: communication\n  text: the messages you write and the assistant's replies\n- category: location\n  text: your country as reported by our network provider, your browser language and user agent\n- category: device\n  text: a one-way hash of your IP address, never the address itself\npurposes:\n- purpose: Authentication and billing\n  text: To authenticate you, provision and meter API keys, show your usage and billing, prevent abuse, and improve\n    reliability.\n- purpose: Service improvement\n  text: Conversations are recorded for that purpose and may be reviewed by our team, to learn which data people\n    need, which APIs fail and where the assistant got something wrong.\n- purpose: Site measurement\n  text: To understand how the site is used, we also set a few measurement cookies\nretention:\n- scope: Account data\n  period: null\n  text: We keep account data while your account is active and usage records for as long as needed for\
  \ billing, security,\n    and legal obligations, then delete or anonymize them.\n- scope: Request logs\n  period: a few days to a few weeks\n  text: 'Request logs are kept on a rolling basis: the most recent 100,000 requests across the Service plus the\n    latest 200 for each endpoint, which in practice is a few days to a few weeks'\n- scope: Failed request parameters\n  period: a few hours\n  text: the parameters of failed requests are kept for a few hours\n- scope: Visit records\n  period: 180 days\n  text: Visit records are deleted after 180 days.\n- scope: Playground requests\n  period: 30 days\n  text: Requests you run in the API playground are kept with their parameters, with personal data such as email\n    addresses, phone numbers and keys removed, for 30 days\n- scope: Clarity recordings\n  period: 30 days\n  text: Recordings are available to us for 30 days; Microsoft keeps recordings we mark as favourites and a random\n    sample for up to 9 months.\nresidency:\n- region: EEA/Azure\n\
  \  text: the data is stored in Microsoft's Azure cloud\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete conversation from assistant menu or email privacy contact; account deletion removes account data\n  text: You can delete a conversation from the assistant's menu\nrights:\n- right: access, correct, export, delete\n  text: you can access, correct, export, or delete your account data, and object to or restrict certain processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, and we don't use your request payloads to build profiles of you.\n"
source_yaml_url: https://artifacts.apis.io/reefapi/privacy/reefapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from ReefAPI's own page on 2026-11-10.
synthetic: false
tags:
- Web Data
- Data Aggregation
- Web Scraping
- SERP
- E-Commerce
- Social Media
- Real Estate
- Job
- Travel
- News
- Finance
- Reviews
- Company Intelligence
- MCP
- Agent-Native
- REST
- OpenAPI
- Llms.txt
- API Catalog
- Free Tier
- Credit
- Gateways
---
