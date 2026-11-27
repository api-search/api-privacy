---
api_specs:
- filename: spade-card-enrichment-api-openapi.yml
  format: yaml
  label: Spade Card Enrichment API
  slug: spade-card-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-card-enrichment-api-openapi.yml
- filename: spade-category-action-triggers-api-openapi.yml
  format: yaml
  label: Spade Category Action Triggers API
  slug: spade-category-action-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-category-action-triggers-api-openapi.yml
- filename: spade-category-personalization-api-openapi.yml
  format: yaml
  label: Spade Category Personalization API
  slug: spade-category-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-category-personalization-api-openapi.yml
- filename: spade-feedback-and-reporting-api-openapi.yml
  format: yaml
  label: Spade Feedback and Reporting API
  slug: spade-feedback-and-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-feedback-and-reporting-api-openapi.yml
- filename: spade-merchant-action-triggers-api-openapi.yml
  format: yaml
  label: Spade Merchant Action Triggers API
  slug: spade-merchant-action-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-merchant-action-triggers-api-openapi.yml
- filename: spade-merchant-search-api-openapi.yml
  format: yaml
  label: Spade Merchant Search API
  slug: spade-merchant-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-merchant-search-api-openapi.yml
- filename: spade-transfer-enrichment-api-openapi.yml
  format: yaml
  label: Spade Transfer Enrichment API
  slug: spade-transfer-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-transfer-enrichment-api-openapi.yml
- filename: spade-universal-enrichment-api-openapi.yml
  format: yaml
  label: Spade Universal Enrichment API
  slug: spade-universal-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-universal-enrichment-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: When you request a demo, we may ask you for your name, position, company website, email address, and other information.
  - category: device
    text: We receive information about the device and software you use to access our Website, including IP address, web browser type, and operating system version.
  - category: behavioral
    text: we automatically receive information about your interactions with our Website like the pages or other content you view and the dates and times of your visits.
  - category: professional
    text: We will collect the information you choose to provide on your resume, such as your education and employment experience.
  - category: communication
    text: we may receive your name, email address, the contents of a message or attachments that you may send to us
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve Website
    text: To provide, maintain, improve, and enhance our Website
  - purpose: analytics and product development
    text: To understand and analyze how you use our Website and develop new products, services, features, and functionality
  - purpose: marketing and advertising
    text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials that may be relevant, valuable, or otherwise of interest to you
  - purpose: fraud and trust and safety
    text: To find and prevent fraud, and respond to trust and safety issues that may arise
  residency:
  - region: United States
    text: Our Website is hosted in the United States (“U.S.”) and intended for visitors located within the U.S.
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
name: Spade
provenance_date: '2026-11-10'
provider_name: Spade
provider_slug: spade
slug: spade-privacy-policy
source_date: '2026-11-10'
source_filename: spade-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.spade.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Spade\naid: spade\nurl: https://www.spade.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you request a demo, we may ask you for your name, position, company website, email address, and other\n    information.\n- category: device\n  text: We receive information about the device and software you use to access our Website, including IP address,\n    web browser type, and operating system version.\n- category: behavioral\n  text: we automatically receive information about your interactions with our Website like the pages or other\
  \ content\n    you view and the dates and times of your visits.\n- category: professional\n  text: We will collect the information you choose to provide on your resume, such as your education and employment\n    experience.\n- category: communication\n  text: we may receive your name, email address, the contents of a message or attachments that you may send to us\npurposes:\n- purpose: provide and improve Website\n  text: To provide, maintain, improve, and enhance our Website\n- purpose: analytics and product development\n  text: To understand and analyze how you use our Website and develop new products, services, features, and functionality\n- purpose: marketing and advertising\n  text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials\n    that may be relevant, valuable, or otherwise of interest to you\n- purpose: fraud and trust and safety\n  text: To find and prevent fraud, and respond to trust and safety issues that may\
  \ arise\nretention: []\nresidency:\n- region: United States\n  text: Our Website is hosted in the United States (“U.S.”) and intended for visitors located within the U.S.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spade/privacy/spade-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
summary_line: 10 quoted statements, read from Spade's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Transaction Enrichment
- Merchant Intelligence
- Payments
- Data Enrichment
- Fraud and Risk
- Fintech
- A2A
---
