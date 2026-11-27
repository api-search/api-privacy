---
api_specs:
- filename: mattermark-companies-api-openapi.yml
  format: yaml
  label: Mattermark Companies API
  slug: mattermark-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-companies-api-openapi.yml
- filename: mattermark-complex-queries-api-openapi.yml
  format: yaml
  label: Mattermark Complex Queries API
  slug: mattermark-complex-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-complex-queries-api-openapi.yml
- filename: mattermark-funding-events-api-openapi.yml
  format: yaml
  label: Mattermark Funding Events API
  slug: mattermark-funding-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-funding-events-api-openapi.yml
- filename: mattermark-investors-api-openapi.yml
  format: yaml
  label: Mattermark Investors API
  slug: mattermark-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-investors-api-openapi.yml
- filename: mattermark-search-api-openapi.yml
  format: yaml
  label: Mattermark Search API
  slug: mattermark-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-search-api-openapi.yml
- filename: mattermark-utilities-api-openapi.yml
  format: yaml
  label: Mattermark Utilities API
  slug: mattermark-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mattermark/openapi/mattermark-utilities-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: if you register, your name, job title, company, phone number, industry, and email
  - category: financial
    text: if you make a purchase, your payment information (e.g., credit card information and billing address)
  - category: device
    text: mobile device ID; location and language information; device name and model; operating system type, name, and version; your activities within the App
  deletion:
    route: Request removal of personal information
    text: You have the right to request that your personal information is permanently removed from our system and database at any time. Such request will be accommodated within 10 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and customer support
    text: To provide our Services to you, to communicate with you about your use of our Services, to respond to your inquiries, to fulfill your orders, and for other customer service purposes.
  - purpose: Marketing and promotion with consent
    text: For marketing and promotional purposes upon your consent.
  - purpose: Analytics and service improvement
    text: To better understand how users access and use our Site, App, and Services, both on an aggregated and individualized basis; to improve our Site, App, and Services; and for other research and analytical purposes.
  retention:
  - period: null
    scope: Personal information
    text: We will retain your personal information for as long as you use the Site, the App and services.
  rights:
  - right: Access and modify personal information
    text: You may modify personal information that you have submitted by logging into your account and updating your profile information.
  - right: Opt out of promotional emails
    text: You may opt-out of such communications by following the opt-out instructions contained in the e-mail.
  - right: Opt out of targeted advertising
    text: You may opt-out of many third-party ad networks, including those operated by members of the Network Advertising Initiative (“NAI”) and the Digital Advertising Alliance (“DAA”).
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
name: Mattermark
provenance_date: '2026-11-10'
provider_name: Mattermark
provider_slug: mattermark
slug: mattermark-privacy-policy
source_date: '2026-11-10'
source_filename: mattermark-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mattermark.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mattermark\naid: mattermark\nurl: https://mattermark.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: if you register, your name, job title, company, phone number, industry, and email\n- category: financial\n  text: if you make a purchase, your payment information (e.g., credit card information and billing address)\n- category: device\n  text: mobile device ID; location and language information; device name and model; operating system type, name,\n    and version; your activities within the App\npurposes:\n- purpose:\
  \ Provide services and customer support\n  text: To provide our Services to you, to communicate with you about your use of our Services, to respond to your\n    inquiries, to fulfill your orders, and for other customer service purposes.\n- purpose: Marketing and promotion with consent\n  text: For marketing and promotional purposes upon your consent.\n- purpose: Analytics and service improvement\n  text: To better understand how users access and use our Site, App, and Services, both on an aggregated and individualized\n    basis; to improve our Site, App, and Services; and for other research and analytical purposes.\nretention:\n- scope: Personal information\n  period: null\n  text: We will retain your personal information for as long as you use the Site, the App and services.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request removal of personal information\n  text: You have the right\
  \ to request that your personal information is permanently removed from our system and\n    database at any time. Such request will be accommodated within 10 days.\nrights:\n- right: Access and modify personal information\n  text: You may modify personal information that you have submitted by logging into your account and updating your\n    profile information.\n- right: Opt out of promotional emails\n  text: You may opt-out of such communications by following the opt-out instructions contained in the e-mail.\n- right: Opt out of targeted advertising\n  text: You may opt-out of many third-party ad networks, including those operated by members of the Network Advertising\n    Initiative (“NAI”) and the Digital Advertising Alliance (“DAA”).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mattermark/privacy/mattermark-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from Mattermark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business Intelligence
- Company Data
- Investor
- Funding
- Sales Intelligence
- Market Research
---
