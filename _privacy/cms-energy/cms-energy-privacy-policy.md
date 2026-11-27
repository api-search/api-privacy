---
api_specs:
- filename: cms-energy-authorizations-api-openapi.yml
  format: yaml
  label: CMS Energy Authorizations API
  slug: cms-energy-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-authorizations-api-openapi.yml
- filename: cms-energy-bills-api-openapi.yml
  format: yaml
  label: CMS Energy Bills API
  slug: cms-energy-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-bills-api-openapi.yml
- filename: cms-energy-greenbutton-api-openapi.yml
  format: yaml
  label: CMS Energy GreenButton API
  slug: cms-energy-greenbutton-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-greenbutton-api-openapi.yml
- filename: cms-energy-intervals-api-openapi.yml
  format: yaml
  label: CMS Energy Intervals API
  slug: cms-energy-intervals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-intervals-api-openapi.yml
- filename: cms-energy-meters-api-openapi.yml
  format: yaml
  label: CMS Energy Meters API
  slug: cms-energy-meters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-meters-api-openapi.yml
- filename: cms-energy-outage-map-api-openapi.yml
  format: yaml
  label: Consumers Energy Outage Map ArcGIS REST API
  slug: cms-energy-outage-map-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-outage-map-api-openapi.yml
- filename: cms-energy-catalog-api-openapi.yml
  format: yaml
  label: CMS Energy Catalog API
  slug: cms-energy-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-catalog-api-openapi.yml
- filename: cms-energy-service-dashboard-api-openapi.yml
  format: yaml
  label: CMS Energy Service Dashboard API
  slug: cms-energy-service-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cms-energy/openapi/cms-energy-service-dashboard-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information that allows us to communicate with you, including your name, address, telephone number and email address.
  - category: behavioral
    text: behavioral Information (e.g. how you have interacted with the website or app, mouse or touch movements, scrolls, mouse clicks, screen taps or zoom information; time of engagement, etc.).
  - category: location
    text: Electric and natural gas Consumption Data gathered by our metering systems
  deletion:
    route: null
    text: Once data is no longer needed for these purposes it is destroyed according to Company data retention schedules and in a manner consistent with Information Governance best practices.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services requested
    text: We use your information to provide you with the services you request, to provide customer service, and to improve website customer experience.
  - purpose: Primary Purposes
    text: We use information collected from you to fulfill the Primary Purpose for which it is collected to provide the requested service.
  retention:
  - period: null
    scope: customer data
    text: We keep customer data as long as necessary to provide you with energy services and to comply with Michigan Public Service Commission and other regulatory requirements.
  rights:
  - right: access
    text: You have a right to know what information Consumers Energy maintains about you, except for proprietary data or that which is used for internal Consumers Energy business purposes only.
  - right: correction
    text: if you believe we may have incorrect data associated with you or your account, please call Customer Service at 1-800-477-5050.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We will not sell your information, except in connection with sales of certain aged receivables to collection firms for purposes of removing this liability from its accounts.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CMS Energy
provenance_date: '2026-11-09'
provider_name: CMS Energy
provider_slug: cms-energy
slug: cms-energy-privacy-policy
source_date: '2026-11-09'
source_filename: cms-energy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.consumersenergy.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CMS Energy\naid: cms-energy\nurl: https://www.consumersenergy.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact information that allows us to communicate with you, including your name, address, telephone number\n    and email address.\n- category: behavioral\n  text: behavioral Information (e.g. how you have interacted with the website or app, mouse or touch movements,\n    scrolls, mouse clicks, screen taps or zoom information; time of engagement, etc.).\n- category: location\n  text: Electric and natural gas Consumption\
  \ Data gathered by our metering systems\npurposes:\n- purpose: provide services requested\n  text: We use your information to provide you with the services you request, to provide customer service, and to\n    improve website customer experience.\n- purpose: Primary Purposes\n  text: We use information collected from you to fulfill the Primary Purpose for which it is collected to provide\n    the requested service.\nretention:\n- scope: customer data\n  period: null\n  text: We keep customer data as long as necessary to provide you with energy services and to comply with Michigan\n    Public Service Commission and other regulatory requirements.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Once data is no longer needed for these purposes it is destroyed according to Company data retention schedules\n    and in a manner consistent with Information Governance best practices.\n\
  rights:\n- right: access\n  text: You have a right to know what information Consumers Energy maintains about you, except for proprietary data\n    or that which is used for internal Consumers Energy business purposes only.\n- right: correction\n  text: if you believe we may have incorrect data associated with you or your account, please call Customer Service\n    at 1-800-477-5050.\nsale_or_sharing:\n  stance: conditional\n  text: We will not sell your information, except in connection with sales of certain aged receivables to collection\n    firms for purposes of removing this liability from its accounts.\n"
source_yaml_url: https://artifacts.apis.io/cms-energy/privacy/cms-energy-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from CMS Energy's own page on 2026-11-09.
synthetic: false
tags:
- Electric
- Energy
- Green Button
- Michigan
- Natural Gas
- Utility
- Fortune 500
---
