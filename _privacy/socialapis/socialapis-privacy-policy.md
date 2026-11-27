---
api_specs:
- filename: socialapis-account-api-openapi.yml
  format: yaml
  label: SocialAPIs Account API
  slug: socialapis-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-account-api-openapi.yml
- filename: socialapis-facebook-groups-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Groups API
  slug: socialapis-facebook-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-groups-api-openapi.yml
- filename: socialapis-facebook-marketplace-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Marketplace API
  slug: socialapis-facebook-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-marketplace-api-openapi.yml
- filename: socialapis-facebook-media-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Media API
  slug: socialapis-facebook-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-media-api-openapi.yml
- filename: socialapis-facebook-pages-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Pages API
  slug: socialapis-facebook-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-pages-api-openapi.yml
- filename: socialapis-facebook-posts-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Posts API
  slug: socialapis-facebook-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-posts-api-openapi.yml
- filename: socialapis-facebook-search-api-openapi.yml
  format: yaml
  label: SocialAPIs Facebook Search API
  slug: socialapis-facebook-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-facebook-search-api-openapi.yml
- filename: socialapis-instagram-api-openapi.yml
  format: yaml
  label: SocialAPIs Instagram API
  slug: socialapis-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-instagram-api-openapi.yml
- filename: socialapis-meta-ads-library-api-openapi.yml
  format: yaml
  label: SocialAPIs Meta Ads Library API
  slug: socialapis-meta-ads-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-meta-ads-library-api-openapi.yml
- filename: socialapis-other-api-openapi.yml
  format: yaml
  label: SocialAPIs Other API
  slug: socialapis-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/socialapis/openapi/socialapis-other-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: first name, last name, email address and password (stored only as a one-way hash).'
  - category: financial
    text: 'Payment information: handled by Stripe. We receive your billing details and payment status, but never your full card number.'
  - category: communication
    text: 'Communications: messages you send to support or through the contact form.'
  - category: device
    text: The IP address and approximate country the request came from
  - category: behavioral
    text: It records page views, referrer, browser, device type and country.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: create and run your account, answer API requests, count credits and show your usage.
  - purpose: Billing
    text: process payments and keep tax and accounting records.
  - purpose: Security and improvement
    text: rate limiting, fraud and abuse prevention, debugging and improving the Service.
  - purpose: Product news
    text: To send product news (legitimate interest or consent, depending on where you live)
  residency:
  - region: European Union
    text: Our servers are in the European Union.
  retention:
  - period: 90 days
    scope: API request logs
    text: 'API request logs (including request and response bodies): deleted automatically after 90 days'
  - period: up to 10 years
    scope: Payment and invoice records
    text: 'Payment and invoice records: kept for as long as tax and accounting law requires, typically up to 10 years'
  - period: null
    scope: Account data
    text: 'Account data: kept while your account is open, and deleted or anonymized after you ask us to close it, except where we must keep it by law'
  rights:
  - right: Access
    text: Access a copy of your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your data
  - right: Portability
    text: Receive your data in a portable format
  - right: Object or restrict
    text: Object to or restrict certain processing
  - right: Withdraw consent
    text: Withdraw consent at any time, where we rely on consent
  role:
    text: SocialAPIs is the controller of your account information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the transfer relies on the safeguards those providers offer, such as the EU Standard Contractual Clauses in their data processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SocialAPIs
provenance_date: '2026-11-10'
provider_name: SocialAPIs
provider_slug: socialapis
slug: socialapis-privacy-policy
source_date: '2026-11-10'
source_filename: socialapis-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://socialapis.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SocialAPIs\naid: socialapis\nurl: https://socialapis.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: SocialAPIs is the controller of your account information.\ndata_categories:\n- category: identifying\n  text: 'Account information: first name, last name, email address and password (stored only as a one-way hash).'\n- category: financial\n  text: 'Payment information: handled by Stripe. We receive your billing details and payment status, but never your\n    full card number.'\n- category: communication\n  text: 'Communications: messages you send to support or through the contact\
  \ form.'\n- category: device\n  text: The IP address and approximate country the request came from\n- category: behavioral\n  text: It records page views, referrer, browser, device type and country.\npurposes:\n- purpose: Provide the Service\n  text: create and run your account, answer API requests, count credits and show your usage.\n- purpose: Billing\n  text: process payments and keep tax and accounting records.\n- purpose: Security and improvement\n  text: rate limiting, fraud and abuse prevention, debugging and improving the Service.\n- purpose: Product news\n  text: To send product news (legitimate interest or consent, depending on where you live)\nretention:\n- scope: API request logs\n  period: 90 days\n  text: 'API request logs (including request and response bodies): deleted automatically after 90 days'\n- scope: Payment and invoice records\n  period: up to 10 years\n  text: 'Payment and invoice records: kept for as long as tax and accounting law requires, typically up to 10\
  \ years'\n- scope: Account data\n  period: null\n  text: 'Account data: kept while your account is open, and deleted or anonymized after you ask us to close it,\n    except where we must keep it by law'\nresidency:\n- region: European Union\n  text: Our servers are in the European Union.\ntransfers:\n- mechanism: SCC\n  text: the transfer relies on the safeguards those providers offer, such as the EU Standard Contractual Clauses\n    in their data processing terms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Access a copy of your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your data\n- right: Portability\n  text: Receive your data in a portable format\n- right: Object or restrict\n  text: Object to or restrict certain processing\n- right: Withdraw consent\n  text: Withdraw consent at any time, where we rely on\
  \ consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/socialapis/privacy/socialapis-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from SocialAPIs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Data
- Developers
---
