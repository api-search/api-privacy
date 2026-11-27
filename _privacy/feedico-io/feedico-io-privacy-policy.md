---
api_specs:
- filename: feedico-io-auth-api-openapi.yml
  format: yaml
  label: feedico-io Auth API
  slug: feedico-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-auth-api-openapi.yml
- filename: feedico-io-catalog-api-openapi.yml
  format: yaml
  label: feedico-io Catalog API
  slug: feedico-io-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-catalog-api-openapi.yml
- filename: feedico-io-coupons-api-openapi.yml
  format: yaml
  label: feedico-io Coupons API
  slug: feedico-io-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-coupons-api-openapi.yml
- filename: feedico-io-firms-api-openapi.yml
  format: yaml
  label: feedico-io Firms API
  slug: feedico-io-firms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-firms-api-openapi.yml
- filename: feedico-io-global-catalogue-api-openapi.yml
  format: yaml
  label: feedico-io Global catalogue API
  slug: feedico-io-global-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-global-catalogue-api-openapi.yml
- filename: feedico-io-health-api-openapi.yml
  format: yaml
  label: feedico-io Health API
  slug: feedico-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-health-api-openapi.yml
- filename: feedico-io-products-api-openapi.yml
  format: yaml
  label: feedico-io Products API
  slug: feedico-io-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-products-api-openapi.yml
- filename: feedico-io-user-api-openapi.yml
  format: yaml
  label: feedico-io User API
  slug: feedico-io-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/feedico-io/openapi/feedico-io-user-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, work email, company name, job function when you provide them
  - category: contact
    text: name and email used for receipts
  - category: financial
    text: plan and term, amounts, currency, payment status, and tax identifiers if you supply them
  - category: location
    text: approximate location derived from IP
  - category: device
    text: IP address, device and browser type, approximate location derived from IP, timestamps, pages viewed
  - category: behavioral
    text: pages viewed, API request metadata, error logs
  - category: communication
    text: content of emails or in-app messages you send us, and records of support interactions
  deletion:
    route: contact us using the details below
    text: To exercise rights, contact us using the details below.
  dpa:
    available: null
    text: Where we act as a processor for an enterprise customer, their instructions and data processing agreement also apply.
    url: null
  purposes:
  - purpose: providing and improving the Services
    text: 'We process personal data for: providing and improving the Services'
  - purpose: security and abuse prevention
    text: security, debugging, and abuse prevention
  - purpose: legitimate interests in aggregate product usage
    text: understanding product usage in aggregate
  - purpose: affiliate click crediting
    text: to credit the sale and to filter invalid traffic
  retention:
  - period: null
    scope: account data
    text: Account data is kept while your account is active and for a reasonable period afterward.
  - period: null
    scope: technical logs
    text: Technical logs may be retained for a shorter rolling window unless longer retention is needed for security investigations.
  rights:
  - right: access
    text: you may have the right to access, rectify, erase, restrict, or object to processing of your personal data
  - right: portability
    text: to data portability
  - right: withdraw consent
    text: to withdraw consent where processing is consent-based
  - right: complaint
    text: You may lodge a complaint with a supervisory authority.
  role:
    text: The controller of personal data collected through this website and direct sign-up flows is Feedico.io
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A list of key subprocessors is available on request for enterprise customers or as published on our site.
    url: null
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards such as Standard Contractual Clauses or other mechanisms permitted by law
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: feedico-io
provenance_date: '2026-11-09'
provider_name: feedico-io
provider_slug: feedico-io
slug: feedico-io-privacy-policy
source_date: '2026-11-09'
source_filename: feedico-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://feedico.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: feedico-io\naid: feedico-io\nurl: https://feedico.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of personal data collected through this website and direct sign-up flows is Feedico.io\ndata_categories:\n- category: identifying\n  text: name, work email, company name, job function when you provide them\n- category: contact\n  text: name and email used for receipts\n- category: financial\n  text: plan and term, amounts, currency, payment status, and tax identifiers if you supply them\n- category: location\n  text: approximate location derived from IP\n- category: device\n\
  \  text: IP address, device and browser type, approximate location derived from IP, timestamps, pages viewed\n- category: behavioral\n  text: pages viewed, API request metadata, error logs\n- category: communication\n  text: content of emails or in-app messages you send us, and records of support interactions\npurposes:\n- purpose: providing and improving the Services\n  text: 'We process personal data for: providing and improving the Services'\n- purpose: security and abuse prevention\n  text: security, debugging, and abuse prevention\n- purpose: legitimate interests in aggregate product usage\n  text: understanding product usage in aggregate\n- purpose: affiliate click crediting\n  text: to credit the sale and to filter invalid traffic\nretention:\n- scope: account data\n  period: null\n  text: Account data is kept while your account is active and for a reasonable period afterward.\n- scope: technical logs\n  period: null\n  text: Technical logs may be retained for a shorter rolling\
  \ window unless longer retention is needed for security\n    investigations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards such as Standard Contractual Clauses or other mechanisms permitted by law\nsubprocessors:\n  url: null\n  text: A list of key subprocessors is available on request for enterprise customers or as published on our site.\ndpa:\n  available: null\n  url: null\n  text: Where we act as a processor for an enterprise customer, their instructions and data processing agreement\n    also apply.\ndeletion:\n  route: contact us using the details below\n  text: To exercise rights, contact us using the details below.\nrights:\n- right: access\n  text: you may have the right to access, rectify, erase, restrict, or object to processing of your personal data\n- right: portability\n  text: to data portability\n- right: withdraw consent\n  text: to withdraw consent where processing is consent-based\n- right: complaint\n  text: You may lodge a complaint\
  \ with a supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/feedico-io/privacy/feedico-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 22 quoted statements, read from feedico-io's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- Marketing
- E-Commerce
- Coupons
---
