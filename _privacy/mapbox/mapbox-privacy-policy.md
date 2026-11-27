---
api_specs:
- filename: mapbox-activity-api-openapi.yml
  format: yaml
  label: Mapbox Activity API
  slug: mapbox-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-activity-api-openapi.yml
- filename: mapbox-mapbox-tiling-service-api-api-openapi.yml
  format: yaml
  label: Mapbox Tiling Service API
  slug: mapbox-mapbox-tiling-service-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-mapbox-tiling-service-api-api-openapi.yml
- filename: mapbox-tilesets-api-openapi.yml
  format: yaml
  label: Mapbox Tilesets API
  slug: mapbox-tilesets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mapbox/openapi/mapbox-tilesets-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identifiers: Such as, name, address, email, phone number, Mapbox account username.'
  - category: financial
    text: 'Financial data: Such as, credit card data is not processed by Mapbox. Instead, credit card data is processed by Stripe, a third-party PCI-certified payment service provider'
  - category: device
    text: browser and device type, (b) operating system, and (c) referring web pages
  - category: location
    text: Geolocation Data Such as latitude and longitude, altitude, horizontal and vertical accuracy
  - category: behavioral
    text: 'Inference data about an individual: Such as, services Mapbox thinks an individual may be interested in based on prior purchases or website browsing'
  - category: communication
    text: 'Conversation Data MapGPT: Microphone data (including voice inputs).'
  - category: professional
    text: 'Commercial information: Such as, transaction data including billing contact’s name, work phone number, work email, work address, professional title, and company name.'
  - category: demographic
    text: 'Employment data: Such as, education and employment history'
  deletion:
    route: Deletion request form linked on page; requests to privacy@mapbox.com
    text: To exercise your right to deletion of personal data, please complete the form here .
  dpa:
    available: true
    text: 'customers/prospective customers should read Mapbox’s data processing addendum (“DPA”): https://www.mapbox.com/legal/dpa'
    url: https://www.mapbox.com/legal/dpa
  purposes:
  - purpose: Provide, test, maintain, secure and improve websites and products
    text: Provide, test, maintain/support, secure and improve Mapbox’s websites, to prevent fraud, misuse and cyberattacks
  - purpose: Marketing communications
    text: Send marketing information, product recommendations and other non-transactional communications
  - purpose: Recruitment
    text: Create and manage the recruitment system, job applications and a database of interested individuals and leads
  - purpose: Model training
    text: Train artificial intelligence models (to the extent personal data is first de-identified)
  - purpose: Legal compliance
    text: Cooperate with public and government authorities, courts or regulators in accordance with Mapbox’s legal obligations.
  retention:
  - period: 30 days
    scope: IP addresses
    text: Mapbox retains IP addresses for 30 days
  - period: null
    scope: General personal data
    text: Mapbox stores personal data for so long as it is needed to fulfill the purposes for which it was collected
  rights:
  - right: Access/view personal data
    text: Access/view personal data
  - right: Portability
    text: Portability of personal data in a commonly machine readable format
  - right: Correct
    text: Correct personal data where it is inaccurate or incomplete
  - right: Deletion
    text: Deletion of personal data
  - right: Restrict or object
    text: Restrict or object to processing of personal data
  - right: Opt-out of sale
    text: Opt-out of the sale of personal data, if applicable, where such requests are permitted by law
  role:
    text: Mapbox processes personal data in its capacity as a data controller under the GDPR
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: certification under the EU-US Data Privacy Framework, UK Extension to the EU-US Data Privacy Framework, and the Swiss-US Data Privacy Framework
  - mechanism: SCC
    text: if required, standard contractual clauses or alternative mechanism for the transfer of data as approved by the European Commission (Art. 46 GDPR)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mapbox
provenance_date: '2026-11-10'
provider_name: Mapbox
provider_slug: mapbox
slug: mapbox-privacy-policy
source_date: '2026-11-10'
source_filename: mapbox-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mapbox.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mapbox\naid: mapbox\nurl: https://www.mapbox.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Mapbox processes personal data in its capacity as a data controller under the GDPR\ndata_categories:\n- category: identifying\n  text: 'Identifiers: Such as, name, address, email, phone number, Mapbox account username.'\n- category: financial\n  text: 'Financial data: Such as, credit card data is not processed by Mapbox. Instead, credit card data is processed\n    by Stripe, a third-party PCI-certified payment service provider'\n- category: device\n  text: browser and\
  \ device type, (b) operating system, and (c) referring web pages\n- category: location\n  text: Geolocation Data Such as latitude and longitude, altitude, horizontal and vertical accuracy\n- category: behavioral\n  text: 'Inference data about an individual: Such as, services Mapbox thinks an individual may be interested in\n    based on prior purchases or website browsing'\n- category: communication\n  text: 'Conversation Data MapGPT: Microphone data (including voice inputs).'\n- category: professional\n  text: 'Commercial information: Such as, transaction data including billing contact’s name, work phone number,\n    work email, work address, professional title, and company name.'\n- category: demographic\n  text: 'Employment data: Such as, education and employment history'\npurposes:\n- purpose: Provide, test, maintain, secure and improve websites and products\n  text: Provide, test, maintain/support, secure and improve Mapbox’s websites, to prevent fraud, misuse and cyberattacks\n-\
  \ purpose: Marketing communications\n  text: Send marketing information, product recommendations and other non-transactional communications\n- purpose: Recruitment\n  text: Create and manage the recruitment system, job applications and a database of interested individuals and\n    leads\n- purpose: Model training\n  text: Train artificial intelligence models (to the extent personal data is first de-identified)\n- purpose: Legal compliance\n  text: Cooperate with public and government authorities, courts or regulators in accordance with Mapbox’s legal\n    obligations.\nretention:\n- scope: IP addresses\n  period: 30 days\n  text: Mapbox retains IP addresses for 30 days\n- scope: General personal data\n  period: null\n  text: Mapbox stores personal data for so long as it is needed to fulfill the purposes for which it was collected\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: certification under the EU-US Data Privacy Framework, UK Extension to the EU-US Data Privacy Framework,\n\
  \    and the Swiss-US Data Privacy Framework\n- mechanism: SCC\n  text: if required, standard contractual clauses or alternative mechanism for the transfer of data as approved\n    by the European Commission (Art. 46 GDPR)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://www.mapbox.com/legal/dpa\n  text: 'customers/prospective customers should read Mapbox’s data processing addendum (“DPA”): https://www.mapbox.com/legal/dpa'\ndeletion:\n  route: Deletion request form linked on page; requests to privacy@mapbox.com\n  text: To exercise your right to deletion of personal data, please complete the form here .\nrights:\n- right: Access/view personal data\n  text: Access/view personal data\n- right: Portability\n  text: Portability of personal data in a commonly machine readable format\n- right: Correct\n  text: Correct personal data where it is inaccurate or incomplete\n- right: Deletion\n  text: Deletion of personal data\n- right: Restrict or object\n  text:\
  \ Restrict or object to processing of personal data\n- right: Opt-out of sale\n  text: Opt-out of the sale of personal data, if applicable, where such requests are permitted by law\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mapbox/privacy/mapbox-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 26 quoted statements, read from Mapbox's own page on 2026-11-10.
synthetic: false
tags:
- Mapping
- Maps
- Geospatial
- Location
- Geocoding
- Routing
---
