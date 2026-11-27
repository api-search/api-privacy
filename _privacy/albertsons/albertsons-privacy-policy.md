---
api_specs:
- filename: albertsons-audiences-api-openapi.yml
  format: yaml
  label: albertsons Audiences API
  slug: albertsons-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-audiences-api-openapi.yml
- filename: albertsons-campaigns-api-openapi.yml
  format: yaml
  label: albertsons Campaigns API
  slug: albertsons-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-campaigns-api-openapi.yml
- filename: albertsons-performance-api-openapi.yml
  format: yaml
  label: albertsons Performance API
  slug: albertsons-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-performance-api-openapi.yml
- filename: albertsons-reporting-api-openapi.yml
  format: yaml
  label: albertsons Reporting API
  slug: albertsons-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albertsons/openapi/albertsons-reporting-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal Data is more than your name, address, and phone number - it includes all types of "identifiers" that can be linked to you.
  - category: health
    text: Medical and Health Information when you use our pharmacy or our Sincerely Health™ offerings
  - category: location
    text: Location and Motion Information (to help you find the nearest store or pharmacy, use special mobile features such as finding items or map of the store in some locations, to determine whether to provide you with content, deals, notices, or other information, and to understand the relevancy and effectiveness of our location-based services, including through our in-store displays)
  - category: financial
    text: Payment Details (when you shop in stores, order online or subscribe to our delivery services)
  - category: behavioral
    text: Inferences derived from personal data/profiling such as your purchase preferences, interests, characteristics, psychological trends, predispositions, behavior, attitudes, intelligence, abilities, and aptitudes
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Process transactions and deliver products
    text: Process and complete your transactions including, as applicable, order confirmation, billing, enrollment in our loyalty or other programs, and delivering products or Services.
  - purpose: Personalized advertising
    text: Provide advertising and marketing services, including personalized advertising.
  - purpose: AI and machine learning development
    text: Develop, train, test, operate, and improve artificial intelligence, machine learning, automated, or similar technologies, including technologies provided by our service providers, for our business purposes and to improve our products, services, customer experiences, operations, security, fraud prevention, analytics, and personalization, in accordance with applicable law.
  retention:
  - period: 60 days
    scope: License scan data for age-restricted purchases
    text: The information captured from your license is kept for 60 days, unless a shorter or longer retention period is required by law or special circumstances require us to keep it longer.
  rights:
  - right: Opt out of cookie-based sale, sharing and targeted advertising via universal opt-out signal
    text: We also recognize browser-based or device-based universal opt-out signals, such as Global Privacy Control, as requests to opt out of cookie-based sale, sharing, and targeted advertising activity on our website for that browser or device.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell or share Sincerely Health™ data with third parties unless we obtain your consent or believe that doing so is necessary to comply with applicable law or respond to valid legal process
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Albertsons
provenance_date: '2026-11-09'
provider_name: Albertsons
provider_slug: albertsons
slug: albertsons-privacy-policy
source_date: '2026-11-09'
source_filename: albertsons-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.albertsonscompanies.com:443/policies-and-disclosures/privacy-policy/default.aspx
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Albertsons\naid: albertsons\nurl: https://www.albertsonscompanies.com:443/policies-and-disclosures/privacy-policy/default.aspx\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personal Data is more than your name, address, and phone number - it includes all types of \"identifiers\"\n    that can be linked to you.\n- category: health\n  text: Medical and Health Information when you use our pharmacy or our Sincerely Health™ offerings\n- category: location\n  text: Location and Motion Information (to help you find the nearest\
  \ store or pharmacy, use special mobile features\n    such as finding items or map of the store in some locations, to determine whether to provide you with content,\n    deals, notices, or other information, and to understand the relevancy and effectiveness of our location-based\n    services, including through our in-store displays)\n- category: financial\n  text: Payment Details (when you shop in stores, order online or subscribe to our delivery services)\n- category: behavioral\n  text: Inferences derived from personal data/profiling such as your purchase preferences, interests, characteristics,\n    psychological trends, predispositions, behavior, attitudes, intelligence, abilities, and aptitudes\npurposes:\n- purpose: Process transactions and deliver products\n  text: Process and complete your transactions including, as applicable, order confirmation, billing, enrollment\n    in our loyalty or other programs, and delivering products or Services.\n- purpose: Personalized advertising\n\
  \  text: Provide advertising and marketing services, including personalized advertising.\n- purpose: AI and machine learning development\n  text: Develop, train, test, operate, and improve artificial intelligence, machine learning, automated, or similar\n    technologies, including technologies provided by our service providers, for our business purposes and to improve\n    our products, services, customer experiences, operations, security, fraud prevention, analytics, and personalization,\n    in accordance with applicable law.\nretention:\n- scope: License scan data for age-restricted purchases\n  period: 60 days\n  text: The information captured from your license is kept for 60 days, unless a shorter or longer retention period\n    is required by law or special circumstances require us to keep it longer.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right:\
  \ Opt out of cookie-based sale, sharing and targeted advertising via universal opt-out signal\n  text: We also recognize browser-based or device-based universal opt-out signals, such as Global Privacy Control,\n    as requests to opt out of cookie-based sale, sharing, and targeted advertising activity on our website for that\n    browser or device.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell or share Sincerely Health™ data with third parties unless we obtain your consent or believe\n    that doing so is necessary to comply with applicable law or respond to valid legal process\n"
source_yaml_url: https://artifacts.apis.io/albertsons/privacy/albertsons-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from Albertsons's own page on 2026-11-09.
synthetic: false
tags:
- Grocery
- Retail
- Retail Media
- Advertising
- Campaigns
- Analytics
- Consumer Goods
- Food
- Pharmacy
---
