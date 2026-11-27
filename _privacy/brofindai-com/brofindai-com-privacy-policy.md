---
api_specs:
- filename: brofindai-com-agents-api-openapi.yml
  format: yaml
  label: Bro Find AI Agents API
  slug: brofindai-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-agents-api-openapi.yml
- filename: brofindai-com-badge-api-openapi.yml
  format: yaml
  label: Bro Find AI Badge API
  slug: brofindai-com-badge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-badge-api-openapi.yml
- filename: brofindai-com-comments-api-openapi.yml
  format: yaml
  label: Bro Find AI Comments API
  slug: brofindai-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-comments-api-openapi.yml
- filename: brofindai-com-feedback-api-openapi.yml
  format: yaml
  label: Bro Find AI Feedback API
  slug: brofindai-com-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-feedback-api-openapi.yml
- filename: brofindai-com-mcp-servers-api-openapi.yml
  format: yaml
  label: Bro Find AI MCP Servers API
  slug: brofindai-com-mcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-mcp-servers-api-openapi.yml
- filename: brofindai-com-reviews-api-openapi.yml
  format: yaml
  label: Bro Find AI Reviews API
  slug: brofindai-com-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-reviews-api-openapi.yml
- filename: brofindai-com-search-api-openapi.yml
  format: yaml
  label: Bro Find AI Search API
  slug: brofindai-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-search-api-openapi.yml
- filename: brofindai-com-tools-api-openapi.yml
  format: yaml
  label: Bro Find AI Tools API
  slug: brofindai-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brofindai-com/openapi/brofindai-com-tools-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: receive your name, email address, and profile photo
  - category: contact
    text: Your address if you subscribe to the newsletter
  - category: financial
    text: we keep the order and payment ids, the product, the amount and your account
  - category: location
    text: approximate location
  - category: device
    text: browser type
  - category: behavioral
    text: pages visited, referring site, browser type, approximate location, and interactions
  - category: professional
    text: your role and company size if you choose to share them when you subscribe
  - category: other
    text: the IP address it was submitted from, to detect abuse
  deletion:
    route: email request
    text: To exercise these rights, or to request deletion of your account, email us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and improve the directory
    text: To operate, maintain, and improve the directory and its features.
  - purpose: understand site usage
    text: To understand how the site is used so we can make it better.
  - purpose: display advertising
    text: To display advertising that helps keep the site free (see below).
  - purpose: respond to support requests
    text: To respond to feedback and support requests.
  retention:
  - period: null
    scope: general data
    text: We retain information for as long as needed to provide the service and meet legal obligations
  rights:
  - right: access, correct, or delete
    text: you may have rights to access, correct, or delete your personal information
  - right: object to processing
    text: or to object to certain processing (including under the GDPR and CCPA)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Google (Firebase Authentication and Firestore, Analytics, Ads, AdSense), Supabase (the catalog and listing statistics database), Cloudflare (hosting, delivery and search), PostHog (product analytics), Razorpay (payments), Resend (email) and Discord (launch announcements).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bro Find AI
provenance_date: '2026-11-09'
provider_name: Bro Find AI
provider_slug: brofindai-com
slug: brofindai-com-privacy-policy
source_date: '2026-11-09'
source_filename: brofindai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://brofindai.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bro Find AI\naid: brofindai-com\nurl: https://brofindai.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: receive your name, email address, and profile photo\n- category: contact\n  text: Your address if you subscribe to the newsletter\n- category: financial\n  text: we keep the order and payment ids, the product, the amount and your account\n- category: location\n  text: approximate location\n- category: device\n  text: browser type\n- category: behavioral\n  text: pages visited, referring site, browser type, approximate location,\
  \ and interactions\n- category: professional\n  text: your role and company size if you choose to share them when you subscribe\n- category: other\n  text: the IP address it was submitted from, to detect abuse\npurposes:\n- purpose: operate and improve the directory\n  text: To operate, maintain, and improve the directory and its features.\n- purpose: understand site usage\n  text: To understand how the site is used so we can make it better.\n- purpose: display advertising\n  text: To display advertising that helps keep the site free (see below).\n- purpose: respond to support requests\n  text: To respond to feedback and support requests.\nretention:\n- scope: general data\n  period: null\n  text: We retain information for as long as needed to provide the service and meet legal obligations\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Google (Firebase Authentication and Firestore, Analytics, Ads, AdSense), Supabase (the catalog and listing\n    statistics database),\
  \ Cloudflare (hosting, delivery and search), PostHog (product analytics), Razorpay (payments),\n    Resend (email) and Discord (launch announcements).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: To exercise these rights, or to request deletion of your account, email us at [email protected] .\nrights:\n- right: access, correct, or delete\n  text: you may have rights to access, correct, or delete your personal information\n- right: object to processing\n  text: or to object to certain processing (including under the GDPR and CCPA)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brofindai-com/privacy/brofindai-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from Bro Find AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Directory
- Tools
- Marketplace
- Company
---
