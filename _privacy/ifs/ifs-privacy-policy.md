---
api_specs:
- filename: ifs-finance-api-openapi.yml
  format: yaml
  label: IFS Finance API
  slug: ifs-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-finance-api-openapi.yml
- filename: ifs-inventory-api-openapi.yml
  format: yaml
  label: IFS Inventory API
  slug: ifs-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-inventory-api-openapi.yml
- filename: ifs-procurement-api-openapi.yml
  format: yaml
  label: IFS Procurement API
  slug: ifs-procurement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-procurement-api-openapi.yml
- filename: ifs-work-orders-api-openapi.yml
  format: yaml
  label: IFS Work Orders API
  slug: ifs-work-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ifs/openapi/ifs-work-orders-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, title and company
  - category: contact
    text: you may be required to provide information and personal data about yourself, such as your name, title and company
  - category: device
    text: your device ID, operating system name and version, browser type and device manufacturer and model
  - category: location
    text: We may derive your approximate location from your IP address.
  - category: behavioral
    text: the pages you visit and features you use
  deletion:
    route: contact privacy@ifs.com
    text: we will delete that data from our systems upon request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate, improve and personalize website and services
    text: IFS uses the information we collect to operate, improve, administer and personalize the website and services we offer.
  - purpose: targeted advertising
    text: We also use this information to help select and display targeted advertisements that we believe may be of interest to you.
  - purpose: site analytics
    text: Such analytics help us operate and improve the performance of these sites and services.
  - purpose: communication
    text: We may also use the information to communicate with you if we have a lawful basis to do so.
  retention:
  - period: null
    scope: personal data
    text: IFS will not retain your personal data longer than is necessary to fulfill the purposes for which it was collected or as required by applicable laws or regulations.
  rights:
  - right: access
    text: You have the right to request access and further information concerning the processing of your information.
  - right: rectification, erasure, restriction
    text: You have a right to request that IFS change, rectify, complete, erase or restrict the processing of your personal data.
  - right: data portability
    text: For processing of personal data that is based on the legal basis consent or fulfilment of agreement you also have the right to data portability.
  - right: withdraw consent
    text: You have a right to withdraw your consent (if our processing is based on consent)
  - right: complaint
    text: you may file a complaint to the competent data protection authority.
  role:
    text: IFS Aktiebolag (Swedish company reg. no 556122-0996) Teknikringen 5, 581 15 Linköping, Sweden (“IFS”) is the data controller for the purposes of this privacy statement.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal data to third parties for marketing purposes unless you have granted us permission to do so.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: this may include the use of intercompany or external data processing agreements based on EU approved Standard Contractual Clauses or EU-US Privacy Shield
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IFS
provenance_date: '2026-11-09'
provider_name: IFS
provider_slug: ifs
slug: ifs-privacy-policy
source_date: '2026-11-09'
source_filename: ifs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ifs.com/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IFS\naid: ifs\nurl: https://www.ifs.com/en/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: IFS Aktiebolag (Swedish company reg. no 556122-0996) Teknikringen 5, 581 15 Linköping, Sweden (“IFS”) is\n    the data controller for the purposes of this privacy statement.\ndata_categories:\n- category: identifying\n  text: such as your name, title and company\n- category: contact\n  text: you may be required to provide information and personal data about yourself, such as your name, title and\n    company\n- category: device\n  text: your device ID, operating system name and version,\
  \ browser type and device manufacturer and model\n- category: location\n  text: We may derive your approximate location from your IP address.\n- category: behavioral\n  text: the pages you visit and features you use\npurposes:\n- purpose: operate, improve and personalize website and services\n  text: IFS uses the information we collect to operate, improve, administer and personalize the website and services\n    we offer.\n- purpose: targeted advertising\n  text: We also use this information to help select and display targeted advertisements that we believe may be of\n    interest to you.\n- purpose: site analytics\n  text: Such analytics help us operate and improve the performance of these sites and services.\n- purpose: communication\n  text: We may also use the information to communicate with you if we have a lawful basis to do so.\nretention:\n- scope: personal data\n  period: null\n  text: IFS will not retain your personal data longer than is necessary to fulfill the purposes for\
  \ which it was\n    collected or as required by applicable laws or regulations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: this may include the use of intercompany or external data processing agreements based on EU approved Standard\n    Contractual Clauses or EU-US Privacy Shield\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact privacy@ifs.com\n  text: we will delete that data from our systems upon request.\nrights:\n- right: access\n  text: You have the right to request access and further information concerning the processing of your information.\n- right: rectification, erasure, restriction\n  text: You have a right to request that IFS change, rectify, complete, erase or restrict the processing of your\n    personal data.\n- right: data portability\n  text: For processing of personal data that is based on the legal basis consent or fulfilment of agreement you\n    also have the right to data portability.\n\
  - right: withdraw consent\n  text: You have a right to withdraw your consent (if our processing is based on consent)\n- right: complaint\n  text: you may file a complaint to the competent data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal data to third parties for marketing purposes unless you have granted\n    us permission to do so.\n"
source_yaml_url: https://artifacts.apis.io/ifs/privacy/ifs-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from IFS's own page on 2026-11-09.
synthetic: false
tags:
- ERP
- Field Service Management
- Asset Management
- Manufacturing
- Energy
- Cloud
- Sweden
---
