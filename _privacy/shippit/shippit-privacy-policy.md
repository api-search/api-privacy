---
api_specs:
- filename: shippit-book-api-openapi.yml
  format: yaml
  label: Shippit Book API
  slug: shippit-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-book-api-openapi.yml
- filename: shippit-label-api-openapi.yml
  format: yaml
  label: Shippit Label API
  slug: shippit-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-label-api-openapi.yml
- filename: shippit-merchant-api-openapi.yml
  format: yaml
  label: Shippit Merchant API
  slug: shippit-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-merchant-api-openapi.yml
- filename: shippit-orders-api-openapi.yml
  format: yaml
  label: Shippit Orders API
  slug: shippit-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-orders-api-openapi.yml
- filename: shippit-quote-api-openapi.yml
  format: yaml
  label: Shippit Quote API
  slug: shippit-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-quote-api-openapi.yml
- filename: shippit-tracking-api-openapi.yml
  format: yaml
  label: Shippit Tracking API
  slug: shippit-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shippit/openapi/shippit-tracking-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: your name and contact details, such as your physical/mailing address, work address, social media handles, email address and phone number
  - category: financial
    text: your payment information (such as your bank account details and payment card information)
  - category: device
    text: the type of device you use; your device’s unique ID; the IP address of your device
  - category: behavioral
    text: the pages of our Website that you visit, the time and date of your visit, the time spent on those pages
  - category: professional
    text: your company name (if applicable) and your job title
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: order fulfilment and delivery
    text: enable you to access and use Shippit’s services and our Website, including order fulfilment, delivery of goods to parcel recipients and the processing of refunds
  - purpose: fraud checks
    text: conduct fraud checks
  - purpose: marketing
    text: conducting marketing activities e.g. promoting new service offerings or inviting you to events
  - purpose: service improvement
    text: develop, operate and improve our service and organisational processes
  residency:
  - region: country of collection
    text: We endeavour to retain your information and personal information on servers located in your country.
  rights:
  - right: withdraw consent
    text: You have the right to withdraw your consent at any time by contacting our Privacy / Data Protection Officer
  - right: opt out of marketing
    text: You can choose to not receive these communications from us at any time and you may opt out by following the opt-out instructions
  - right: complaint to data protection authority
    text: you have the right to contact the relevant local data protection authority to lodge a complaint
  role:
    text: we comply with the General Data Protection Regulation 2016/679 ( GDPR ) and act as a "data controller" of that personal information
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We will not sell your personal information to other people
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we will take reasonable steps to ensure that the third party does not breach the privacy obligations relating to your personal information (e.g. by entering into an enforceable contractual arrangement with the overseas recipient
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Shippit
provenance_date: '2026-11-10'
provider_name: Shippit
provider_slug: shippit
slug: shippit-privacy-policy
source_date: '2026-11-10'
source_filename: shippit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.shippit.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Shippit\naid: shippit\nurl: https://www.shippit.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: we comply with the General Data Protection Regulation 2016/679 ( GDPR ) and act as a \"data controller\" of\n    that personal information\ndata_categories:\n- category: contact\n  text: your name and contact details, such as your physical/mailing address, work address, social media handles,\n    email address and phone number\n- category: financial\n  text: your payment information (such as your bank account details and payment card information)\n- category: device\n  text: the\
  \ type of device you use; your device’s unique ID; the IP address of your device\n- category: behavioral\n  text: the pages of our Website that you visit, the time and date of your visit, the time spent on those pages\n- category: professional\n  text: your company name (if applicable) and your job title\npurposes:\n- purpose: order fulfilment and delivery\n  text: enable you to access and use Shippit’s services and our Website, including order fulfilment, delivery of\n    goods to parcel recipients and the processing of refunds\n- purpose: fraud checks\n  text: conduct fraud checks\n- purpose: marketing\n  text: conducting marketing activities e.g. promoting new service offerings or inviting you to events\n- purpose: service improvement\n  text: develop, operate and improve our service and organisational processes\nretention: []\nresidency:\n- region: country of collection\n  text: We endeavour to retain your information and personal information on servers located in your country.\ntransfers:\n\
  - mechanism: other\n  text: we will take reasonable steps to ensure that the third party does not breach the privacy obligations relating\n    to your personal information (e.g. by entering into an enforceable contractual arrangement with the overseas\n    recipient\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: withdraw consent\n  text: You have the right to withdraw your consent at any time by contacting our Privacy / Data Protection Officer\n- right: opt out of marketing\n  text: You can choose to not receive these communications from us at any time and you may opt out by following\n    the opt-out instructions\n- right: complaint to data protection authority\n  text: you have the right to contact the relevant local data protection authority to lodge a complaint\nsale_or_sharing:\n  stance: prohibited\n  text: We will not sell your personal information to other people\n"
source_yaml_url: https://artifacts.apis.io/shippit/privacy/shippit-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- transfers
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Shippit's own page on 2026-11-10.
synthetic: false
tags:
- Shipping
- Logistics
- Fulfillment
- Australia
- Asia Pacific
- Multi-Carrier
- Labels
- Tracking
- Parcel
- E-commerce Logistics
- Software-as-a-Service
---
