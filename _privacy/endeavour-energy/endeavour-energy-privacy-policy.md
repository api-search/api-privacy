---
api_specs:
- filename: endeavour-energy-catalog-api-openapi.yml
  format: yaml
  label: Endeavour Energy Catalog API
  slug: endeavour-energy-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endeavour-energy/openapi/endeavour-energy-catalog-api-openapi.yml
- filename: endeavour-energy-dataset-api-openapi.yml
  format: yaml
  label: Endeavour Energy Dataset API
  slug: endeavour-energy-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/endeavour-energy/openapi/endeavour-energy-dataset-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: your name, contact information (including your email address, home address, business address and telephone numbers)
  - category: financial
    text: bank details (including BSB, account number and account holder)
  - category: location
    text: your NMI address (the meter location which may be the same as your personal address)
  - category: behavioral
    text: information about your electricity usage patterns
  - category: biometric
    text: images of you via CCTV cameras
  - category: health
    text: We will only collect and use health information where you have provided your consent.
  - category: identifying
    text: National Meter Identifier (NMI)
  deletion:
    route: null
    text: When personal information is no longer required, the personal information is destroyed in accordance with Endeavour Energy's policies and internal processes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: supplying customers with services and products
    text: We collect and hold personal information that is reasonably necessary for the purpose of supplying customers with our services and products.
  - purpose: direct marketing
    text: We may also collect, hold, use and disclose personal information for the purpose of telling you from time to time about our services, products or promotions.
  - purpose: website development
    text: Web usage information is collected to assist us to build and develop our website to best meet customer needs
  residency:
  - region: Australia
    text: We do not typically disclose personal information outside of Australia.
  - region: New South Wales
    text: With respect to health information, we typically do not disclose health information outside of New South Wales.
  retention:
  - period: null
    scope: personal information no longer required
    text: When personal information is no longer required, the personal information is destroyed in accordance with Endeavour Energy's policies and internal processes.
  rights:
  - right: access
    text: you have a right to seek access to personal information including health information which we hold about you
  - right: correction
    text: You also have the right to ask us to correct information about you, which is inaccurate, incomplete, out of date, irrelevant or misleading.
  - right: opt out of marketing
    text: you can opt out by clicking on the opt-out function included in each marketing message.
  - right: complain
    text: you may take your privacy-related complaint to the Office of the Australian Information Commissioner (OAIC)
  role:
    text: Endeavour Energy is bound by the Privacy Act 1988 (Cth) (the Privacy Act ), including the Australian Privacy Principles ( APPs )
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Endeavour Energy
provenance_date: '2026-11-09'
provider_name: Endeavour Energy
provider_slug: endeavour-energy
slug: endeavour-energy-privacy-policy
source_date: '2026-11-09'
source_filename: endeavour-energy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.endeavourenergy.com.au/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Endeavour Energy\naid: endeavour-energy\nurl: https://www.endeavourenergy.com.au/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Endeavour Energy is bound by the Privacy Act 1988 (Cth) (the Privacy Act ), including the Australian Privacy\n    Principles ( APPs )\ndata_categories:\n- category: contact\n  text: your name, contact information (including your email address, home address, business address and telephone\n    numbers)\n- category: financial\n  text: bank details (including BSB, account number and account holder)\n- category: location\n  text: your NMI address (the meter\
  \ location which may be the same as your personal address)\n- category: behavioral\n  text: information about your electricity usage patterns\n- category: biometric\n  text: images of you via CCTV cameras\n- category: health\n  text: We will only collect and use health information where you have provided your consent.\n- category: identifying\n  text: National Meter Identifier (NMI)\npurposes:\n- purpose: supplying customers with services and products\n  text: We collect and hold personal information that is reasonably necessary for the purpose of supplying customers\n    with our services and products.\n- purpose: direct marketing\n  text: We may also collect, hold, use and disclose personal information for the purpose of telling you from time\n    to time about our services, products or promotions.\n- purpose: website development\n  text: Web usage information is collected to assist us to build and develop our website to best meet customer needs\nretention:\n- scope: personal information\
  \ no longer required\n  period: null\n  text: When personal information is no longer required, the personal information is destroyed in accordance with\n    Endeavour Energy's policies and internal processes.\nresidency:\n- region: Australia\n  text: We do not typically disclose personal information outside of Australia.\n- region: New South Wales\n  text: With respect to health information, we typically do not disclose health information outside of New South\n    Wales.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: When personal information is no longer required, the personal information is destroyed in accordance with\n    Endeavour Energy's policies and internal processes.\nrights:\n- right: access\n  text: you have a right to seek access to personal information including health information which we hold about\n    you\n- right: correction\n  text: You also have the right to ask us to\
  \ correct information about you, which is inaccurate, incomplete, out\n    of date, irrelevant or misleading.\n- right: opt out of marketing\n  text: you can opt out by clicking on the opt-out function included in each marketing message.\n- right: complain\n  text: you may take your privacy-related complaint to the Office of the Australian Information Commissioner (OAIC)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/endeavour-energy/privacy/endeavour-energy-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Endeavour Energy's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Australia
- Utilities
- Electricity
- Grid
- Open Data
- Energy Networks
- Distribution
- Outages
- Consumer Data Right
- Smart Metering
- DER
- Solar
- Renewables
---
