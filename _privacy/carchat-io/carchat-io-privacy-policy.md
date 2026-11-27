---
api_specs:
- filename: carchat-io-dealers-api-openapi.yml
  format: yaml
  label: CarChat Dealers API
  slug: carchat-io-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-dealers-api-openapi.yml
- filename: carchat-io-inventory-api-openapi.yml
  format: yaml
  label: CarChat Inventory API
  slug: carchat-io-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-inventory-api-openapi.yml
- filename: carchat-io-lead-api-openapi.yml
  format: yaml
  label: CarChat Lead API
  slug: carchat-io-lead-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-lead-api-openapi.yml
- filename: carchat-io-segments-api-openapi.yml
  format: yaml
  label: CarChat Segments API
  slug: carchat-io-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-segments-api-openapi.yml
- filename: carchat-io-vehicles-api-openapi.yml
  format: yaml
  label: CarChat Vehicles API
  slug: carchat-io-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carchat-io/openapi/carchat-io-vehicles-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, phone number, email (if you give one), and your message
  - category: financial
    text: the fields you type (identity, residence, employment, income, and optionally a Social Security number and driver's license)
  - category: location
    text: we collect your name, phone, and address and send the request to the selling dealership
  - category: device
    text: Standard server logs (IP address, browser, pages viewed)
  - category: behavioral
    text: Search terms sent to our site or API (for example "used truck under $25,000")
  deletion:
    route: Email support@carchat.io to request display or deletion of an inquiry
    text: You can ask us to show you or delete any inquiry you submitted by emailing support@carchat.io from the address in the inquiry, or by including the phone number you used.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Private negotiation case
    text: For a private negotiation case, CarChat uses your information to work on your request.
  - purpose: Site operation and abuse prevention
    text: so we can keep the site working and stop abuse
  - purpose: Spam prevention
    text: we keep a copy so the dealership can follow up and so we can prevent spam
  retention:
  - period: up to 24 months
    scope: Inquiries
    text: 'Inquiries: up to 24 months from submission, then deleted.'
  - period: up to 90 days
    scope: Financing applications
    text: 'Financing applications: encrypted application data up to 90 days, then shredded.'
  - period: up to 30 days
    scope: Prequalification requests
    text: 'Prequalification requests: address and the written instruction up to 30 days, then deleted.'
  - period: up to 90 days
    scope: Server logs and search queries
    text: 'Server logs and search queries: up to 90 days.'
  rights:
  - right: Access and deletion of inquiries
    text: You can ask us to show you or delete any inquiry you submitted by emailing support@carchat.io
  - right: Response time
    text: We respond within 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not share shopper information with advertisers or data brokers, and we do not sell personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CarChat
provenance_date: '2026-11-09'
provider_name: CarChat
provider_slug: carchat-io
slug: carchat-io-privacy-policy
source_date: '2026-11-09'
source_filename: carchat-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carchat.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CarChat\naid: carchat-io\nurl: https://carchat.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your name, phone number, email (if you give one), and your message\n- category: financial\n  text: the fields you type (identity, residence, employment, income, and optionally a Social Security number and\n    driver's license)\n- category: location\n  text: we collect your name, phone, and address and send the request to the selling dealership\n- category: device\n  text: Standard server logs (IP address, browser, pages\
  \ viewed)\n- category: behavioral\n  text: Search terms sent to our site or API (for example \"used truck under $25,000\")\npurposes:\n- purpose: Private negotiation case\n  text: For a private negotiation case, CarChat uses your information to work on your request.\n- purpose: Site operation and abuse prevention\n  text: so we can keep the site working and stop abuse\n- purpose: Spam prevention\n  text: we keep a copy so the dealership can follow up and so we can prevent spam\nretention:\n- scope: Inquiries\n  period: up to 24 months\n  text: 'Inquiries: up to 24 months from submission, then deleted.'\n- scope: Financing applications\n  period: up to 90 days\n  text: 'Financing applications: encrypted application data up to 90 days, then shredded.'\n- scope: Prequalification requests\n  period: up to 30 days\n  text: 'Prequalification requests: address and the written instruction up to 30 days, then deleted.'\n- scope: Server logs and search queries\n  period: up to 90 days\n  text: 'Server\
  \ logs and search queries: up to 90 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@carchat.io to request display or deletion of an inquiry\n  text: You can ask us to show you or delete any inquiry you submitted by emailing support@carchat.io from the address\n    in the inquiry, or by including the phone number you used.\nrights:\n- right: Access and deletion of inquiries\n  text: You can ask us to show you or delete any inquiry you submitted by emailing support@carchat.io\n- right: Response time\n  text: We respond within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not share shopper information with advertisers or data brokers, and we do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/carchat-io/privacy/carchat-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from CarChat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Automotive
- Artificial Intelligence
- OpenAPI
---
