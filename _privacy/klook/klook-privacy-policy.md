---
api_specs:
- filename: klook-availability-api-openapi.yml
  format: yaml
  label: Klook Availability API
  slug: klook-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-availability-api-openapi.yml
- filename: klook-bookings-api-openapi.yml
  format: yaml
  label: Klook Bookings API
  slug: klook-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-bookings-api-openapi.yml
- filename: klook-products-api-openapi.yml
  format: yaml
  label: Klook Products API
  slug: klook-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-products-api-openapi.yml
- filename: klook-supplier-api-openapi.yml
  format: yaml
  label: Klook Supplier API
  slug: klook-supplier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/klook/openapi/klook-supplier-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information such as your first name and surname, date of birth, email address, phone number, postal address, country and region of residence
  - category: financial
    text: any necessary billing and payment information such as credit card details, billing address and bank account numbers
  - category: location
    text: Information such as data inferred from your IP address, name of telecommunication operator/carrier, SIM region and network and other geo-positioning data.
  - category: behavioral
    text: information relating to previous purchases and bookings and any other information relevant to travel preferences and itinerary details
  - category: communication
    text: Information such as communications between Klook and you or between you and Operators.
  deletion:
    route: privacy@klook.com
    text: 'you may contact Klook at the following email address: privacy@klook.com or file a request in writing to our privacy team'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Klook Services
    text: fulfilling your reservations, rentals and or bookings
  - purpose: Marketing
    text: For providing you with marketing messages from Klook
  - purpose: Targeted advertising
    text: We use advertising services and products provided by third party service providers (such as marketing agencies and social media platforms) for marketing and promotional purposes
  - purpose: Legal and administrative
    text: To comply with legal obligations and for administrative purposes such as verifying and processing payment, issuing invoices, screening against fraud
  retention:
  - period: null
    scope: Personal data
    text: Klook will only retain your personal data for as long as is necessary to serve the purposes as set out above in section 3, or to comply with the relevant legal requirements.
  rights:
  - right: Access
    text: You have the right to access personal data that Klook holds about you and request Klook to send you a copy of such personal data processed
  - right: Correction
    text: to correct any personal data that is inaccurate or incomplete
  - right: Erasure
    text: to delete your personal data, subject to certain exceptions
  - right: Withdraw consent
    text: You have the right to withdraw consent and request that Klook stops using and/or disclosing your personal data
  - right: Object to direct marketing
    text: You also have the right to ask us not to process your personal data for direct marketing purposes.
  - right: Portability
    text: Right to data portability - You have the right to receive the personal data concerning you
  - right: Complaint
    text: You also have the right to lodge a complaint about our processing of your personal data with the data protection authority in your country or region.
  role:
    text: as a data controller
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: standard contractual clauses of the European Commission
  - mechanism: DPF
    text: the EU-US, Switzerland-US, EU-UK privacy shield
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Klook
provenance_date: '2026-11-09'
provider_name: Klook
provider_slug: klook
slug: klook-privacy-policy
source_date: '2026-11-09'
source_filename: klook-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.klook.com/en-US/policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Klook\naid: klook\nurl: https://www.klook.com/en-US/policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: as a data controller\ndata_categories:\n- category: identifying\n  text: Information such as your first name and surname, date of birth, email address, phone number, postal address,\n    country and region of residence\n- category: financial\n  text: any necessary billing and payment information such as credit card details, billing address and bank account\n    numbers\n- category: location\n  text: Information such as data inferred from your IP address, name of telecommunication operator/carrier,\
  \ SIM\n    region and network and other geo-positioning data.\n- category: behavioral\n  text: information relating to previous purchases and bookings and any other information relevant to travel preferences\n    and itinerary details\n- category: communication\n  text: Information such as communications between Klook and you or between you and Operators.\npurposes:\n- purpose: Provide Klook Services\n  text: fulfilling your reservations, rentals and or bookings\n- purpose: Marketing\n  text: For providing you with marketing messages from Klook\n- purpose: Targeted advertising\n  text: We use advertising services and products provided by third party service providers (such as marketing agencies\n    and social media platforms) for marketing and promotional purposes\n- purpose: Legal and administrative\n  text: To comply with legal obligations and for administrative purposes such as verifying and processing payment,\n    issuing invoices, screening against fraud\nretention:\n- scope: Personal\
  \ data\n  period: null\n  text: Klook will only retain your personal data for as long as is necessary to serve the purposes as set out above\n    in section 3, or to comply with the relevant legal requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: standard contractual clauses of the European Commission\n- mechanism: DPF\n  text: the EU-US, Switzerland-US, EU-UK privacy shield\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy@klook.com\n  text: 'you may contact Klook at the following email address: privacy@klook.com or file a request in writing to\n    our privacy team'\nrights:\n- right: Access\n  text: You have the right to access personal data that Klook holds about you and request Klook to send you a copy\n    of such personal data processed\n- right: Correction\n  text: to correct any personal data that is inaccurate or incomplete\n- right: Erasure\n  text: to delete your personal data, subject\
  \ to certain exceptions\n- right: Withdraw consent\n  text: You have the right to withdraw consent and request that Klook stops using and/or disclosing your personal\n    data\n- right: Object to direct marketing\n  text: You also have the right to ask us not to process your personal data for direct marketing purposes.\n- right: Portability\n  text: Right to data portability - You have the right to receive the personal data concerning you\n- right: Complaint\n  text: You also have the right to lodge a complaint about our processing of your personal data with the data protection\n    authority in your country or region.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/klook/privacy/klook-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from Klook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Travel
- Tours and Activities
- Booking
- Experience
- Distribution
- OCTO
- Hospitality
---
