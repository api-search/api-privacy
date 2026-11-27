---
api_specs:
- filename: appmanai-com-app-metadata-api-openapi.yml
  format: yaml
  label: AppManAi App Metadata API
  slug: appmanai-com-app-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-metadata-api-openapi.yml
- filename: appmanai-com-app-metrics-api-openapi.yml
  format: yaml
  label: AppManAi App Metrics API
  slug: appmanai-com-app-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-metrics-api-openapi.yml
- filename: appmanai-com-app-reviews-api-openapi.yml
  format: yaml
  label: AppManAi App Reviews API
  slug: appmanai-com-app-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-reviews-api-openapi.yml
- filename: appmanai-com-app-search-api-openapi.yml
  format: yaml
  label: AppManAi App Search API
  slug: appmanai-com-app-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appmanai-com/openapi/appmanai-com-app-search-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up we store your name, email address, and — if you use social login (Google or Apple) — the account identifier returned by that provider.
  - category: financial
    text: We store your customer identifier, plan and credit balance, and a record of your transactions.
  - category: behavioral
    text: we log the request (endpoint, timestamp, credits spent, response status and a request identifier)
  - category: device
    text: we automatically receive your IP address, browser and device information, and diagnostic logs.
  - category: communication
    text: Our product emails contain a small image and tracked links, so we can see whether an email was opened and which links were clicked.
  - category: behavioral
    text: we note the referring site, the landing page, and any campaign tags in the link (such as utm_source or an ad click identifier).
  deletion:
    route: Email or request account deletion
    text: You can ask us to delete your account at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate and maintain the Service, including authentication and API metering.
  - purpose: Process payments
    text: Process payments, manage credits, and send billing-related messages.
  - purpose: Security
    text: Secure the Service — detect, prevent and respond to fraud, abuse and technical issues.
  - purpose: Marketing email
    text: 'Email you about the Service: setup tips, notices about your credits and plan, and occasional offers.'
  retention:
  - period: null
    scope: Account and billing records
    text: We keep account and billing records for as long as your account is active and for as long afterwards as needed to meet legal, tax and accounting obligations.
  - period: null
    scope: Usage logs
    text: Usage logs are retained for a limited period for security and support, then deleted or anonymised.
  rights:
  - right: access
    text: you may have the right to access, correct, delete, or export your personal data
  - right: object or restrict
    text: to object to or restrict certain processing, and to withdraw consent
  - right: non-discrimination (CCPA/CPRA)
    text: including the right not to be discriminated against for exercising them
  - right: complain to authority
    text: You also have the right to complain to your local data-protection authority.
  role:
    text: AppmanAi operates the Service and acts as the “data controller” for the personal data described below.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Stripe — payment processing and tax. · Google and Apple — only if you choose social login. · Hosting, CDN and email providers — to serve, secure and communicate about the Service.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, such transfers are covered by appropriate safeguards such as the European Commission’s Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AppManAi
provenance_date: '2026-11-09'
provider_name: AppManAi
provider_slug: appmanai-com
slug: appmanai-com-privacy-policy
source_date: '2026-11-09'
source_filename: appmanai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://appmanai.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AppManAi\naid: appmanai-com\nurl: https://appmanai.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AppmanAi operates the Service and acts as the “data controller” for the personal data described below.\ndata_categories:\n- category: identifying\n  text: When you sign up we store your name, email address, and — if you use social login (Google or Apple) — the\n    account identifier returned by that provider.\n- category: financial\n  text: We store your customer identifier, plan and credit balance, and a record of your transactions.\n- category: behavioral\n  text: we log the request\
  \ (endpoint, timestamp, credits spent, response status and a request identifier)\n- category: device\n  text: we automatically receive your IP address, browser and device information, and diagnostic logs.\n- category: communication\n  text: Our product emails contain a small image and tracked links, so we can see whether an email was opened and\n    which links were clicked.\n- category: behavioral\n  text: we note the referring site, the landing page, and any campaign tags in the link (such as utm_source or an\n    ad click identifier).\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate and maintain the Service, including authentication and API metering.\n- purpose: Process payments\n  text: Process payments, manage credits, and send billing-related messages.\n- purpose: Security\n  text: Secure the Service — detect, prevent and respond to fraud, abuse and technical issues.\n- purpose: Marketing email\n  text: 'Email you about the Service: setup tips, notices\
  \ about your credits and plan, and occasional offers.'\nretention:\n- scope: Account and billing records\n  period: null\n  text: We keep account and billing records for as long as your account is active and for as long afterwards as\n    needed to meet legal, tax and accounting obligations.\n- scope: Usage logs\n  period: null\n  text: Usage logs are retained for a limited period for security and support, then deleted or anonymised.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, such transfers are covered by appropriate safeguards such as the European Commission’s Standard\n    Contractual Clauses.\nsubprocessors:\n  url: null\n  text: Stripe — payment processing and tax. · Google and Apple — only if you choose social login. · Hosting, CDN\n    and email providers — to serve, secure and communicate about the Service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email or request account deletion\n  text: You can ask us to delete your account\
  \ at any time.\nrights:\n- right: access\n  text: you may have the right to access, correct, delete, or export your personal data\n- right: object or restrict\n  text: to object to or restrict certain processing, and to withdraw consent\n- right: non-discrimination (CCPA/CPRA)\n  text: including the right not to be discriminated against for exercising them\n- right: complain to authority\n  text: You also have the right to complain to your local data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/appmanai-com/privacy/appmanai-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from AppManAi's own page on 2026-11-09.
synthetic: false
tags:
- App Store Data
- Google Play Data
- ASO
- Data API
- App Intelligence
---
