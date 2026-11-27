---
api_specs:
- filename: epcor-boundaries-api-openapi.yml
  format: yaml
  label: EPCOR Boundaries API
  slug: epcor-boundaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-boundaries-api-openapi.yml
- filename: epcor-catalog-api-openapi.yml
  format: yaml
  label: EPCOR Catalog API
  slug: epcor-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-catalog-api-openapi.yml
- filename: epcor-infrastructure-api-openapi.yml
  format: yaml
  label: EPCOR Infrastructure API
  slug: epcor-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-infrastructure-api-openapi.yml
- filename: epcor-power-outages-api-openapi.yml
  format: yaml
  label: EPCOR Power Outages API
  slug: epcor-power-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-power-outages-api-openapi.yml
- filename: epcor-service-areas-api-openapi.yml
  format: yaml
  label: EPCOR Service Areas API
  slug: epcor-service-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-service-areas-api-openapi.yml
- filename: epcor-us-water-outages-api-openapi.yml
  format: yaml
  label: EPCOR Us Water Outages API
  slug: epcor-us-water-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-us-water-outages-api-openapi.yml
- filename: epcor-water-outages-api-openapi.yml
  format: yaml
  label: EPCOR Water Outages API
  slug: epcor-water-outages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/epcor/openapi/epcor-water-outages-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information (name, address, email address and telephone numbers)
  - category: identifying
    text: Personal identification
  - category: financial
    text: Credit history
  - category: financial
    text: Bank account details (for Automatic Withdrawal)
  - category: other
    text: Legal documents (death certificates, proof of ownership or lease)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Confirm customer identity and credit history
    text: Confirm customer identity and credit history
  - purpose: Provide ongoing service
    text: Provide customers with ongoing service
  - purpose: Understand customer needs and preferences
    text: Understand customer needs and preferences
  - purpose: Develop, enhance, market or provide products or services
    text: Develop, enhance, market or provide EPCOR's products or services
  - purpose: Meet legal and regulatory requirements
    text: Meet legal and regulatory requirements
  retention:
  - period: null
    scope: personal information
    text: Will only keep your personal information as long as reasonably required
  rights:
  - right: access
    text: We will give you access to the information that we have about you.
  - right: refuse or withdraw consent
    text: You may, at any time, refuse or withdraw your consent.
  - right: removal from marketing lists
    text: You may also have your name removed from our marketing lists.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never disclose, sell, lease or trade your information unless you authorize us to do so, or it's required or permitted by law.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EPCOR
provenance_date: '2026-11-09'
provider_name: EPCOR
provider_slug: epcor
slug: epcor-privacy-policy
source_date: '2026-11-09'
source_filename: epcor-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.epcor.com/ca/en/about/policies/privacy-policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EPCOR\naid: epcor\nurl: https://www.epcor.com/ca/en/about/policies/privacy-policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Contact information (name, address, email address and telephone numbers)\n- category: identifying\n  text: Personal identification\n- category: financial\n  text: Credit history\n- category: financial\n  text: Bank account details (for Automatic Withdrawal)\n- category: other\n  text: Legal documents (death certificates, proof of ownership or lease)\npurposes:\n- purpose: Confirm customer identity and credit\
  \ history\n  text: Confirm customer identity and credit history\n- purpose: Provide ongoing service\n  text: Provide customers with ongoing service\n- purpose: Understand customer needs and preferences\n  text: Understand customer needs and preferences\n- purpose: Develop, enhance, market or provide products or services\n  text: Develop, enhance, market or provide EPCOR's products or services\n- purpose: Meet legal and regulatory requirements\n  text: Meet legal and regulatory requirements\nretention:\n- scope: personal information\n  period: null\n  text: Will only keep your personal information as long as reasonably required\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: We will give you access to the information that we have about you.\n- right: refuse or withdraw consent\n  text: You may, at any time, refuse or withdraw your consent.\n\
  - right: removal from marketing lists\n  text: You may also have your name removed from our marketing lists.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never disclose, sell, lease or trade your information unless you authorize us to do so, or it's\n    required or permitted by law.\n"
source_yaml_url: https://artifacts.apis.io/epcor/privacy/epcor-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from EPCOR's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Natural Gas
- Water
- Green Button
- Smart Metering
- Grid
- Ontario
- Alberta
- Outages
- Geospatial
- Open Data
---
